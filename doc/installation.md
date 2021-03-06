# Installation

## Aureli-Cli

Run `npm i aurelia-orm --save` from your project root.

Aurelia-orm has submodules and makes use of `extends`, `get-prop`, `typer` and `aurelia-validation@0.6.6`. So, add following to the `build.bundles.dependencies` section of `aurelia-project/aurelia.json`.

```js
"dependencies": [
  // ...
  "extends",
  "get-prop",
  "typer",
  {
    "name": "aurelia-orm",
    "path": "../node_modules/aurelia-orm/dist/amd",
    "main": "aurelia-orm"
  },
  {
  "name": "aurelia-validation",
  "path": "../node_modules/aurelia-validation/dist/amd",
  "main": "index"
  },
  // ...
],
```

## Jspm

Run `jspm i aurelia-orm`

Aurelia-orm has submodules. They are imported in it's main file, so no further action is required.

If the installation results in having forks, try resolving them by running:

```sh
jspm inspect --forks
jspm resolve --only registry:package-name@version
```

E.g.

```sh
jspm inspect --forks
>     Installed Forks
>         npm:aurelia-dependency-injection 1.0.0-beta.1.2.3 1.0.0-beta.2.1.0

jspm resolve --only npm:aurelia-dependency-injection@1.0.0-beta.2.1.0
```

## Webpack

Run `npm i aurelia-orm --save` from your project root.

Add `'aurelia-orm'` in the `coreBundles.aurelia section` of your `webpack.config.js`.

Aurelia-orm has several submodules. They are included in it's package.json, so no further action is required.

## Typescript

Add to your `typings.json`

```js
"aurelia-orm": "github:spoonx/aurelia-orm",
```

and run `typings i`

or run

```sh
typings i github:spoonx/aurelia-orm
```
