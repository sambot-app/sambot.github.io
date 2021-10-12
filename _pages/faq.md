# FAQ


#### Bug analysis is not appearing in the app ?

- you need to have in your artefacts the `raw-xcodebuild-output.log` file for it to work

#### Test reports are not appearing in the app ?

- for the moment we support only iOS
- you need to have in your artefacts the `xcode-test-results-<ProjectName>.html` file for it to work

#### Why there is hooks that are not remove from your service in our projet ?

It is because the token have expired and you did stop using the app without deleting the user in the app. Since we don't store your token or info without your input we cannot full delete the hook on bitrise.

#### How to be sure I completely remove every thing from your service ?

Go to Project -> Code -> Remove the web hook with URL `api.sambot.app`

#### Push notification don’t seems to work ?

Push notification only work when the integration is finished and only if they have succeed or failed.

- Go to Project -> Code -> Remove the web hook with URL `api.sambot.app` (pas sur de l’utilité dans ce cas la)
- Add a project to push by enabling the bell

#### Why are only some step visible in the step module while it’s running ?

Because until the integration is finished we do not have access to the whole file. Just what has been recently processed.

#### Sync iCloud

This work only for the devices that share the same iCloud account and use a token that allow access to the same team.

#### How to delete a saved build ?

Long press on it and use the contextual menu.

#### Why sometimes the full log button is not visible ?

Just after the end of a build it took Bitrise a sometime to process the full log file it can go from a few seconds to a few minutes.
