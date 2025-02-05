# Changelog

### [1.1.2](https://www.github.com/zachowj/hass-node-red/compare/v1.1.1...v1.1.2) (2022-09-30)


### Bug Fixes

* **sensor:** Update state class on new discovery message ([280061b](https://www.github.com/zachowj/hass-node-red/commit/280061b0b43ae490ce0c37ffeec61fb25d7a00f4))

### [1.1.1](https://www.github.com/zachowj/hass-node-red/compare/v1.1.0...v1.1.1) (2022-09-21)


### Bug Fixes

* Return device info ([3a10a71](https://www.github.com/zachowj/hass-node-red/commit/3a10a71a1e4ad98521233ef3504bb879ecd04358))

## [1.1.0](https://www.github.com/zachowj/hass-node-red/compare/v1.0.9...v1.1.0) (2022-09-21)


### Features

* Add websocket command to remove device ([075e0f1](https://www.github.com/zachowj/hass-node-red/commit/075e0f133169ccc3d48a37df904aa0b19e79c3f2))
* Add websocket command to update config dynamically ([075e0f1](https://www.github.com/zachowj/hass-node-red/commit/075e0f133169ccc3d48a37df904aa0b19e79c3f2))


### Bug Fixes

* Fix import that was moved in HA ([abe7411](https://www.github.com/zachowj/hass-node-red/commit/abe741126855800ad61ceaabb7961dd4de482eb9))
* Use the correct Date type for device classes ([2e23897](https://www.github.com/zachowj/hass-node-red/commit/2e238970bc19abffca6ec3da56e47516532a6250))

### [1.0.9](https://www.github.com/zachowj/hass-node-red/compare/v1.0.8...v1.0.9) (2022-07-08)


### Bug Fixes

* Remove domains key from hacs.json ([60e389e](https://www.github.com/zachowj/hass-node-red/commit/60e389ed55d55f84cac3f4dcae535134934a43ea))
* Remove iot_class from hacs.json ([8d7fa98](https://www.github.com/zachowj/hass-node-red/commit/8d7fa980e2a620289b30ea4f12d7526cfa55273d))
* remove update listener on entry unload to avoid multiple listeners ([73dfce5](https://www.github.com/zachowj/hass-node-red/commit/73dfce507ae1ad206ac0bbc8b085d2727263a19c))


### Documentation

* Create French translation. ([#132](https://www.github.com/zachowj/hass-node-red/issues/132)) ([1b1cc39](https://www.github.com/zachowj/hass-node-red/commit/1b1cc39f49837dd91852893a391ef2f5b8d473fe))

### [1.0.8](https://www.github.com/zachowj/hass-node-red/compare/v1.0.7...v1.0.8) (2022-04-15)


### Bug Fixes

* Use enum for device automation type ([205df7b](https://www.github.com/zachowj/hass-node-red/commit/205df7b8aa2a872876ce0557cb3d15abd1a89168))


### Documentation

* Add Swedish translation ([21f1932](https://www.github.com/zachowj/hass-node-red/commit/21f193207b536ebe19b0acc49d311d67d774d6a6))

### [1.0.7](https://www.github.com/zachowj/hass-node-red/compare/v1.0.6...v1.0.7) (2022-04-03)


### Bug Fixes

* Add Companion to component title in config ([7079554](https://www.github.com/zachowj/hass-node-red/commit/70795544538f3f5969f0c6557721bd4562d2cf32))


### Documentation

* Add Brazilian Portuguese Translation ([f91adb8](https://www.github.com/zachowj/hass-node-red/commit/f91adb8aaecdd81221eb8ccf48329235ac103c92))
* Add Danish translations ([#112](https://www.github.com/zachowj/hass-node-red/issues/112)) ([2a11f2e](https://www.github.com/zachowj/hass-node-red/commit/2a11f2e0d96fac862a30be7c8b273f1b1acf53ea))
* Add german translation ([#127](https://www.github.com/zachowj/hass-node-red/issues/127)) ([fcc5a4f](https://www.github.com/zachowj/hass-node-red/commit/fcc5a4f09e7a3831699b2a0da6e7b5fd5f81b3f5))
* Rename Brazilian Portuguese Translation ([#125](https://www.github.com/zachowj/hass-node-red/issues/125)) ([2a6df42](https://www.github.com/zachowj/hass-node-red/commit/2a6df4231abea31547b7951097c5e44cc5c95af7))
* Separate install instructions ([ba49e7a](https://www.github.com/zachowj/hass-node-red/commit/ba49e7ac73ec1d531df82acb8e7dcbd3f908ce14))
* Update install instructions in readme ([#117](https://www.github.com/zachowj/hass-node-red/issues/117)) ([3f9e83b](https://www.github.com/zachowj/hass-node-red/commit/3f9e83bc6584eaf7235ec79241769518aff5d19b))

### [1.0.6](https://www.github.com/zachowj/hass-node-red/compare/v1.0.5...v1.0.6) (2022-01-08)


### Bug Fixes

* Allow binary sensors and sensors to be set to unknown by setting state to null ([ab1d854](https://www.github.com/zachowj/hass-node-red/commit/ab1d854ddf4068c6c12daed3d91140474bb051f5)), closes [#102](https://www.github.com/zachowj/hass-node-red/issues/102)
* **sensor:** Convert sensor native state to a datetime when device class is set to timestamp ([90ed37a](https://www.github.com/zachowj/hass-node-red/commit/90ed37a94a4445e5975b83101d4614f2282184cd)), closes [#103](https://www.github.com/zachowj/hass-node-red/issues/103)

### [1.0.5](https://www.github.com/zachowj/hass-node-red/compare/v1.0.4...v1.0.5) (2022-01-01)


### Bug Fixes

* **button:** Add component type ([6f7bab2](https://www.github.com/zachowj/hass-node-red/commit/6f7bab2ada1b093ad487502282c49fb94d637132))

### [1.0.4](https://www.github.com/zachowj/hass-node-red/compare/v1.0.3...v1.0.4) (2021-12-31)


### Bug Fixes

* Fix unit_of_measurement being overridden in the sensor entity ([5224dc7](https://www.github.com/zachowj/hass-node-red/commit/5224dc7c51bc2b8f888b82ced714650d483cf508))

### [1.0.3](https://www.github.com/zachowj/hass-node-red/compare/v1.0.2...v1.0.3) (2021-12-31)


### Miscellaneous Chores

* Force Release 1.0.3 ([641b5ef](https://www.github.com/zachowj/hass-node-red/commit/641b5ef85ad369c0a01c04e7dc0184518eeb129f))

### [1.0.2](https://www.github.com/zachowj/hass-node-red/compare/v1.0.1...v1.0.2) (2021-12-30)


### Bug Fixes

* Change MRO for sensor so correct unit_of_measurement gets called ([d47d2dc](https://www.github.com/zachowj/hass-node-red/commit/d47d2dc76fd3993751d23a2014e3fe79a2b7824e)), closes [#95](https://www.github.com/zachowj/hass-node-red/issues/95)

### [1.0.1](https://www.github.com/zachowj/hass-node-red/compare/v1.0.0...v1.0.1) (2021-12-26)


### Bug Fixes

* Wait for HA to be in a running state before registering device triggers ([0acacdf](https://www.github.com/zachowj/hass-node-red/commit/0acacdf6fd6d7d25de2a3dadf1b5c7fcb82e4995))

## [1.0.0](https://www.github.com/zachowj/hass-node-red/compare/v0.5.4...v1.0.0) (2021-12-19)


### ⚠ BREAKING CHANGES

* Re-add extra_state_attributes as a property function

### Features

* Add state_class and last_reset to sensor class ([6a288e0](https://www.github.com/zachowj/hass-node-red/commit/6a288e002b915a1e6a704dd6b4999c7bb4a10006)), closes [#78](https://www.github.com/zachowj/hass-node-red/issues/78)
* Added button entity ([0763aec](https://www.github.com/zachowj/hass-node-red/commit/0763aec6d8dbbb31fba785278205cca59c25c101)), closes [#91](https://www.github.com/zachowj/hass-node-red/issues/91)


### Code Refactoring

* Re-add extra_state_attributes as a property function ([541297d](https://www.github.com/zachowj/hass-node-red/commit/541297d8ee6545585c86c05b455a204d3dc30a40))

### [0.5.4](https://www.github.com/zachowj/hass-node-red/compare/v0.5.3...v0.5.4) (2021-12-03)


### Miscellaneous Chores

* release 0.5.4 ([a23b9d6](https://www.github.com/zachowj/hass-node-red/commit/a23b9d6afe8f1fae2a0005eab23f61bc8a7c1702))

### [0.5.3](https://www.github.com/zachowj/hass-node-red/compare/v0.5.2...v0.5.3) (2021-11-30)


### Bug Fixes

* Fix typo in info.md ([19642c2](https://www.github.com/zachowj/hass-node-red/commit/19642c26e1c17fceedb1ab174d95e91fa17e1002)), closes [#76](https://www.github.com/zachowj/hass-node-red/issues/76)
* removed device_state_attributes ([#82](https://www.github.com/zachowj/hass-node-red/issues/82)) ([c5f7e8c](https://www.github.com/zachowj/hass-node-red/commit/c5f7e8cacdbaf3662365437d1068293cae1290da))

### [0.5.2](https://www.github.com/zachowj/hass-node-red/compare/v0.5.0...v0.5.2) (2021-05-03)


### Bug Fixes

* Add iot_class to manifest ([437f807](https://www.github.com/zachowj/hass-node-red/commit/437f807e148534769c8ac76b07542c075a6d26a1))

## [0.5.0](https://www.github.com/zachowj/hass-node-red/compare/v0.4.5...v0.5.0) (2021-04-20)


### Features

* Add device action endpoint and device trigger switch ([b717be9](https://www.github.com/zachowj/hass-node-red/commit/b717be9505c311c8c34dccd2e42d39062a786091))
* **webhook:** send query params to NR ([a17ad73](https://www.github.com/zachowj/hass-node-red/commit/a17ad73a975ba80082e6390d8520e06a0e99c952))


### Documentation

* Add companion to name ([fb971cb](https://www.github.com/zachowj/hass-node-red/commit/fb971cb2df0da65e80ef9cb871c7d6d3bc35d53c))
* Reword webhooks ([d896bc1](https://www.github.com/zachowj/hass-node-red/commit/d896bc1f7dfae37c23a97061ea7e03482bb1b198))
* Update features ([268003d](https://www.github.com/zachowj/hass-node-red/commit/268003d02ee0d138e864b07d02bf4396c6fed217)), closes [#57](https://www.github.com/zachowj/hass-node-red/issues/57)

### [0.4.5](https://www.github.com/zachowj/hass-node-red/compare/v0.4.4...v0.4.5) (2021-03-03)


### Bug Fixes

* Add version to manifest.json ([#56](https://www.github.com/zachowj/hass-node-red/issues/56)) ([94d5ebe](https://www.github.com/zachowj/hass-node-red/commit/94d5ebe3b1295aa568bd894cb3fe3b98cf18e96e))


### Documentation

* Add step about refreshing browser ([d4c24ca](https://www.github.com/zachowj/hass-node-red/commit/d4c24cac8ffdd5ccccffc9d074d87a1bd133e537))
* Update info ([aaa5423](https://www.github.com/zachowj/hass-node-red/commit/aaa54231ea482a8413128add61d79f312934aa1a))
