# Changelog

## [1.1.3](https://github.com/taskmedia/size-label-action/compare/v1.1.2...v1.1.3) (2025-12-25)


### Miscellaneous Chores

* **deps:** bump actions/checkout from 4.1.1 to 6.0.1 ([#134](https://github.com/taskmedia/size-label-action/issues/134)) ([7cc8ac6](https://github.com/taskmedia/size-label-action/commit/7cc8ac6ac3bc4d786dc9c67b8f0032471bf641f2))
* **deps:** bump actions/stale from 8.0.0 to 10.1.1 ([#135](https://github.com/taskmedia/size-label-action/issues/135)) ([378ceed](https://github.com/taskmedia/size-label-action/commit/378ceeda681a1ec740617ffc3ae6abe5341e0cde))
* **deps:** bump stefanzweifel/git-auto-commit-action ([#137](https://github.com/taskmedia/size-label-action/issues/137)) ([4f04d67](https://github.com/taskmedia/size-label-action/commit/4f04d67359c62b798e004ffb29cbf6437f1c27d4))

## [1.1.2](https://github.com/taskmedia/size-label-action/compare/v1.1.1...v1.1.2) (2023-11-20)


### Bug Fixes

* resolve fetch is not set error (node20) ([#11](https://github.com/taskmedia/size-label-action/issues/11)) ([ef1d6fc](https://github.com/taskmedia/size-label-action/commit/ef1d6fca8745f18708d5eeb07a3c7d4f5ecb2fc6))

## [1.1.1](https://github.com/taskmedia/size-label-action/compare/v1.1.0...v1.1.1) (2023-11-20)


### Miscellaneous Chores

* **ci:** add (pr) lint and test wf ([95c84cb](https://github.com/taskmedia/size-label-action/commit/95c84cb102351cfd924701b8135e92a44d3c5757))
* **ci:** remove actions/labeler ([#10](https://github.com/taskmedia/size-label-action/issues/10)) ([c2ffded](https://github.com/taskmedia/size-label-action/commit/c2ffded629845ade5c75bd16a44924712e94d140))
* **deps:** bump @octokit/rest from 19.0.11 to 20.0.2 ([#8](https://github.com/taskmedia/size-label-action/issues/8)) ([3804bff](https://github.com/taskmedia/size-label-action/commit/3804bff4ba68c3429b0794c507e59a086e68685f))
* **deps:** bump @vercel/ncc from 0.36.1 to 0.38.1 ([#9](https://github.com/taskmedia/size-label-action/issues/9)) ([ed0ebd4](https://github.com/taskmedia/size-label-action/commit/ed0ebd4b609e77412176dd99ab365577d20702bb))
* **deps:** bump dotenv from 16.1.2 to 16.3.1 ([#7](https://github.com/taskmedia/size-label-action/issues/7)) ([272ae1d](https://github.com/taskmedia/size-label-action/commit/272ae1d5146a51070434b2de352d28fadbf12e6d))
* **deps:** bump eslint from 8.41.0 to 8.54.0 ([#6](https://github.com/taskmedia/size-label-action/issues/6)) ([d5e78d5](https://github.com/taskmedia/size-label-action/commit/d5e78d5f7f37290171fcca3938cdcbb04e17f8fc))

## [1.1.0](https://github.com/taskmedia/size-label-action/compare/v1.0.0...v1.1.0) (2023-11-17)


### Features

* add yarn steps to release binary ([0e24a4c](https://github.com/taskmedia/size-label-action/commit/0e24a4c71de1a116bc7bffff3ccc6292b8d37dd8))


### Bug Fixes

* **ci:** checkout rp branch when commiting ([16800ca](https://github.com/taskmedia/size-label-action/commit/16800cac4e773e8f650d24c8c566016053290d3b))
* **ci:** get yarn dependencies on release wf ([9c958fc](https://github.com/taskmedia/size-label-action/commit/9c958fca8569ea2a44f295e1a8ba14143dcfe6b0))
* **ci:** skip node installation ([5f6ed1c](https://github.com/taskmedia/size-label-action/commit/5f6ed1c1e8f8d9314a41a2b5d6d6c7178e2759fc))
* **ci:** trigger build if rpa has pr action ([fce8235](https://github.com/taskmedia/size-label-action/commit/fce8235869dc594566f4a5e6f94f2bca9699b406))
* **ci:** use yarn for prepublish ([ca0d60a](https://github.com/taskmedia/size-label-action/commit/ca0d60a9d39353998dd8d51274e51fb1daf3cc4c))


### Miscellaneous Chores

* **build:** build dist for release ([f0b4421](https://github.com/taskmedia/size-label-action/commit/f0b442190a861a02812f5c64e1e91347ea4af4ca))

## 1.0.0 (2023-11-17)


### Features

* accept size config as input ✨ ([#25](https://github.com/taskmedia/size-label-action/issues/25)) ([6e019d2](https://github.com/taskmedia/size-label-action/commit/6e019d28eac8a5a84ed7af732a769ee8b18de1db))
* add release workflow ([afe23db](https://github.com/taskmedia/size-label-action/commit/afe23dbfcc490c7ef79b04c019c13ff09c5e7610))
* do not fail on label remove error ([#19](https://github.com/taskmedia/size-label-action/issues/19)) ([d8a4728](https://github.com/taskmedia/size-label-action/commit/d8a472826920ffa63e6285dffcaa0df6eb38e48e))
* use GITHUB_API_URL as baseUrl for octokit ([#1](https://github.com/taskmedia/size-label-action/issues/1)) ([49702a5](https://github.com/taskmedia/size-label-action/commit/49702a5a2b9c2e3cc2ceee46af7038a10f48a0d8))


### Miscellaneous Chores

* allow dot files ([2d18d32](https://github.com/taskmedia/size-label-action/commit/2d18d32a1b24836dc12f91178013967963f0bd6d))
* upgraded dependencies ([#37](https://github.com/taskmedia/size-label-action/issues/37)) ([fefca17](https://github.com/taskmedia/size-label-action/commit/fefca174ed70e310691357a0e7acf5a538ba5357))
