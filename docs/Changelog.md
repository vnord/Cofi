# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Next step will now be displayed near the timer (you can turn that off in settings)
- added missing German translations
- Added "Support Cofi" Dialog when user finishes their second recipe and in the settings
- Added button to download WearOS app in settings
- Added box with info that app has been updated with a link to this changelog
### Changed
- Tweaked Bottom Sheets across the app to be more Material You-like
### Removed


## [1.14.0|1.5.0] - 2023-02-03

### Added
- two new icons: a cup, and a cezve - sponsored by @YurishoSan

### Changed
- Step value can now be expressed with a decimal point
- fixed issues with how multiplier worked
- updated dependencies

### Removed


## [1.13.2|1.4.2] - 2023-01-05

### Added
- Norwegian (Bokmål) translation - thanks @deltainium

### Changed
- fixed crash on WearOS 2 devices
- changed style of timer on Android app
- added animations to step change in both WearOS and Android app
- fixed highlight when clicking on an edge of the Start FAB
### Removed


## [1.13.1|1.4.1] - 2022-12-27

### Added
- Italian translation - thanks @cmendoza2000
- New recipe icons to choose - sponsored by @ThatOneCalculator

### Changed

### Removed


## [1.13.0|1.4.0] - 2022-12-16

### Added
- Added settings page to the WearOS app
- Added multipliers to the WearOS app
- Added Position indicator, Vignette, and Rotary control to the WearOS app

### Changed
- Change milliseconds display

### Removed


## [1.11.2] - 2022-12-06

### Added
- Added Always on Display when timer is running
- If wearOS device doesn't support AoD then keep screen on during timer

### Changed
- fixed keyboard issue when adding steps after certain number
- changed Icon Bottom Sheet during recipe edit slightly

### Removed


## [1.11.1] - 2022-11-29

### Added
- Added a wearOS app
- separated Play Store and Open Source builds

### Changed
- fixed performance issues with timer when there are a lot of short steps
- fixed potential crash when editing the recipe
- fixed weight calculation when using multipliers

### Removed


## [1.11.0] - 2022-11-27 [Pre-release]

### Added
- Added a wearOS app
- separated Play Store and Open Source builds
- fixed performance issues with timer when there are a lot of short steps

### Changed

### Removed


## [1.9.1] - 2022-11-02

### Added

### Changed
- fixed already done weight calculation when using multiplier

### Removed


## [1.9.0] - 2022-11-01

### Added
- Added ability to multiply all values of the recipe without editing the recipe itself

### Changed
- Improved performance of app bar collapse
- updated dependencies

### Removed


## [1.8.0] - 2022-10-07

### Added
- Show recipe basic info in timer and on main recipe list screen
- WYSIWYG in description input
- Added "Cancel" button to Dialogs that were missing it

### Changed
- Back button now closes icon picker bottom sheet in recipe edit
- Tweaked scrolling into view of inputs in recipe edit page
- Description input is hidden by default to indicate that it isn't required
- Tweaked layout of Timer, StepAddCard, Description, Recipe Edit, Settings
- Fixed adding default recipes

### Removed


## [1.7.8] - 2022-08-19

### Added
- Added support for predictive back gesture animation on Android 13+

### Changed
- Updated dependencies
- fixed horizontal overscoll effect being applied when there is no horizontal scroll
- Add recipe FAB will collapse down to "small" state on scroll

### Removed



## [1.7.5] - 2022-07-22

### Added
- Added setting to enable/disable vibration on step change

### Changed
- Cleaned up Settings pages
- PiP animation should be smoother on Android 12+
- Added some animations when icon changes state (play/pause, current/done)

### Removed


## [1.7.4] - 2022-06-24

### Added

### Changed
- Fixed issues with Timer duration if user changed Animator Duration Scale

### Removed


## [1.7.3] - 2022-06-17

### Added
hotfix for crash

### Changed

### Removed


## [1.7.2] - 2022-06-17

### Added
- Added app shortcuts to last recipes

### Changed
- Fixed deeplinks only working when app is dead
- Fixed layout on foldable phones (like Z Fold)
- Target Android T, with language selection in app settings

### Removed


## [1.7.1] - 2022-05-27

### Added
- Ability to change current step by tapping on the name of the step

### Changed
- New animations of the text during step change
- Fixed issue with empty description showing up
- Fixed issue with steps with no time not changing FAB to the "play" icon

### Removed


## [1.7.0] - 2022-05-21

### Added
- New default recipe - AeroPress
- Ability to add default recipes again - in case you've edit them or want to get new default one without wiping app data
- Added layouts for landscape displays. App is now usable on Tablets
- Added ability to backup data to JSON and restore recipes from it

### Changed
- Updated more components to Material You
- New animation when changing between screens
- Minor performance improvements
- Fixed issues with layout in Timer if names are too long
- Fixed visibility issues in Timer in Dark Mode
- Timer is now prettier, and less square
- App bar now collapses when starting timer

### Removed


## [1.6.0] - 2022-05-08

### Added
- Missing german translations
- German store translation
- Ability to create blocking steps that require user input to progress

### Changed
- Fixed keyboard not hiding on step being added (and crash when it happens)
- Updated underlying dependencies,

### Removed


## [1.5.0] - 2022-02-11

### Added
- Ability to change step order
- Alert dialog when exiting edit/add screen with unsaved changes
- App version in settings
- Ability to clone recipes

### Changed
- Fix text selection colors
- Fix about page list item icon alignment
- Fix wait step ime keyboard action
- Fix saving step without a name
- Removed a few kb from app size
- Retroactively changed previous release to 1.4.0
- Scroll to progress indicator on recipe start

### Removed


## [1.4.0 (1.8.0 via error)] - 2022-01-30

### Added
- Proper changelog
- Added rudimentary validation in Recipe Edit page

### Changed
- Replaced webview implementation of Open Source Licenses with one written in Compose
- Fixed issue where app would misbehave and/or crash if user revoke PiP permission
- Changed design on step add card
- Fixed PiP setting toggle not working

### Removed

## [1.3.4] - 2022-01-18

### Added
- German language [@lneugebauer](https://github.com/lneugebauer)
- Ability to cancel out of step edit [@lneugebauer](https://github.com/lneugebauer)

### Changed
- Added missing Polish strings
- Fixed crash on going back to full screen

### Removed
