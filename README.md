# Github Actions Discord Self Bot
Automate sending a static message to a specific channel every 15mins^ on discord using Github Actions

> [!CAUTION]
> This does break Discord's TOS, use at on own risk. Better to use an alt account.

^ It's kinda random

### Requirements
1. Get your account's Auth Token : [Guide](https://gist.github.com/oyepriyansh/1be45b722181ec634664410cde244708) 
2. Get the channel's ID : [Guide](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID)
3. Get the json escaped message to send every interval : [JsonEscaper](https://www.freeformatter.com/json-escape.html)

### Get Started
1. Fork this repo
2. Setup the [Actions secrets and variables](./../../settings/secrets/actions) : 
[Guide](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions#creating-secrets-for-a-repository)
  - ACCOUNT_TOKEN
  - CHANNEL_ID
  - MESSAGE

3. Trigger the [Workflow](./../../actions/workflows/test.yml), by editing a file or manually triggering it.

[How to edit a file](https://stackoverflow.com/questions/72175416/how-can-i-edit-the-read-me-file-on-github)
