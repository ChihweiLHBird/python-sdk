# Changelog

## [0.5.0](https://github.com/open-feature/python-sdk/compare/v0.4.2...v0.5.0) (2024-02-20)


### ⚠ BREAKING CHANGES

* add support for domains ([#271](https://github.com/open-feature/python-sdk/issues/271))

### Features

* add support for domains ([#271](https://github.com/open-feature/python-sdk/issues/271)) ([ed6a42f](https://github.com/open-feature/python-sdk/commit/ed6a42f264a6efc149642181bfc4c6de0eb83ce1))

## [0.4.2](https://github.com/open-feature/python-sdk/compare/v0.4.1...v0.4.2) (2024-02-06)


### Features

* add FeatureProvider protocol ([#268](https://github.com/open-feature/python-sdk/issues/268)) ([caa7f36](https://github.com/open-feature/python-sdk/commit/caa7f36c309149bd8d91c214e85f382b026093f6))
* improve logging setup ([#261](https://github.com/open-feature/python-sdk/issues/261)) ([ccbff2c](https://github.com/open-feature/python-sdk/commit/ccbff2c5e46f69274230fc5ddc3cfb90a283d013))
* make return value not optional in provider API functions ([#270](https://github.com/open-feature/python-sdk/issues/270)) ([cb1677b](https://github.com/open-feature/python-sdk/commit/cb1677b0a826ad496f1ffa1074018f1400d84c80))
* make specific fields in HookContext immutable ([#266](https://github.com/open-feature/python-sdk/issues/266)) ([3b89760](https://github.com/open-feature/python-sdk/commit/3b89760d4127a997dadbee920d0e066b2bf08e84))


### Bug Fixes

* Allow string values for `FlagEvaluationDetails.reason` and  `FlagResolutionDetails.reason` ([#264](https://github.com/open-feature/python-sdk/issues/264)) ([5ef6ca1](https://github.com/open-feature/python-sdk/commit/5ef6ca1263d2cebdc7c16177fc182eccd56bae2f))


### Documentation

* document shutdown function ([#237](https://github.com/open-feature/python-sdk/issues/237)) ([95d69e2](https://github.com/open-feature/python-sdk/commit/95d69e27b3f6b9cb9f716ae4b2d5b0879c0253e3))
* update supported spec version ([#269](https://github.com/open-feature/python-sdk/issues/269)) ([1282bab](https://github.com/open-feature/python-sdk/commit/1282bab31ea6a554911a9d37c4c4d3e14ffa5133))

## [0.4.1](https://github.com/open-feature/python-sdk/compare/v0.4.0...v0.4.1) (2023-11-08)


### Bug Fixes

* add PEP 561 py.typed marker file ([#232](https://github.com/open-feature/python-sdk/issues/232)) ([db50494](https://github.com/open-feature/python-sdk/commit/db504946d1aea7e653e5755d703cff3d52b455dd))
* fix types for HookContext.{client,provider}_metadata ([#233](https://github.com/open-feature/python-sdk/issues/233)) ([4bdd384](https://github.com/open-feature/python-sdk/commit/4bdd384544c24f5d9942c1e6261689c6b8ceb7de))
* replace str with enum value in InMemoryFlag definition ([#234](https://github.com/open-feature/python-sdk/issues/234)) ([963b01e](https://github.com/open-feature/python-sdk/commit/963b01e66d6ebe8062beaf3bfa0d034a312c037e))

## [0.4.0](https://github.com/open-feature/python-sdk/compare/v0.3.1...v0.4.0) (2023-11-01)


### ⚠ BREAKING CHANGES

* raise error if the flag wasn't found using the in-memory provider ([#228](https://github.com/open-feature/python-sdk/issues/228))

### Features

* implement initialize/shutdown on provider registration ([#213](https://github.com/open-feature/python-sdk/issues/213)) ([84af1ae](https://github.com/open-feature/python-sdk/commit/84af1aec01241842289bce2beb35486153876706))
* pass flag_metadata from resolution to evaluation details ([#212](https://github.com/open-feature/python-sdk/issues/212)) ([88a204d](https://github.com/open-feature/python-sdk/commit/88a204dc27c435f3b5faec231a07a96cb011518c))


### Bug Fixes

* Hook methods should have default non-abstract implementations ([#216](https://github.com/open-feature/python-sdk/issues/216)) ([c661ab2](https://github.com/open-feature/python-sdk/commit/c661ab20a43ff4411b7f0847c71df886af87e7ed))
* raise error if the flag wasn't found using the in-memory provider ([#228](https://github.com/open-feature/python-sdk/issues/228)) ([0c314ab](https://github.com/open-feature/python-sdk/commit/0c314ab77cd60d3347aea7f733d324a6228e8871))

## [0.3.1](https://github.com/open-feature/python-sdk/compare/v0.3.0...v0.3.1) (2023-09-28)


### Features

* make openfeature an implicit namespace package ([#199](https://github.com/open-feature/python-sdk/issues/199)) ([c544918](https://github.com/open-feature/python-sdk/commit/c544918d65c2b0af621ec9e2261784e9a715dd9d))

## [0.3.0](https://github.com/open-feature/python-sdk/compare/v0.2.0...v0.3.0) (2023-09-25)


### ⚠ BREAKING CHANGES

* rename top-level package to openfeature ([#192](https://github.com/open-feature/python-sdk/issues/192))

### Code Refactoring

* rename top-level package to openfeature ([#192](https://github.com/open-feature/python-sdk/issues/192)) ([51f0d26](https://github.com/open-feature/python-sdk/commit/51f0d260f02cce5ab673305f212770ffcfc0744f))

## [0.2.0](https://github.com/open-feature/python-sdk/compare/v0.1.0...v0.2.0) (2023-09-09)


### ⚠ BREAKING CHANGES

* simplify namespaces to make public API more pythonic ([#172](https://github.com/open-feature/python-sdk/issues/172))
* move api hooks methods to api module ([#169](https://github.com/open-feature/python-sdk/issues/169))
* move api evaluation context methods to api module ([#164](https://github.com/open-feature/python-sdk/issues/164))

### Code Refactoring

* move api evaluation context methods to api module ([#164](https://github.com/open-feature/python-sdk/issues/164)) ([67ba861](https://github.com/open-feature/python-sdk/commit/67ba8619b913c4af25f1af9df2bab863cb7989d0))
* move api hooks methods to api module ([#169](https://github.com/open-feature/python-sdk/issues/169)) ([a7da26f](https://github.com/open-feature/python-sdk/commit/a7da26fd93c5dae33318366f1fc3c8b11e11ddaa))
* simplify namespaces to make public API more pythonic ([#172](https://github.com/open-feature/python-sdk/issues/172)) ([793ced1](https://github.com/open-feature/python-sdk/commit/793ced19177d6f18f7ecbfc0673a520fbbf2a2cd))

## [0.1.0](https://github.com/open-feature/python-sdk/compare/v0.0.9...v0.1.0) (2023-07-25)


### ⚠ BREAKING CHANGES

* EvaluationDetails.reason should be a string, Reason enum should export default reasons per spec ([#126](https://github.com/open-feature/python-sdk/issues/126))

### Features

* EvaluationDetails.reason should be a string, Reason enum should export default reasons per spec ([#126](https://github.com/open-feature/python-sdk/issues/126)) ([c2d225e](https://github.com/open-feature/python-sdk/commit/c2d225e34cefe284288e7fc5a574c1136e0962aa))
* implement api-level hooks ([#139](https://github.com/open-feature/python-sdk/issues/139)) ([7fe511f](https://github.com/open-feature/python-sdk/commit/7fe511ffe023b164f7ad6bd9f41d60b289747268))
* implement client get_metadata for requirement 1.2.2 ([#141](https://github.com/open-feature/python-sdk/issues/141)) ([571f5eb](https://github.com/open-feature/python-sdk/commit/571f5eb3bfe147407e473b36ae8a6c5ad056ebf2))
* implement get_provider_metadata for requirement 1.1.5 ([#140](https://github.com/open-feature/python-sdk/issues/140)) ([695da28](https://github.com/open-feature/python-sdk/commit/695da28c1ed4f65e19bed0fa4a379257d7dc6776))
* implement InMemoryProvider ([#157](https://github.com/open-feature/python-sdk/issues/157)) ([5e7bf1f](https://github.com/open-feature/python-sdk/commit/5e7bf1f8ad6aa6a34f5be322ade92b672ad9b6b6))


### Bug Fixes

* object client methods can receive dict or list as default_value ([#134](https://github.com/open-feature/python-sdk/issues/134)) ([291581f](https://github.com/open-feature/python-sdk/commit/291581fbceb5abbe267d63c9c7e94d4cd34cef21))
* return correct type object in OpenFeatureClient._create_provider_evaluation ([#136](https://github.com/open-feature/python-sdk/issues/136)) ([052e149](https://github.com/open-feature/python-sdk/commit/052e149ec530c71efed6d8c478d09b9772505153))
* use str values in FlagType enum for easier typing ([#137](https://github.com/open-feature/python-sdk/issues/137)) ([292a0df](https://github.com/open-feature/python-sdk/commit/292a0dfc0ba6e0d2baa6cd0cb87351b8b02ef13a))


### Documentation

* simplified the under development warning ([0926a68](https://github.com/open-feature/python-sdk/commit/0926a68de69dfe5dba0f7af49daaa07e3383aed5))

## [0.0.9](https://github.com/open-feature/python-sdk/compare/v0.0.8...v0.0.9) (2023-01-19)


### Bug Fixes

* reverse the merged before hooks ([#71](https://github.com/open-feature/python-sdk/issues/71)) ([3a33551](https://github.com/open-feature/python-sdk/commit/3a33551fdbd01c876920177ab2035d0e24e17572))


### Documentation

* add NoOpProvider import to config sample ([#68](https://github.com/open-feature/python-sdk/issues/68)) ([643d9fa](https://github.com/open-feature/python-sdk/commit/643d9fa34f94f6ca1f9a5d4251097a3f98dae43e))

## [0.0.8](https://github.com/open-feature/python-sdk/compare/v0.0.7...v0.0.8) (2022-12-28)


### Features

* defaults to NoOpProvider ([#66](https://github.com/open-feature/python-sdk/issues/66)) ([9276d35](https://github.com/open-feature/python-sdk/commit/9276d3579881049f8412e329f0ceec7df56e914b))

## [0.0.7](https://github.com/open-feature/python-sdk/compare/v0.0.6...v0.0.7) (2022-12-19)


### Bug Fixes

* Get Object should return both list and dict ([#64](https://github.com/open-feature/python-sdk/issues/64)) ([85db1e0](https://github.com/open-feature/python-sdk/commit/85db1e0a748bc131bbdb9f8996284b13480b3a33))

## [0.0.6](https://github.com/open-feature/python-sdk/compare/v0.0.5...v0.0.6) (2022-12-02)


### Features

* process flag evaluation options in client ([#31](https://github.com/open-feature/python-sdk/issues/31)) ([6f6186e](https://github.com/open-feature/python-sdk/commit/6f6186ed910be12579c10e6e5d693867093cf4b2))

## [0.0.5](https://github.com/open-feature/python-sdk/compare/v0.0.4...v0.0.5) (2022-11-22)


### Bug Fixes

* Fix type checking ([#25](https://github.com/open-feature/python-sdk/issues/25)) ([50f5a48](https://github.com/open-feature/python-sdk/commit/50f5a484a012167aeebac4d99a47a336d146e243))


### Documentation

* Update pip install instructions ([#57](https://github.com/open-feature/python-sdk/issues/57)) ([dc6ed6f](https://github.com/open-feature/python-sdk/commit/dc6ed6f6d744d694ad08c5330c8c3d16189d9de3))

## [0.0.4](https://github.com/open-feature/python-sdk/compare/v0.0.3...v0.0.4) (2022-11-15)


### Features

* Add needs to release job ([#52](https://github.com/open-feature/python-sdk/issues/52)) ([fb7655a](https://github.com/open-feature/python-sdk/commit/fb7655aa3aae0fb021e0aae57c0a7d182a8218cf))

## [0.0.3](https://github.com/open-feature/python-sdk/compare/v0.0.2...v0.0.3) (2022-11-15)


### Features

* Run a single container for sdk release ([#50](https://github.com/open-feature/python-sdk/issues/50)) ([87c62cf](https://github.com/open-feature/python-sdk/commit/87c62cfae7ce2bd47ed79adb7bb9b58d3b0072fd))

## [0.0.2](https://github.com/open-feature/python-sdk/compare/v0.0.1...v0.0.2) (2022-11-15)


### Features

* Add metadata to providers ([#26](https://github.com/open-feature/python-sdk/issues/26)) ([b39cced](https://github.com/open-feature/python-sdk/commit/b39cced329d16741aa8fa8768fd44ff51f916bfa))
* Add release please to handle releases ([#45](https://github.com/open-feature/python-sdk/issues/45)) ([5bc0571](https://github.com/open-feature/python-sdk/commit/5bc057192d69659d17b9552cae854843a86d879c))
* Fix release workflow ([#48](https://github.com/open-feature/python-sdk/issues/48)) ([2c44d55](https://github.com/open-feature/python-sdk/commit/2c44d55af349e9485a3f697f28c1391cc11c5ed0))
* spec-0.2.0 ([#38](https://github.com/open-feature/python-sdk/issues/38)) ([311b8ee](https://github.com/open-feature/python-sdk/commit/311b8eef53cfd535f8f45e5cd680381cc79abbc1))
* specification-0.5.0 ([#44](https://github.com/open-feature/python-sdk/issues/44)) ([04a4323](https://github.com/open-feature/python-sdk/commit/04a432331036cf771a613dd66dcc46c4e10d9284))


### Bug Fixes

* eval context fixes and new error types ([#43](https://github.com/open-feature/python-sdk/issues/43)) ([06d0494](https://github.com/open-feature/python-sdk/commit/06d0494331b62deb0c0ec96846ffed5ab8471e60))
* Move flag evaluation details to a dataclass ([#27](https://github.com/open-feature/python-sdk/issues/27)) ([b44224b](https://github.com/open-feature/python-sdk/commit/b44224be0ddaf3745d031d6e7caea19f41322cf1))
* requirements-dev.txt to reduce vulnerabilities ([#37](https://github.com/open-feature/python-sdk/issues/37)) ([1e82122](https://github.com/open-feature/python-sdk/commit/1e82122978e92173fab3c65c75ca3b5477ce3655))
* Unit tests ([#28](https://github.com/open-feature/python-sdk/issues/28)) ([df0c033](https://github.com/open-feature/python-sdk/commit/df0c03308346c5b3be7223edc162582c578b4678))


### Documentation

* add badge showing supported Python version range ([c2d214a](https://github.com/open-feature/python-sdk/commit/c2d214a809bf2b9f12f50dc8a5a6aec32f9d1dca))
* add badge showing supported Python version range ([f845d9e](https://github.com/open-feature/python-sdk/commit/f845d9e4184ca9328311906c825d42b2cc73a319))
