---
layout: page
title: FAQ
include_in_header: true
---

# Frequently Asked Questions
**Last updated** November 3, 2021

## Sambot app

### What is this app for ?
Sambot app is a tool helping you in your Bitrise continuous integration experience, to be more efficient and focused on what you love to do!


### What do I need to use it?
To use Sambot app you need a Bitrise account access and a valid generated token ([see this tutorial](/tokentuto/index.html) for more details)..

### On which platform can I use it?
Sambot app is (at the moment) available on iOS and iPadOS and should soon be running on macOS.

### How much does it cost?
Sambot app is free to use with lots of great features. But if you wish to use some extra features (like Push Notifications, iCloud Sync, Detailed Test Reports, Unlimited Favorite Projects, or Siri & Shortcuts) check out our Pro features Plan and unlock it with in-app purchases.

---

## Build Detailed Screen

### Failure Review module is not appearing?
You need to have `raw-xcodebuild-output.log` file in your artifacts list for this feature to work.

### Test Report module is not appearing?
You need to have `xcode-test-results-<ProjectName>.html` file in your artifacts list for this feature to work.
Please note that at the moment, this is an iOS-only-project feature.

### Why is sometimes the "See Bitrise full logs" button not visible?
Just after the end of a build, it takes time for Bitrise to process the full log file. According to its size, it can take from a few seconds to a few minutes.

### Why are steps in the Build Steps module sometimes incomplete while a build is running?
Until the integration process is finished, Sambot app does not have access to the whole log file but just what has been recently processed. But don't worry, as soon as the build is finished, the entire file will be parsed and you'll be able to see all steps in detail.

---

## Push notifications

### Push notifications don’t seem to work?
- Push Notifications are included in Pro Features Plan. You have to subscribe to this plan to be able to receive them.
- Push Notifications are sent when the build integration has finished with a succeeded or failed status.
- To enable Push Notifications for a specific project in Sambot app, go to its Project screen and enable them by toggling on the Bell button.

### How do I know that everything is correctly configured in Sambot app?
To check that everything is OK or enable and give permissions if needed, just go to Settings screen > Notifications and tap on "Send a Test Notification" button.

### What if I don't want to receive any Push Notifications when I'm not at work?
Sambot app allows you to set your working days range as well as your time slots. Just go to Settings screen > Notifications to configure them as you wish.

---

## iCloud Sync

### iCloud Synchronization is not working?
- iCloud Sync is included in Pro Features Plan. You have to subscribe to this plan to be able to use it.
- iCloud Sync only works for devices that share the same iCloud account and use a token that allow access to the same team.

### What is synchronized across my devices?
At the moment, the iCloud Sync feature allows you to synchronize your favorite Projects, your favorite Builds, and your Custom Environment Parameters across your iOS/iPadOS devices.

### I want to delete all Sambot objects that are hosted on my iCloud account
Go to Settings screen > Manage your Token then toggle on "Clear all iCloud datas" and tap on "Remove registered Token" button.

---

## Cleaning

### How to delete a favorite Build or Project?
You have two ways to do it:
- On Dashboard, by long pressing on Project/Build tile then using the contextual menu delete button.
- On Project Screen/Edited Build screen, by toggling on the Star button.

### Why are there hooks not removed from your service in our Bitrise project?
Since we don't store your token, we cannot fully delete the hook on Bitrise by ourselves. For example, if you've stopped using Sambot app for a while without removing your token in the Settings screen, your hooks won't be deleted automatically from your Bitrise project.

### How to completely remove everything from your service?
- Bitrise website: Go to Project > Code then remove webhooks with `api.sambot.app` URL
- Sambot app: Go to Settings screen > Manage your token > Remove registered Token

--- 

### I didn't my question in this list

If you don't find your question in this list, please contact us [on Twitter](https://twitter.com/sambot_app) or [by email](mailto:sambot-public1021@jaynjay.app).