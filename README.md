# slack-notifier
Sends a Slack message when a PR is opened

https://api.slack.com/methods/chat.postMessage
https://api.slack.com/start/building/bolt-js

Needs a Slack Bot integration in your Slack channel and a bot acess token. It fetches incoming webhooks generated from a Pull Request made on a repo. Currently uses https://github.com/archive/github-actions-slack as the main config repo. 
