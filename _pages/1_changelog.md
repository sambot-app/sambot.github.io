---
layout: page
title: What's new
include_in_header: true
---

# Changelog
**Last updated** September 13, 2022

# **Version 2.0**

### What's New ?

### Features
- [Feat] Invite all your teammates (securely) to join your Sambot teams via a _Magic link_ without sharing any token to them
- [Feat] Manage users access permissions (guest, member or admin) from any of your teams (Developer / QA / Marketing / DevOps, and a lot more...)
- [Feat] Add new `Account screen` (accessible from `Settings` toolbar)
- [Feat] Improve `Settings screen`

### Fixes
- [Fix] Fix iOS 16 compatibility
- [Fix] Fix a few bugs around last-updated/favorite `Applications` on Dashboard
- [Fix] Fix crashes on iOS
- [Fix] Fix crashes on macOS

### Refacto
- [Refacto] Refactor all system of `Modal sheets` all over the app
- [Refacto] Summer haircut for Notifications

<br>

### **Version 1.10**
- [Feat] Add toggle on `Project Screen` to receive Push Notification as soon as builds finished
- [Feat] Add native `ColorPicker` to improve color edition experience for Projects, Updated Apps, and Builds tiles
- [Feat] Add button to share Bitrise Build URL on `Build Detailed screen`
- [Fix] Update `Updated Apps` / `Meteo` when data download is finished
- [Refacto] Improve `Analytics Insights` Charts performances
- [Refacto] Drastically reduce memory consumption
- [Design] Update `Project screen` appearance

<br>

### **Version 1.9**
- [Feat] Improve `Add Environment Parameters` screen
- [Feat] You can now add any fresh new branch when starting a build
- [Fix] Fix bug when duplicated Environment params appears
- [Fix] Fix a crash at launch
- [Refacto] Working on a next (great) feature

<br>

### **Version 1.8**
- [Feat] Add automatic app updates on Dashboard for all your favorites projects to always be aware of the last up-to-date built app
- [Feat] Improve `Environment Params` auto-completion when triggering a new build
- [Feat] You can now restart/retry a Build from its tile button and quickly edit any of its combination of workflow, branch, env params
- [Fix] Fix a crash on app launch
- [Fix] Fix duplicates while setting Environment params to a Build
- [Fix] Fix Analytics Insights live update with fresh builds and date range that were sometimes wrongly set at launch
- [Fix] Fix a crash on Test Report Summary in Build detailed screen

<br>

### **Version 1.7**
- [Feat] `Environment Parameters` now autocomplete when configuring a build to run from any combinaison of project / workflow / branch / tags
- [Feat] Add duration progress estimated from DB for favorites projects Builds running
- [Fix] A few graphical glitches fixed
- [Fix] `Analytics Insights` fetching was sometimes blocked
- [Refacto] Improved `Build Screen` loading (speed + code) 
- [Refacto] Improved `Analytics Insights` fetching datas reliability
- [Refacto] Improved quality of implementation for an incoming (great) feature 😉

<br>

### **Version 1.6**
- [Feat] Add macOS Support *(Apple silicon only)*
- [Feat] Improve iPad version (adding `Sidebar`, adaptative padding, charts markers...)
- [Feat] Improve Filters usage & style in `Analytics Insights` screen
- [Fix] Improve `Analytics Insights` Downloader stop/resume behaviour
- [Fix] Fix `Tests Results` parser
- [Fix] Fix bugs in `Analytics Insights` screen
- [Fix] Fix `Premium Pro plan` random disconnection 
- [Fix] Persistent store crash after reseting token
- [Fix] Fix websites URLs
- [Fix] Fix iCloud sync
- [Refacto] Replace a few deprecated APIs
- [Refacto] Reduce code warnings, remove useless files

<br>

### **Version 1.5**
- [Feat] New Onboarding for token generation
- [Fix] Analytics Insights charts UI bugs
- [Fix] Fix update token alert
- [Style] Improvements on buttons, colors and tiles
- [Refacto] Analytics Insights Downloader is now more reliable
- [CI] A few improvements

<br>

### **Version 1.4**
- [Feat] Add a `Demo Mode` to try and discover Sambot app without entering any token
- [Feat] Add an achievement progress bar on `Build Tile` when running (based on median duration for its workflow over past 3 months)
- [Feat] Add `Analytics Insights` entry on `Dashboard` and make it available for multiple Projects
- [Feat] Add  a "triggered by user" filter in `Analytics Insights` screen
- [Feat] Add the Successful builds median duration in `Analytics Insights`
- [Fix] Fix ScrollViews insets troubles on small devices
- [Fix] Fix crashes from nil Reducers
- [Style] Small graphical improvements mainly on `Dashboard` and `Project` screens
- [Refacto] Move all Colors into `StyleGuide` module for better app modularization

<br>

### **Version 1.3**
- [Feat] New `Analytics Insight` feature ! Discover tons of metrics computed from all the builds of your projects from the very first one: Cost, Duration, Success/Failure rates, Waiting time, Number of builds... These metrics are presented in beautiful colored charts, grids or highlights !
- [Fix] Update `Failure Review` BuildScreen module by adding smarter limits
- [Fix] `Favorites Artifacts` are now saved when leaving application
- [Fix] Improve `Bitrise Colorized Log` to be available even build still running
- [Fix] A few bugs and crashes
- [Style] Small graphical improvements mainly on `Dashboard` and `BuildScreen`

<br>

### **Version 1.2**
- [Feat] Add new `Favorite Artifacts Updates` feature. Mark any artifacts as favorite in Build Detailed screen and always get the last updated version of them on your Dashboard 
- [Feat] Add more information on Build Detailed screen (cost in credits, stack, timestamps...)
- [Feat] Add `Bitrise Public Page` button for the main artifact in Build Detailed screen 
- [Feat] Improve Pro Features screen for subscribed users (subscription management, redeem code...)
- [Fix] Elapsed time countdown on Build tile
- [Fix] Build Detailed screen automatic refresh troubles when it ends
- [Fix] At the end of a Build, `FailureReview` module automatically refreshes itself until log & artifacts are ready
- [Fix] A few other bugs
- [Fix] Artifact expiration AWS token
- [Refacto] A little bit of refacto (always good for health) + clean a few TODOs

<br>

### **Version 1.1**
- [Fix] Fixes after AppStore verification process feedbacks...
- [Fix] Backend fixes...
- [Fix] Push Notifications fixes...

<br>

### **Version 1.0**
- [Feat] First version of Sambot iOS / iPadOS application ! 