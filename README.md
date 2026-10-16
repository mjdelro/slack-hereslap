# Slack Hereslap

A small, unfinished Slack bot that warns someone after they use `@here`. The warning is ephemeral and includes the number of members in the channel.

## Status

This project uses the legacy `slackclient` 1.x RTM API and is not ready to run as committed. `bot.py` still contains an unresolved `BOTTOKEN` placeholder, while `config.ini` is read but not used to load a token.

Before using the idea in a workspace, migrate it to a supported Slack SDK and store the bot token outside the source code. The Slack app will need permission to read channel membership and post ephemeral messages.

## Original dependencies

```text
configparser>=3.5.0
slackclient>=1.3.0
```
