fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios release_build
```
fastlane ios release_build
```
Release build with clean
### ios test
```
fastlane ios test
```
Build xamarin project for debug and start nuunit tests
### ios build_debug
```
fastlane ios build_debug
```
Build xamarin project for debug and start nuunit tests
### ios release_custom_cert
```
fastlane ios release_custom_cert
```
Build xamarin release for iPhone with setting custom certificates and provision derived from match

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
