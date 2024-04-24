# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### 0.0.25 (2024-04-24)


### Features

* **#99:** add syntax highlighting for import statements ([42ed236](https://github.com/a-h/templ-vscode/commit/42ed2366d94609c0c65e54732886ab598a1a1efb)), closes [#99](https://github.com/a-h/templ-vscode/issues/99)
* add ~/go/bin to probed directories, fixes [#393](https://github.com/a-h/templ-vscode/issues/393) ([34543ff](https://github.com/a-h/templ-vscode/commit/34543ff8688cac6bcb9905a5645ee61fa9414e95))
* add icon ([23d8bea](https://github.com/a-h/templ-vscode/commit/23d8beab6141e51b4b020d5b54b74203fbbabc1e))
* add OpenVSX and VS Code Marketplace CI, fixes [#111](https://github.com/a-h/templ-vscode/issues/111) ([824166a](https://github.com/a-h/templ-vscode/commit/824166abfc2fb0108317f98b1ebd719a5f7f549f))
* add support for Go comments in templ files, fixes https://github.com/a-h/templ/issues/233 ([09e01f3](https://github.com/a-h/templ-vscode/commit/09e01f35c9a8d5c3fe47d64f9a927612405c373f))
* add support for the new HTTP configuration value ([89c4ce5](https://github.com/a-h/templ-vscode/commit/89c4ce5e8ba6ee298d00885c9356477293ac4718))
* add syntax highlighting for style/script tags ([#32](https://github.com/a-h/templ-vscode/issues/32)) ([ed896d6](https://github.com/a-h/templ-vscode/commit/ed896d60363584a30d41458bc6763bebe8dd31ca))
* add syntax highlighting support for HTML attribute conditional statements ([#33](https://github.com/a-h/templ-vscode/issues/33)) ([783b1c5](https://github.com/a-h/templ-vscode/commit/783b1c54b0f86156ce518619ed0a859a46e7cc3b))
* added templ 2.0 syntax support. ([c4391f8](https://github.com/a-h/templ-vscode/commit/c4391f80ca52c5a0acfd478e43bea0cad2c43d7c))
* configure braces to autoclose. ([7e6a7c4](https://github.com/a-h/templ-vscode/commit/7e6a7c40a9a27ed2b3bd56e9a233a1ef5ec98f0c))
* enable configuration of the LSP to enable logging. ([6b35e20](https://github.com/a-h/templ-vscode/commit/6b35e205ec74ba1d9c492d60080afd92a3b722a8))
* multi-line templ/script/css function params syntax highlighting ([#41](https://github.com/a-h/templ-vscode/issues/41)) ([ba185d4](https://github.com/a-h/templ-vscode/commit/ba185d4f792eb7f58e35085e830e3b0db84e38ad))
* probe paths to look for templ executable ([47fb4ef](https://github.com/a-h/templ-vscode/commit/47fb4efd355686a9de81cab0abab12fdf427e335))
* show "Starting LSP: templ" as a status bar message ([#43](https://github.com/a-h/templ-vscode/issues/43)) ([fd2ae87](https://github.com/a-h/templ-vscode/commit/fd2ae878edd820f2c6b63da7a8f6ad2bdb49a63a))


### Bug Fixes

* **#652:** remove usage of lookbehind regex with wildcard lengths  ([#47](https://github.com/a-h/templ-vscode/issues/47)) ([25eeddc](https://github.com/a-h/templ-vscode/commit/25eeddc8a31f3b454d1a6e24afdc6743733033d0)), closes [#652](https://github.com/a-h/templ-vscode/issues/652)
* add highlighting for else if ([614822d](https://github.com/a-h/templ-vscode/commit/614822dd9e5e0e333027872b1a4501d8ed2a527b))
* bump semver ([58ecfe1](https://github.com/a-h/templ-vscode/commit/58ecfe11ffc7669b94fb14af4b49e8391f701798))
* Closing style tags on the same line cause syntax highlight issues ([#40](https://github.com/a-h/templ-vscode/issues/40)) ([69ddaf0](https://github.com/a-h/templ-vscode/commit/69ddaf0003fa962740e2fbd911140061c2e558d9))
* ensure go expressions are highlighted as Go code, not strings ([98024f3](https://github.com/a-h/templ-vscode/commit/98024f3da686f91b50c9425257b7916b2ae656db))
* if/else-if multiline statement syntax regex matching ([#31](https://github.com/a-h/templ-vscode/issues/31)) ([75d7f4a](https://github.com/a-h/templ-vscode/commit/75d7f4a61e6efbb59e287857a8dd008f49524efe))
* multi-line import expression syntax highlighting ([#16](https://github.com/a-h/templ-vscode/issues/16)) ([64226db](https://github.com/a-h/templ-vscode/commit/64226db7c8d57227176fc8f7da450a59de7cdc76))
* non-function import expression syntax highlighting ([#39](https://github.com/a-h/templ-vscode/issues/39)) ([e33c522](https://github.com/a-h/templ-vscode/commit/e33c5229f43564db51ae51c5ce86d1589fefd53c))
* resolve single line import expression syntax highlighting [#508](https://github.com/a-h/templ-vscode/issues/508) ([#29](https://github.com/a-h/templ-vscode/issues/29)) ([b3ebe7f](https://github.com/a-h/templ-vscode/commit/b3ebe7f113a0d2eaa17ba119904f8a1d81f577a5))
* struct method syntax highlighting ([b961f34](https://github.com/a-h/templ-vscode/commit/b961f34cee9d4cd18dad697a78e5676a096e358c))
* Syntax issue when closing a script on the same line ([#35](https://github.com/a-h/templ-vscode/issues/35)) ([36b2da7](https://github.com/a-h/templ-vscode/commit/36b2da785e6c8643f8df8af6dc84cc72a99e1bce))
* update vscode version ([6f609f5](https://github.com/a-h/templ-vscode/commit/6f609f545746367d2b5ac7d8c7909e4bf04eec64))

### [0.0.24](https://github.com/a-h/templ-vscode/compare/v0.0.23...v0.0.24) (2024-04-15)

### [0.0.23](https://github.com/a-h/templ-vscode/compare/v0.0.22...v0.0.23) (2024-04-15)


### Features

* multi-line templ/script/css function params syntax highlighting ([#41](https://github.com/a-h/templ-vscode/issues/41)) ([ba185d4](https://github.com/a-h/templ-vscode/commit/ba185d4f792eb7f58e35085e830e3b0db84e38ad))
* show "Starting LSP: templ" as a status bar message ([#43](https://github.com/a-h/templ-vscode/issues/43)) ([fd2ae87](https://github.com/a-h/templ-vscode/commit/fd2ae878edd820f2c6b63da7a8f6ad2bdb49a63a))


### Bug Fixes

* **#652:** remove usage of lookbehind regex with wildcard lengths  ([#47](https://github.com/a-h/templ-vscode/issues/47)) ([25eeddc](https://github.com/a-h/templ-vscode/commit/25eeddc8a31f3b454d1a6e24afdc6743733033d0)), closes [#652](https://github.com/a-h/templ-vscode/issues/652)

### [0.0.22](https://github.com/a-h/templ-vscode/compare/v0.0.20...v0.0.22) (2024-03-01)


### Bug Fixes

* Closing style tags on the same line cause syntax highlight issues ([#40](https://github.com/a-h/templ-vscode/issues/40)) ([69ddaf0](https://github.com/a-h/templ-vscode/commit/69ddaf0003fa962740e2fbd911140061c2e558d9))
* non-function import expression syntax highlighting ([#39](https://github.com/a-h/templ-vscode/issues/39)) ([e33c522](https://github.com/a-h/templ-vscode/commit/e33c5229f43564db51ae51c5ce86d1589fefd53c))
* struct method syntax highlighting ([b961f34](https://github.com/a-h/templ-vscode/commit/b961f34cee9d4cd18dad697a78e5676a096e358c))
* Syntax issue when closing a script on the same line ([#35](https://github.com/a-h/templ-vscode/issues/35)) ([36b2da7](https://github.com/a-h/templ-vscode/commit/36b2da785e6c8643f8df8af6dc84cc72a99e1bce))

### [0.0.21](https://github.com/a-h/templ-vscode/compare/v0.0.20...v0.0.21) (2024-02-27)

### Features

* Add restart command

### [0.0.20](https://github.com/templ-go/templ-vscode/compare/v0.0.19...v0.0.20) (2024-02-18)

* Resolve single line import expression syntax highlighting, fixes [#508](https://github.com/a-h/templ/issues/508) in #29
* Refactor import-expression syntax regex matching, fixes [#524](https://github.com/a-h/templ/issues/524) in #30
* Refactor if/else-if statement syntax regex matching, fixes [#524](https://github.com/a-h/templ/issues/524) in #31
* Add syntax highlighting for style/script tags, fixes [#489](https://github.com/a-h/templ/issues/489) in #32
* Add syntax highlighting support for HTML attribute conditional statements, fixes [#533](https://github.com/a-h/templ/issues/533) in #33

### [0.0.19](https://github.com/a-h/templ-vscode/compare/v0.0.18...v0.0.19) (2024-01-19)

### Features

* Resolve issue with broken syntax highlighting on switch statements, fixes [#437](https://github.com/a-h/templ/issues/437) ([b6f0c68](https://github.com/a-h/templ-vscode/commit/b6f0c68b487bf96648661d6d1ada81b76c09f492))

### [0.0.18](https://github.com/a-h/templ-vscode/compare/v0.0.17...v0.0.18) (2024-01-04)


### Features

* add ~/go/bin to probed directories, fixes [#393](https://github.com/a-h/templ-vscode/issues/393) ([34543ff](https://github.com/a-h/templ-vscode/commit/34543ff8688cac6bcb9905a5645ee61fa9414e95))

### [0.0.14](https://github.com/a-h/templ-vscode/compare/v0.0.13...v0.0.14) (2023-09-09)


### Features

* add OpenVSX and VS Code Marketplace CI, fixes [#111](https://github.com/a-h/templ-vscode/issues/111) ([824166a](https://github.com/a-h/templ-vscode/commit/824166abfc2fb0108317f98b1ebd719a5f7f549f))

### [0.0.13](https://github.com/a-h/templ-vscode/compare/v0.0.12...v0.0.13) (2023-09-09)


### Bug Fixes

* ensure go expressions are highlighted as Go code, not strings ([98024f3](https://github.com/a-h/templ-vscode/commit/98024f3da686f91b50c9425257b7916b2ae656db))

### [0.0.12](https://github.com/a-h/templ-vscode/compare/v0.0.11...v0.0.12) (2023-08-20)

### [0.0.11](https://github.com/a-h/templ-vscode/compare/v0.0.10...v0.0.11) (2023-08-20)


### Bug Fixes

* bump semver ([58ecfe1](https://github.com/a-h/templ-vscode/commit/58ecfe11ffc7669b94fb14af4b49e8391f701798))

### [0.0.10](https://github.com/a-h/templ-vscode/compare/v0.0.9...v0.0.10) (2023-08-20)


### Bug Fixes

* add highlighting for else if ([614822d](https://github.com/a-h/templ-vscode/commit/614822dd9e5e0e333027872b1a4501d8ed2a527b))

# Change Log

All notable changes to the "templ" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

- Initial release
