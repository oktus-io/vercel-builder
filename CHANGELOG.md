### [0.22.8](https://github.com/oktus-io/vercel-builder/compare/v0.22.7...v0.22.8) (2022-05-13)


### Bug Fixes

* added pnpm flags ([670cf7e](https://github.com/oktus-io/vercel-builder/commit/670cf7e5bf20e4b12274249bcf9d15c6e471d1e2))

### [0.22.7](https://github.com/oktus-io/vercel-builder/compare/v0.22.6...v0.22.7) (2022-05-13)


### Bug Fixes

* removed flags/args ([5b7eebd](https://github.com/oktus-io/vercel-builder/commit/5b7eebd61c4e8b9a45949e4af54e752477edf2ce))

### [0.22.6](https://github.com/oktus-io/vercel-builder/compare/v0.22.5...v0.22.6) (2022-05-13)


### Bug Fixes

* (pnpm) removed incompatible flags ([1c95191](https://github.com/oktus-io/vercel-builder/commit/1c95191b5cbc52f5dae7c33e5833ae13d10560c6))

### [0.22.5](https://github.com/oktus-io/vercel-builder/compare/v0.22.4...v0.22.5) (2022-05-13)


### Bug Fixes

* removed logs ([b1fc06f](https://github.com/oktus-io/vercel-builder/commit/b1fc06faa21ed0a2698aaffa96fa82c1eda90786))

### [0.22.4](https://github.com/oktus-io/vercel-builder/compare/v0.22.3...v0.22.4) (2022-05-13)


### Bug Fixes

* logging runtime options ([258b4d9](https://github.com/oktus-io/vercel-builder/commit/258b4d97053df7483b2b9796f36b0655c33fad9c))

### [0.22.3](https://github.com/oktus-io/vercel-builder/compare/v0.22.1...v0.22.3) (2022-05-13)


### Bug Fixes

* removed codecov from main workflow ([0f0e644](https://github.com/oktus-io/vercel-builder/commit/0f0e64422918bd63a1077a27daff07d934e50546))

### [0.22.1](https://github.com/nuxt/vercel-builder/compare/v0.22.0...v0.22.1) (2021-09-28)


### Bug Fixes

* revert `@vercel/build-utils` upgrade (hotfix) ([c34432f](https://github.com/nuxt/vercel-builder/commit/c34432fc948564790196583fa3ef2c55adbc4e20)), closes [nuxt/vercel-builder#633](https://github.com/nuxt/vercel-builder/issues/633)

## [0.22.0](https://github.com/nuxt/vercel-builder/compare/v0.21.3...v0.22.0) (2021-09-25)


### ⚠ BREAKING CHANGES

* upgrade `@vercel/node-bridge`

### Features

* allow disabling cache with `NUXT_CACHE_DISABLED` flag ([#628](https://github.com/nuxt/vercel-builder/issues/628)) ([e993410](https://github.com/nuxt/vercel-builder/commit/e993410575f39d55c6abda7861804018f82532fd))


### Miscellaneous Chores

* upgrade `@vercel/node-bridge` ([73af3f9](https://github.com/nuxt/vercel-builder/commit/73af3f941eee2eb782eec468c1538e6b46e819b5))

### [0.21.3](https://github.com/nuxt/vercel-builder/compare/v0.21.2...v0.21.3) (2021-06-10)


### Bug Fixes

* only use custom `publicPath` if it is not absolute ([d8df9af](https://github.com/nuxt/vercel-builder/commit/d8df9aff618c322617523c6b07ba65b45e69be59)), closes [#578](https://github.com/nuxt/vercel-builder/issues/578)

### [0.21.2](https://github.com/nuxt/vercel-builder/compare/v0.21.1...v0.21.2) (2021-03-02)

### [0.21.1](https://github.com/nuxt/vercel-builder/compare/v0.21.0...v0.21.1) (2021-03-02)


### Bug Fixes

* improve error messages when failing to load nuxt config ([4874361](https://github.com/nuxt/vercel-builder/commit/48743613505eba308a98b3ade7ba0880599a3b2c))

## [0.21.0](https://github.com/nuxt/vercel-builder/compare/v0.20.3...v0.21.0) (2021-02-25)


### Features

* zero-config integration with vercel analytics ([#518](https://github.com/nuxt/vercel-builder/issues/518)) ([5001a4a](https://github.com/nuxt/vercel-builder/commit/5001a4ac8a30162c8a4a2855750e27bd8318073f))

### [0.20.3](https://github.com/nuxt/vercel-builder/compare/v0.20.2...v0.20.3) (2021-02-15)


### Bug Fixes

* remove needless default ([455ff1a](https://github.com/nuxt/vercel-builder/commit/455ff1a7aa3185cfb5db1de6930e38fa6faa7a47))

### [0.20.2](https://github.com/nuxt/vercel-builder/compare/v0.20.1...v0.20.2) (2021-02-15)


### Bug Fixes

* de-default the jiti import ([bce0a26](https://github.com/nuxt/vercel-builder/commit/bce0a26f253aca14362ae1825f517c439c019baa))

### [0.20.1](https://github.com/nuxt/vercel-builder/compare/v0.20.0...v0.20.1) (2021-02-15)


### Bug Fixes

* add workaround for esm for Nuxt < 2.15 ([a7a2e49](https://github.com/nuxt/vercel-builder/commit/a7a2e49a20d70766b7eace060b305baeb6fecc14))

## [0.20.0](https://github.com/nuxt/vercel-builder/compare/v0.19.0...v0.20.0) (2021-02-15)


### ⚠ BREAKING CHANGES

* upgrade to nuxt 2.15

### Miscellaneous Chores

* upgrade to nuxt 2.15 ([1588c3b](https://github.com/nuxt/vercel-builder/commit/1588c3b5b1a4383176b47d2a60cdc73cada1554a))

## [0.19.0](https://github.com/nuxt/vercel-builder/compare/v0.18.1...v0.19.0) (2021-01-30)


### Features

* add support for `NPM_RC` and `NPM_TOKEN` ([a223f15](https://github.com/nuxt/vercel-builder/commit/a223f15ccfb4ed39f3292d946b2c0a81289f2ecc)), closes [#488](https://github.com/nuxt/vercel-builder/issues/488)

### [0.18.1](https://github.com/nuxt/vercel-builder/compare/v0.18.0...v0.18.1) (2020-11-30)


### Bug Fixes

* collect all static generated files ([fe4e507](https://github.com/nuxt/vercel-builder/commit/fe4e50701bd9d8ad855c5fcdcf87ff4fb210a243)), closes [#391](https://github.com/nuxt/vercel-builder/issues/391)

## [0.18.0](https://github.com/nuxt/vercel-builder/compare/v0.17.12...v0.18.0) (2020-11-09)


### Features

* add internal server for serverMiddleware ([#375](https://github.com/nuxt/vercel-builder/issues/375)) ([4935cab](https://github.com/nuxt/vercel-builder/commit/4935cab146a04366beb31fc14c35f78cb779d202))

### [0.17.12](https://github.com/nuxt/vercel-builder/compare/v0.17.11...v0.17.12) (2020-09-28)


### Bug Fixes

* improve cache handling ([bec1d02](https://github.com/nuxt/vercel-builder/commit/bec1d02cd8d41ce91f0fccca944f0c77cdafe948))
* print debugging info and don't use `repoRootPath` for `node_modules` ([2626f7f](https://github.com/nuxt/vercel-builder/commit/2626f7f068dde19f146b82270ad3a8a153164f18))

### [0.17.11](https://github.com/nuxt/vercel-builder/compare/v0.17.10...v0.17.11) (2020-09-27)

### [0.17.10](https://github.com/nuxt/vercel-builder/compare/v0.17.9...v0.17.10) (2020-09-27)


### Bug Fixes

* preserve contents of `node_modules` folder if it exists ([b9318b8](https://github.com/nuxt/vercel-builder/commit/b9318b8f98f4e807b90babdbeb2db1759d843258))

### [0.17.9](https://github.com/nuxt/vercel-builder/compare/v0.17.8...v0.17.9) (2020-09-27)


### Bug Fixes

* recursively delete `node_modules` if it exists ([461e2ff](https://github.com/nuxt/vercel-builder/commit/461e2ffb5c3e16c6ca1d76f2d422f702d5db2b05))

### [0.17.8](https://github.com/nuxt/vercel-builder/compare/v0.17.7...v0.17.8) (2020-09-27)


### Bug Fixes

* hotfix to address unlinking `node_modules` issue ([9334118](https://github.com/nuxt/vercel-builder/commit/9334118fa58ed20abd6b38a9c56e530ef3f1a353)), closes [#369](https://github.com/nuxt/vercel-builder/issues/369)

### [0.17.7](https://github.com/nuxt/vercel-builder/compare/v0.17.6...v0.17.7) (2020-09-22)


### Bug Fixes

* revert vercel monorepo support ([#366](https://github.com/nuxt/vercel-builder/issues/366)) ([f7d4ff4](https://github.com/nuxt/vercel-builder/commit/f7d4ff4e27fd1e5f175e45792a631c81abf6f976))

### [0.17.6](https://github.com/nuxt/vercel-builder/compare/v0.17.5...v0.17.6) (2020-09-22)

### [0.17.5](https://github.com/nuxt/vercel-builder/compare/v0.17.4...v0.17.5) (2020-09-06)


### Bug Fixes

* add support for UTF-16 LE encoded `tsconfig.json` ([#354](https://github.com/nuxt/vercel-builder/issues/354)) ([ac40dd2](https://github.com/nuxt/vercel-builder/commit/ac40dd2fe9b151521f1f1d88eaa98499f913b95e)), closes [#245](https://github.com/nuxt/vercel-builder/issues/245)

### [0.17.4](https://github.com/nuxt/vercel-builder/compare/v0.17.3...v0.17.4) (2020-08-26)

### [0.17.3](https://github.com/nuxt/now-builder/compare/v0.17.2...v0.17.3) (2020-07-02)

### [0.17.2](https://github.com/nuxt/now-builder/compare/v0.17.1...v0.17.2) (2020-05-14)

### [0.17.1](https://github.com/nuxt/now-builder/compare/v0.17.0...v0.17.1) (2020-02-27)


### Features

* add option to include static generated pages ([#185](https://github.com/nuxt/now-builder/issues/185)) ([a488cb6](https://github.com/nuxt/now-builder/commit/a488cb68917c6b70d32e77f43b73a8d0199a8010))

## [0.17.0](https://github.com/nuxt/now-builder/compare/v0.16.6...v0.17.0) (2020-01-23)


### ⚠ BREAKING CHANGES

* @nuxt/now-builder no longer supports node v8

* docs: correct default version

* chore: upgrade now deps

Co-authored-by: Steven <steven@ceriously.com>

### Features

* add support for now-build script ([#168](https://github.com/nuxt/now-builder/issues/168)) ([5266188](https://github.com/nuxt/now-builder/commit/526618864ffe2e0dd8fc3ea6cab99b674fc4088b))
* support new config options ([#158](https://github.com/nuxt/now-builder/issues/158)) ([01a241a](https://github.com/nuxt/now-builder/commit/01a241a52f485d973b541d843777bca6331bb133))


### Bug Fixes

* pin old version of nuxt for compat with node 8 ([d4408fd](https://github.com/nuxt/now-builder/commit/d4408fdddcb1b41e4945ab706e93a1a6bcf1d68f))
* use srcDir to retrieve static folder ([#150](https://github.com/nuxt/now-builder/issues/150)) ([e23b4e5](https://github.com/nuxt/now-builder/commit/e23b4e5c5c1760179d217c6d22a871a7bf8b8e75))
* use srcDir when compiling build files ([#152](https://github.com/nuxt/now-builder/issues/152)) ([6e25975](https://github.com/nuxt/now-builder/commit/6e25975bd33de83db2f4a24c8964af63667c6273))

### [0.16.6](https://github.com/nuxt/now-builder/compare/v0.16.5...v0.16.6) (2019-10-23)


### Bug Fixes

* install devDependencies with npm ([c14deee](https://github.com/nuxt/now-builder/commit/c14deee)), closes [#143](https://github.com/nuxt/now-builder/issues/143)

### [0.16.5](https://github.com/nuxt/now-builder/compare/v0.16.4...v0.16.5) (2019-10-11)


### Bug Fixes

* prepare cache against workCache ([#136](https://github.com/nuxt/now-builder/issues/136)) ([8dfac11](https://github.com/nuxt/now-builder/commit/8dfac11)), closes [#133](https://github.com/nuxt/now-builder/issues/133)
* remove boilerplate routes from example ([#140](https://github.com/nuxt/now-builder/issues/140)) ([d0a50cb](https://github.com/nuxt/now-builder/commit/d0a50cb))
* revert to using cachePath ([#135](https://github.com/nuxt/now-builder/issues/135)) ([da7409e](https://github.com/nuxt/now-builder/commit/da7409e)), closes [#133](https://github.com/nuxt/now-builder/issues/133)
* test for presence of nuxt.config.ts before compile ([a218681](https://github.com/nuxt/now-builder/commit/a218681))

### [0.16.4](https://github.com/nuxt/now-builder/compare/v0.16.3...v0.16.4) (2019-09-11)


### Bug Fixes

* force production NODE_ENV ([7333afa](https://github.com/nuxt/now-builder/commit/7333afa))
* set NODE_ENV to production before building nuxt ([9bbaeac](https://github.com/nuxt/now-builder/commit/9bbaeac)), closes [#126](https://github.com/nuxt/now-builder/issues/126)
* set NODE_ENV to production before building nuxt ([#127](https://github.com/nuxt/now-builder/issues/127)) ([db76f1c](https://github.com/nuxt/now-builder/commit/db76f1c))

### [0.16.3](https://github.com/nuxt/now-builder/compare/v0.16.2...v0.16.3) (2019-09-10)


### Bug Fixes

* consume default export of nuxt config file ([#124](https://github.com/nuxt/now-builder/issues/124)) ([22dff63](https://github.com/nuxt/now-builder/commit/22dff63)), closes [#43](https://github.com/nuxt/now-builder/issues/43)

### [0.16.2](https://github.com/nuxt/now-builder/compare/v0.16.1...v0.16.2) (2019-09-10)


### Bug Fixes

* use new object property from Now ([#122](https://github.com/nuxt/now-builder/issues/122)) ([d01e992](https://github.com/nuxt/now-builder/commit/d01e992)), closes [#111](https://github.com/nuxt/now-builder/issues/111)

### [0.16.1](https://github.com/nuxt/now-builder/compare/v0.16.0...v0.16.1) (2019-08-30)


### Bug Fixes

* fix typescript dependency test ([#118](https://github.com/nuxt/now-builder/issues/118)) ([5d41eee](https://github.com/nuxt/now-builder/commit/5d41eee))



## [0.16.0](https://github.com/nuxt/now-builder/compare/v0.15.3...v0.16.0) (2019-08-30)


### Bug Fixes

* allow installing node 10 dependencies ([#109](https://github.com/nuxt/now-builder/issues/109)) ([20962de](https://github.com/nuxt/now-builder/commit/20962de))
* test for presence of dependencies before accessing ([#116](https://github.com/nuxt/now-builder/issues/116)) ([4fc181d](https://github.com/nuxt/now-builder/commit/4fc181d))


### Features

* add required options for typescript projects ([#110](https://github.com/nuxt/now-builder/issues/110)) ([100e6f4](https://github.com/nuxt/now-builder/commit/100e6f4))
* expose static files as routes ([#106](https://github.com/nuxt/now-builder/issues/106)) ([d66931d](https://github.com/nuxt/now-builder/commit/d66931d))



### [0.15.3](https://github.com/nuxt/now-builder/compare/v0.15.2...v0.15.3) (2019-08-22)


### Features

* add support for yarn workspaces ([#103](https://github.com/nuxt/now-builder/issues/103)) ([a4a7e94](https://github.com/nuxt/now-builder/commit/a4a7e94))

### [0.14.6](https://github.com/nuxt/now-builder/compare/v0.14.5...v0.14.6) (2019-06-29)


### Bug Fixes

* downgrade execa to 1.x ([55b01bb](https://github.com/nuxt/now-builder/commit/55b01bb))



### [0.14.5](https://github.com/nuxt/now-builder/compare/v0.14.4...v0.14.5) (2019-06-29)


### Bug Fixes

* pin @now/node-bridge dependency to 1.2.1 ([#67](https://github.com/nuxt/now-builder/issues/67)) ([72090c6](https://github.com/nuxt/now-builder/commit/72090c6))
* pin all non dev dependencies ([f386391](https://github.com/nuxt/now-builder/commit/f386391))
* use preferLocal: true for execa ([00318b4](https://github.com/nuxt/now-builder/commit/00318b4))



## [0.14.4](https://github.com/nuxt/now-builder/compare/v0.14.3...v0.14.4) (2019-05-27)



## [0.14.3](https://github.com/nuxt/now-builder/compare/v0.14.2...v0.14.3) (2019-04-30)



## [0.14.2](https://github.com/nuxt/now-builder/compare/v0.14.1...v0.14.2) (2019-04-30)


### Bug Fixes

* add package.json to serverFiles ([#21](https://github.com/nuxt/now-builder/issues/21)) ([3b4e3d9](https://github.com/nuxt/now-builder/commit/3b4e3d9))
* allow using nuxt 2.4.0 ([#29](https://github.com/nuxt/now-builder/issues/29)) ([2e096c2](https://github.com/nuxt/now-builder/commit/2e096c2))



## [0.14.1](https://github.com/nuxt/now-builder/compare/v0.14.0...v0.14.1) (2019-04-03)


### Bug Fixes

* read nuxt.config after yarn install. fixes [#26](https://github.com/nuxt/now-builder/issues/26) ([a5a1068](https://github.com/nuxt/now-builder/commit/a5a1068))



# [0.14.0](https://github.com/nuxt/now-builder/compare/v0.13.1...v0.14.0) (2019-04-02)


### Bug Fixes

* resolve buildDir relative to rootDir ([4d56202](https://github.com/nuxt/now-builder/commit/4d56202))


### Features

* wait for nuxt to be ready before render ([#21](https://github.com/nuxt/now-builder/issues/21), [#24](https://github.com/nuxt/now-builder/issues/24)) ([75151ca](https://github.com/nuxt/now-builder/commit/75151ca))



## [0.13.1](https://github.com/nuxt/now-builder/compare/v0.13.0...v0.13.1) (2019-03-23)


### Bug Fixes

* use --no-lock. fixes [#19](https://github.com/nuxt/now-builder/issues/19). ([52b8a89](https://github.com/nuxt/now-builder/commit/52b8a89))



# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

# [0.13.0](https://github.com/nuxt/now-builder/compare/v0.12.3...v0.13.0) (2019-02-24)


### Features

* working cache! ([b942a5d](https://github.com/nuxt/now-builder/commit/b942a5d))
