# Github Actions Discord Self Bot
Automate sending a static message to a specific channel every 15mins^ on discord using Github Actions

> [!CAUTION]
> This does break Discord's TOS, use at on own risk. Better to use an alt account.

^ It's kinda random

### Requirements
1. Get your account's Auth Token 
2. Get the channel's ID
3. Get the json escaped message to send every interval

## Get Started
1. Fork this repo
2. Setup the [Actions secrets and variables](./settings/secrets/actions)
  - ACCOUNT_TOKEN
  - CHANNEL_ID
  - MESSAGE
3. Trigger the [Workflow](./actions/workflows/test.yml), by editing a file or manually triggering it.
