<a name="3.0.0-rc5"></a>
## [3.0.0-rc5](https://github.com/SpoonX/aurelia-orm/compare/3.0.0-rc2...v33.0.0-rc5) (2016-07-22)


### Bug Fixes

* **aurelia-orm:** export Repository ([c99d4c6](https://github.com/SpoonX/aurelia-orm/commit/c99d4c6))
* **component:** association select has bindable resource property ([e037efa](https://github.com/SpoonX/aurelia-orm/commit/e037efa))
* **component:** association select\'s resource bindable  can also reference repo instance ([48ae57a](https://github.com/SpoonX/aurelia-orm/commit/48ae57a))
* **component:** bindable multiple for association select component ([ad68275](https://github.com/SpoonX/aurelia-orm/commit/ad68275))
* **decorators:** no return ([2274878](https://github.com/SpoonX/aurelia-orm/commit/2274878))
* **depend:** fix paged dependencies, move components docs ([89b5b35](https://github.com/SpoonX/aurelia-orm/commit/89b5b35))
* **entity:** fix reset and test ([51dd588](https://github.com/SpoonX/aurelia-orm/commit/51dd588))
* **entity:** use getId for collections ([224cade](https://github.com/SpoonX/aurelia-orm/commit/224cade))


### Features

* **association-select:** Added resource attribute (no more need for a repository) ([8badedc](https://github.com/SpoonX/aurelia-orm/commit/8badedc))
* **component:** add paged component ([23df688](https://github.com/SpoonX/aurelia-orm/commit/23df688))
* **component:** association select with identifier bindable ([9f67554](https://github.com/SpoonX/aurelia-orm/commit/9f67554))
* **decorators:** data decorator for generic entity property data ([c7faf9e](https://github.com/SpoonX/aurelia-orm/commit/c7faf9e))
* **entity:** added entity.reset(shallow) ([b237d67](https://github.com/SpoonX/aurelia-orm/commit/b237d67))
* **entity:** allow custom id property names. Use [@idProperty](https://github.com/idProperty)() decorator to set a custom id property name ([6d2f9b1](https://github.com/SpoonX/aurelia-orm/commit/6d2f9b1))
* **entity:** prevent accidental infinite loops ([2cb9527](https://github.com/SpoonX/aurelia-orm/commit/2cb9527))
* **entity:** setData with optional markClean ([ee01480](https://github.com/SpoonX/aurelia-orm/commit/ee01480))


<a name"3.0.0-rc2"></a>
### 3.0.0-rc2 (2016-05-04)


#### Bug Fixes

* **metadata:** use metadata.getOrCreateOwn 's optional targettKey for TS to circumvent TS's 'ex ([75c23d03](https://github.com/SpoonX/aurelia-orm/commit/75c23d03))


<a name"3.0.0-rc1"></a>
## 3.0.0-rc1 (2016-04-28)


#### Bug Fixes

* **build:** current bundling with folders doesn't work. ([eef385fa](https://github.com/SpoonX/aurelia-orm/commit/eef385fa))
* **d.ts:** include only necessary imports ([a0ff34c7](https://github.com/SpoonX/aurelia-orm/commit/a0ff34c7))


#### Features

* **bundle:** import association select for convinient bundling ([a081f361](https://github.com/SpoonX/aurelia-orm/commit/a081f361))
* **entity:** Save new children and mark as dirty when children added or removed. ([37f6b515](https://github.com/SpoonX/aurelia-orm/commit/37f6b515))
* **project:**
  * Rename project to remove spoonx prefix. enable npm installation ([c2b977fe](https://github.com/SpoonX/aurelia-orm/commit/c2b977fe))
  * bundle into single file ([91581443](https://github.com/SpoonX/aurelia-orm/commit/91581443))


#### Breaking Changes

* `spoonx/` prefix dropped from install name for orm and api. Update `package.json` and `config.js` accordingly.

 ([c2b977fe](https://github.com/SpoonX/aurelia-orm/commit/c2b977fe))
* all imports but components need to use 'aurelia-orm'

 ([91581443](https://github.com/SpoonX/aurelia-orm/commit/91581443))


<a name"2.2.3"></a>
### 2.2.3 (2016-03-26)


#### Bug Fixes

* **project:** fix wrong dependency introduced in 2.2.2 ([ae8a42d0](https://github.com/SpoonX/aurelia-orm/commit/ae8a42d0))


<a name"2.2.2"></a>
### 2.2.2 (2016-03-25)


<a name"2.2.1"></a>
### 2.2.1 (2016-03-25)


#### Features

* **project:** add d.ts file ([6a6368ce](https://github.com/SpoonX/aurelia-orm/commit/6a6368ce))


<a name"2.2.0"></a>
## 2.2.0 (2016-03-05)


#### Features

* **entity:** Create child when new, upon adding ([a2ff99d9](https://github.com/SpoonX/aurelia-orm/commit/a2ff99d9))


<a name"2.1.1"></a>
### 2.1.1 (2016-03-02)


## 2.1.0 (2016-02-23)


#### Features

* **decorator:** Added type decorator ([3e70062e](https://github.com/SpoonX/aurelia-orm/commit/3e70062e0f11d82bdadc80985a1eba625a152182))
* **project:** Expose type decorator from project index ([e20459cc](https://github.com/SpoonX/aurelia-orm/commit/e20459cca82ffa2b5196ec1bcf03f0487b29a591))
* **repository:** Cast values if they have type decorators ([a40d7632](https://github.com/SpoonX/aurelia-orm/commit/a40d7632f856a78ff78c0428075c78f90af67a68))


<a name"2.0.3"></a>
## 2.0.3 (2016-01-25)


#### Bug Fixes

* **repository:** retrieved single entitiy marked clean ([be0b5d13](https://github.com/SpoonX/aurelia-orm/commit/be0b5d13))


<a name"2.0.2"></a>
### 2.0.2 (2016-01-24)


#### Bug Fixes

* **project:**
  * removed aurelia-framework dependency and imported directly ([a23194b5](https://github.com/SpoonX/aurelia-orm/commit/a23194b5))


<a name"2.0.1"></a>
### 2.0.1 (2016-01-24)


#### Bug Fixes

* **project:** systemjs module loader ([126dbaf8](https://github.com/SpoonX/aurelia-orm/commit/126dbaf8))


## 2.0.0 (2016-01-17)


#### Features

* **decorator:** Added @endpoint() decorator ([36d58cd1](https://github.com/SpoonX/aurelia-orm/commit/36d58cd133b58491774b9f90c65c2208405c0b86))
* **project:** Expose @endpoint() decorator ([8a0c107a](https://github.com/SpoonX/aurelia-orm/commit/8a0c107acef3cf351faec14b2b7c607c64b7ec78))


## 1.4.0 (2016-01-06)


#### Bug Fixes

* **repository:** Mark entities as clean upon calling .find() ([b689329e](https://github.com/SpoonX/aurelia-orm/commit/b689329e4b2c08ab63752959c0be83f9cb26fecd))
* **test:** Stop server after build tests ([c1c7a1ed](https://github.com/SpoonX/aurelia-orm/commit/c1c7a1edd118877d8813064fa199886c02fb306f))


#### Features

* **association-select:** Added support for `multiple` ([f5809016](https://github.com/SpoonX/aurelia-orm/commit/f5809016b730a4bcac5e6749b1168ccdad2b89db))
* **entity:** Added support for collection associations (add / remove) ([e3c24718](https://github.com/SpoonX/aurelia-orm/commit/e3c24718f53bee7b999a9a9ec46ca082a7d10dba))
* **entity-manager:** Set repository on new entities and allow easier entity registering ([2ae8ad1a](https://github.com/SpoonX/aurelia-orm/commit/2ae8ad1ad4309363dc58cd8c05715bfdb872b0eb))


### 1.3.1 (2015-12-29)


#### Features

* **decorator:** Added @name decorator ([819f6596](https://github.com/SpoonX/aurelia-orm/commit/819f65966d1bda811ac3009827a544e7f7c40643))
* **entity:** Added .getName() methods for instance and static ([f65d78fb](https://github.com/SpoonX/aurelia-orm/commit/f65d78fb97fd6d733c7083e2be77346639553b5b))


## 1.3.0 (2015-12-28)


#### Bug Fixes

* **watch:** Run sync, to prevent errors from race conditions ([19cc4b0c](https://github.com/SpoonX/aurelia-orm/commit/19cc4b0c0896e4384cc09a4b3fd3474a54a6ae6e))


#### Features

* **entity:**
  * Added .isNew() method ([884ec051](https://github.com/SpoonX/aurelia-orm/commit/884ec0518ab4659102e0b7636fdcadec2f961032))
  * Added .isDirty() method ([e2bb595f](https://github.com/SpoonX/aurelia-orm/commit/e2bb595f0a021f8bd3a28625cfab32175db9309f))
  * Added .isClean() method ([46b499c9](https://github.com/SpoonX/aurelia-orm/commit/46b499c9ab56303ffe0572369fa024a60cc4537d))
  * Added .markClean() method ([b333f25a](https://github.com/SpoonX/aurelia-orm/commit/b333f25a502a56e2c40e8c548de0554a2bfb6b90))


### 1.2.4 (2015-12-28)


#### Bug Fixes

* **association-select:** Remove populate criteria for many-assoc ([bc41d4ea](https://github.com/SpoonX/aurelia-orm/commit/bc41d4ea3f0bba4664ce4293d7d315caa845fe2e))


### 1.2.3 (2015-12-23)


#### Bug Fixes

* **association-select:** Return promise on load ([2cc220a5](https://github.com/SpoonX/aurelia-orm/commit/2cc220a5b39d195d9de2e10e29bb8311809a1ee4))


### 1.2.2 (2015-12-22)


#### Bug Fixes

* **association-select:** Properly load initial data ([2a952b23](https://github.com/SpoonX/aurelia-orm/commit/2a952b2344c11d3654f408ebb73f28652fcba61d))


### 1.2.1 (2015-12-22)


#### Bug Fixes

* **repository:** Faulthy return value in docblock ([58d5240f](https://github.com/SpoonX/aurelia-orm/commit/58d5240f415d66bcc6630e3e681338c946b59560))


#### Features

* **association-select:** Added a new custom element ([ab5d456f](https://github.com/SpoonX/aurelia-orm/commit/ab5d456f468b7cab92cbec6ed62dc5b03150a4e6))


## 1.2.0 (2015-12-21)


#### Features

* **repository:** Added findPath and getResource methods for flexibility. ([2f32bafd](https://github.com/SpoonX/aurelia-orm/commit/2f32bafd3eba087dcbe49b1f6f58727066c0d514))
* **validator:**
  * Add validation rule for associations to validator ([30fb1dd1](https://github.com/SpoonX/aurelia-orm/commit/30fb1dd1918d561c8ac2a99708af962224824c9e))
  * Added validation rule for associations ([350c9e31](https://github.com/SpoonX/aurelia-orm/commit/350c9e31570e616035b0e52a43b57d226c4fbd8f))


### 1.1.4 (2015-12-17)


### 1.1.3 (2015-12-16)


#### Features

* **repository:** Added support for new populated entity ([54ba6468](https://github.com/SpoonX/aurelia-orm/commit/54ba646813dcea973acd8d0603872ae92e8b01f2))


### 1.1.2 (2015-12-08)
* Added info to README

### 1.1.1 (2015-12-07)
* Reformat according to CS
* Removed unused dependency
* Removed unused imports
* Added lint to test command

### 1.1.0 (2015-12-07)
* Lazy-load validation
* Added tests for new use cases

### 1.0.0 (2015-12-04)
* Normalized api
* Added full test suite
* Added decorators for common configurations
* Added documentation

### 0.2.0 (2015-12-01)
* Added association annotation
* Added support for nested populates
* Added shallow .save() for associations
