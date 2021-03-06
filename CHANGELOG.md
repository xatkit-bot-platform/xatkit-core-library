# Changelog

All notable changes for the Core library will be documented in this file.

Note that there is no changelog available for the initial release of the platform (1.0.0), you can find the release notes [here](https://github.com/xatkit-bot-platform/xatkit-core-library/releases).

The changelog format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/v2.0.0.html)

## Unreleased

### Added

- Add *Greetings*, *HowAreYou*, and *WhoAreYou* intents. These intents are quite common in designed bot, so we made them easily accessible through the *CoreLibrary*.
- Add *GoodBye* intent.
- Add *Thanks* intent.

### Changed

- Improve training sentences for *Help* intent
- *Help* intent now creates the `help` context (this context can be used to start a conversation path from the *Help* intent)

### Fixed

- [#1](https://github.com/xatkit-bot-platform/xatkit-core-library/issues/1): *Add welcome intent*
- [#2](https://github.com/xatkit-bot-platform/xatkit-core-library/issues/2): *Add a goodbye intent*
- [#5](https://github.com/xatkit-bot-platform/xatkit-core-library/issues/5): *Add thanks intent*

## [1.0.1] - 2019-12-01

### Changed
- Generated `xmi` files are now ignored by default. These files are not needed since the Xbase integration (`.intrent` files are loaded and parsed on the fly).

## [1.0.0] - 2019-10-09 

See the release notes [here](https://github.com/xatkit-bot-platform/xatkit-core-library/releases).

