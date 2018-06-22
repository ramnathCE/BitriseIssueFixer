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
### ios test
```
fastlane ios test
```
Runs all the tests
### ios hockeyrelease
```
fastlane ios hockeyrelease
```
Submit a new Commercial Adhoc Build to Hockey App
### ios upload_hockey_app
```
fastlane ios upload_hockey_app
```
Upload Hockey App
### ios after_all_clean_commit
```
fastlane ios after_all_clean_commit
```
Clean the project and commit the changes
### ios tag_in
```
fastlane ios tag_in
```
Test

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
