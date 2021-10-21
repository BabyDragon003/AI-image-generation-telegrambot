# Telegram DALL·E bot
![GitHub](https://img.shields.io/github/license/javitoro/telegram-dalle-bot) [![GitHub issues](https://img.shields.io/github/issues/JaviToro/telegram-dalle-bot)](https://github.com/JaviToro/telegram-dalle-bot/issues) [![GitHub forks](https://img.shields.io/github/forks/JaviToro/telegram-dalle-bot)](https://github.com/JaviToro/telegram-dalle-bot/network)

## Introduction
This is a simple implementation of the OpenAI API, a Telegram bot which will generate an image using AI for the prompt you send to it using the command `/image [prompt]`. Like, for example, `/image bots getting to the Moon`.

## Set-up guide

### Getting keys
In order to use this bot yourself, you'll need to get two keys, one for the OpenAI API authorization and other one as a token for the Telegram bot. As for OpenAI, you can register and get your API key [here](https://beta.openai.com/docs/introduction/overview). For the Telegram side, you can create a bot and get its token using [@BotFather](https://t.me/botfather) inside the app.

### Setting up the environment

Once you've got both keys, create a .env file in the root of the project and then add the tokens there, the following way:
```

And that's all, you can now interact with your bot using Telegram.
