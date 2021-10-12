---
layout: page
title: FAQ
include_in_header: true
---

# Frequently Asked Questions

---

### Bug analysis is not appearing in the app ?

- You need to have in your artefacts the `raw-xcodebuild-output.log` file for it to work

### Test reports are not appearing in the app ?

- For the moment, this is an iOS only feature
- You need to have in your artefacts the `xcode-test-results-<ProjectName>.html` file for it to work

### Why are there hooks that are not removed from your service in our projet ?

- Because token expired and you've stop using the app without deleting the user in the app. Since we don't store your token or info without your input we cannot fully delete the hook on bitrise.

### How to be sure I completely remove every thing from your service ?

- Bitrise website: go to Project -> Code -> Remove the web hook with URL `api.sambot.app`
- Sambot app: go to Settings screen -> Manage your token -> Remove registered Token 

### Push notification doesn’t seem to work ?

- Push notifications work when the integration is finished if builds have succeed or failed.

- Bitrise website: go to Project -> Code -> Remove the web hook with URL `api.sambot.app` (pas sur de l’utilité dans ce cas la)
- Sambot app: go to your Project screen and enable push by toggling on the bell

### Why are there (sometimes) only partial steps visible on step module in Build screen while build is running ?

- Until the integration is finished we do not have access to the whole file. Just what has been recently processed.

### Sync iCloud

- This work only for devices that share the same iCloud account and use a token that allow access to the same team.

### How to delete any bookmarked build or project ?

- Long press on it and use the contextual menu.

### Why sometimes the full log button is not visible ?

- Just after the end of a build it took time to Bitrise to process the full log file it can go from a few seconds to a few minutes.

---

### I didn't my question in this list

If you don't find you question in this list, please contact us [on Twitter](https://twitter.com/sambot_app) or [by email](mailto:sambot-public1021@jaynjay.app).