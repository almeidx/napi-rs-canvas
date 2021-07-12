## [0.0.10](https://github.com/Brooooooklyn/canvas/compare/v0.0.9...v0.0.10) (2021-07-12)

### Bug Fixes

- missing registerFromPath implementation ([8bac515](https://github.com/Brooooooklyn/canvas/commit/8bac515eac3c8bf5db026f701a57ee839fedb42d))

## [0.0.9](https://github.com/Brooooooklyn/canvas/compare/v0.0.8...v0.0.9) (2021-07-11)

### Features

- upgrade skia to chrome/m92 latest ([584a02a](https://github.com/Brooooooklyn/canvas/commit/584a02aef28516dd18d675a8f90c1f25dceae129))

## [0.0.8](https://github.com/Brooooooklyn/canvas/compare/v0.0.7...v0.0.8) (2021-06-23)

### Features

- support conic gradient ([850b6ee](https://github.com/Brooooooklyn/canvas/commit/850b6ee4f7df8ce440574fc41c16e8559ef1f232))
- support webp output ([4948c49](https://github.com/Brooooooklyn/canvas/commit/4948c49f89ea4e423dc14b240c82cb4d5e917248))

## [0.0.7](https://github.com/Brooooooklyn/canvas/compare/v0.0.6...v0.0.7) (2021-06-21)

### Bug Fixes

- **deps:** update rust crate once_cell to 1.8 ([c859162](https://github.com/Brooooooklyn/canvas/commit/c859162650590648d45e64782a104a5144a033bf))
- **deps:** update rust crate regex to 1.5 ([1915c60](https://github.com/Brooooooklyn/canvas/commit/1915c608fcb7318ce778f687c3ca08543203820f))
- JsArrayBuffer usage ([b58e987](https://github.com/Brooooooklyn/canvas/commit/b58e987bc7e92d5547e749b377720e1900454172))

### Features

- support jpeg output ([76adbdc](https://github.com/Brooooooklyn/canvas/commit/76adbdc04cd02f868fde9da21851694f10f15ce5))
- support svg source in image ([8df688f](https://github.com/Brooooooklyn/canvas/commit/8df688f702967fb60c75fceda52cbcf08a72be37))

## [0.0.6](https://github.com/Brooooooklyn/canvas/compare/v0.0.5...v0.0.6) (2021-05-06)

### Bug Fixes

- windows setAssetFontManager crash ([54861e9](https://github.com/Brooooooklyn/canvas/commit/54861e9b3b5fe18cbcd791b65b05c98b40087d42))

### Features

- add .editorconfig file ([62dcf35](https://github.com/Brooooooklyn/canvas/commit/62dcf35b6cdc11e3154af178b04e091aa09e3ac9))
- add font collection singleton scaffold ([9b7a00a](https://github.com/Brooooooklyn/canvas/commit/9b7a00a1eb2cef311cce8409fb37df359d3ab39e))
- support GlobalFonts.families ([00be237](https://github.com/Brooooooklyn/canvas/commit/00be237c08eff287ce706b30dd3ceda3e40727f6))
- support GlobalFonts.has ([0461afc](https://github.com/Brooooooklyn/canvas/commit/0461afcf8efc6ec49e2722f5f124c4bada45a48b))
- support GlobalFonts.register ([295d507](https://github.com/Brooooooklyn/canvas/commit/295d5072de571f1c6b04b930c99f6290f20149a4))

## [0.0.5](https://github.com/Brooooooklyn/canvas/compare/v0.0.4...v0.0.5) (2021-05-04)

### Bug Fixes

- **path:** wrong Stroke type cast and miterLimit default value ([5f1761b](https://github.com/Brooooooklyn/canvas/commit/5f1761b602c992639ab511336fc0551d061c8d5c))
- add stroke to trim test to make it more visually recognizable ([bddb3c6](https://github.com/Brooooooklyn/canvas/commit/bddb3c6ef96f588f36760f69e5077db56417d7cb))

### Features

- add getFillTypeString() for PathKit ([44719de](https://github.com/Brooooooklyn/canvas/commit/44719de4d119ffe370b0c6df26072303d8707a85))
- add PathKit.dash() ([#238](https://github.com/Brooooooklyn/canvas/issues/238)) ([c238113](https://github.com/Brooooooklyn/canvas/commit/c238113ef1feafd179d6c190e2a29e51326737d3))

## [0.0.4](https://github.com/Brooooooklyn/canvas/compare/v0.0.3...v0.0.4) (2021-04-19)

### Bug Fixes

- parse error for single font size rules ([aa80fb7](https://github.com/Brooooooklyn/canvas/commit/aa80fb7109584b32bf6a66ae7d70753ec53882b6))

### Features

- **path2d:** implement pathkit functions ([eea95bf](https://github.com/Brooooooklyn/canvas/commit/eea95bf627a8c643155618fa5e662c6060f73365))
- skia chrome/m91, add back mimalloc ([0420c14](https://github.com/Brooooooklyn/canvas/commit/0420c14339b2ef9c886d0495bddeb30c0af31f1d))

## [0.0.3](https://github.com/Brooooooklyn/canvas/compare/v0.0.2...v0.0.3) (2021-03-27)

### Bug Fixes

- wrong package name in index.js ([e3c35bb](https://github.com/Brooooooklyn/canvas/commit/e3c35bb0611f5d75f52d481738affdd530e1ac5a))

## [0.0.2](https://github.com/Brooooooklyn/canvas/compare/v0.0.1-alpha.3...v0.0.2) (2021-03-27)

### Bug Fixes

- bitmap destructor ([b138da2](https://github.com/Brooooooklyn/canvas/commit/b138da228286f560fe7aebe4e12ef5fc2ddf8e25))
- build on windows ([b731ea8](https://github.com/Brooooooklyn/canvas/commit/b731ea84d529d0a971b2fe34c20eb654f1fa9f34))
- compat with Node.js readonly error messages ([c7e1764](https://github.com/Brooooooklyn/canvas/commit/c7e176440b4d167b03e988059a9e8a34169da9a7))
- eslint & vscode config ignore ([f7dd018](https://github.com/Brooooooklyn/canvas/commit/f7dd018a81ff8dee0845258ef13e488c985f160f))
- image shadow ([8396b93](https://github.com/Brooooooklyn/canvas/commit/8396b93f4634705d1f0dfdb2028afb6fa3b25a99))
- image src getter ([336549d](https://github.com/Brooooooklyn/canvas/commit/336549d8f56b3e93687760b485d4a9d8cd72c6b4))
- setters on readonly properties ([adac797](https://github.com/Brooooooklyn/canvas/commit/adac797e5af7dd1407e05f6c3084dfa725161b6b))
- sync lock file ([340bfb5](https://github.com/Brooooooklyn/canvas/commit/340bfb571187635d041129eaf0c9e365bc7c336d))
- transform matrix config ([9dcddf2](https://github.com/Brooooooklyn/canvas/commit/9dcddf293c25c19a3d93b058d3ba78b43d52a281))

### Features

- add drawImage poc ([a5e5ddf](https://github.com/Brooooooklyn/canvas/commit/a5e5ddf52fc1be006590dcd63aad1ac53d2f5a1d))
- add image class poc ([11e04a5](https://github.com/Brooooooklyn/canvas/commit/11e04a597d2d0153bd5a15da2aabd6bec08efb0e))
- add image SkData field poc ([bb0c108](https://github.com/Brooooooklyn/canvas/commit/bb0c108d80da525efdb61a9b8653041f862933f7))
- ImageData relates API and tests ([24c7990](https://github.com/Brooooooklyn/canvas/commit/24c7990f9c83a1fa81aa9b23d7712980ac556467))
- implement image pattern ([2efbb18](https://github.com/Brooooooklyn/canvas/commit/2efbb18b6f80eadd5f457048c149cc50076fe2a2))
- scale and rotate ([f6c761f](https://github.com/Brooooooklyn/canvas/commit/f6c761f4ebbb57c23dbec1f9be5c80ab7be38b95))
- skia m89 ([e9c1cc9](https://github.com/Brooooooklyn/canvas/commit/e9c1cc94d33204e68ebe72ae94e934bf686d3e28))
- support all drawImage variants ([8d5ded6](https://github.com/Brooooooklyn/canvas/commit/8d5ded624f5e915907ece2696f0f5e350e244b4c))
- support context alpha ([929bdc0](https://github.com/Brooooooklyn/canvas/commit/929bdc092374ee8d196cc7fa5c56a057acfa2cfa))
- support creating SkImage ([3945321](https://github.com/Brooooooklyn/canvas/commit/39453214b2793d40f16c6229e6444d713c0904cc))
- support getContextAttributes ([4c0586b](https://github.com/Brooooooklyn/canvas/commit/4c0586b39cd923217c7db5bdd5bc620d3c438131))
- support isPointInPath ([2150788](https://github.com/Brooooooklyn/canvas/commit/2150788b01103f25a272d8c89cf3cea2e2d5851b))
- support isPointInStroke ([2a14513](https://github.com/Brooooooklyn/canvas/commit/2a14513c4a06ab9d6eeefcc31827b3a6e06d80a1))
- support naturalWidth/naturalHeight/complete/alt ([1bb1042](https://github.com/Brooooooklyn/canvas/commit/1bb104206450d440991cdd6cc093ad31696be489))
- sync skia m89 ([9748c44](https://github.com/Brooooooklyn/canvas/commit/9748c44658f4507dcb86e463a1e68117d05f057b))
- text states and font styles ([a175cf7](https://github.com/Brooooooklyn/canvas/commit/a175cf729f4340ec49cec464e8e10c3561c20ebb))

### Performance Improvements

- disable image data copy ([ccc8630](https://github.com/Brooooooklyn/canvas/commit/ccc8630906afaf573e7f46877efbb6ed652212f8))

## [0.0.1-alpha.3](https://github.com/Brooooooklyn/canvas/compare/v0.0.1-alpha.2...v0.0.1-alpha.3) (2021-01-06)

### Features

- properties in CanvasRenderContext2D ([12727a7](https://github.com/Brooooooklyn/canvas/commit/12727a795e75c6873a900dba0755e7e9471f85ef))
- testing for context2d functions ([107a650](https://github.com/Brooooooklyn/canvas/commit/107a650213ba3f13038955c2b8a7875b9b571449))

## [0.0.1-alpha.2](https://github.com/Brooooooklyn/canvas/compare/v0.0.1-alpha.1...v0.0.1-alpha.2) (2020-12-26)

### Features

- implement Path2D ([91124d6](https://github.com/Brooooooklyn/canvas/commit/91124d6ba143c2c0728f8725c24443b58ef3fa06))
- support gradient in fill/stroke style ([12e061c](https://github.com/Brooooooklyn/canvas/commit/12e061cdbd2ab4849a846cef2d5077bd00793613))

## [0.0.1-alpha.1](https://github.com/Brooooooklyn/canvas/compare/v0.0.1-alpha.0...v0.0.1-alpha.1) (2020-12-24)

### Features

- async/sync get png data from Canvas ([f6d8cd6](https://github.com/Brooooooklyn/canvas/commit/f6d8cd60a6d336822a885bb0302a1ae2b8eafa9b))

## [0.0.1-alpha.0](https://github.com/Brooooooklyn/canvas/compare/5b09b4b92712bbce9468f0b874aed3ec7b87a716...v0.0.1-alpha.0) (2020-12-17)

### Features

- simple example ([5b09b4b](https://github.com/Brooooooklyn/canvas/commit/5b09b4b92712bbce9468f0b874aed3ec7b87a716))
- strokeStyle ([e185ca3](https://github.com/Brooooooklyn/canvas/commit/e185ca3faa1a13a22af37a20284a00114b9669ae))
- upgrade everything ([5d27f63](https://github.com/Brooooooklyn/canvas/commit/5d27f6355ffe0ef8abcda5a7e14871cccfcdd71b))