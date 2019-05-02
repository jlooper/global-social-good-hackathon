# Translator bot

## Overview

Chat bots offer a new user experience which focuses on text and natural language. As such, a bot is a perfect tool for creating a translation service, where a user can specify a target language and a message, and receive the translated text.

## Success criteria

Your team will create a chat bot which supports the following workflow:

- The bot asks the user what language they want to translate the text into
- The user answers
- The bot asks for the text
- The user enters the text
- The bot detects the current language and translates the message into the target language
- The bot sends a message back to the user indicating the original language, and then the translated text

The flow is [demonstrated on Botsociety](https://app.botsociety.io/s/5cc9dd7fe278e912aa256514?p=9a73e74183553a68c6c2d85de4aaef5fff71772c&desktop=false).

The bot can be accessible either via [Bot Framework Emulator](https://github.com/Microsoft/BotFramework-Emulator/blob/master/README.md) or [another channel](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0) such as Slack or Facebook Messenger.

### Possible additional challenges

- Enable speech support

## Resources

### Bot Framework

- [Create and deploy a bot](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-tutorial-basic-deploy?view=azure-bot-service-4.0&tabs=csharp)
- [Connect a bot to channels](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0)
- [Bot Framework Emulator](https://github.com/Microsoft/BotFramework-Emulator/blob/master/README.md)
- [Send and receive text messages](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-send-messages?view=azure-bot-service-4.0&tabs=csharp)
- [Save user and conversation data](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-v4-state?view=azure-bot-service-4.0&tabs=javascript)

### Translator Speech API

- [What is Translator Speech API](https://docs.microsoft.com/en-us/azure/cognitive-services/translator-speech/overview)
- [Quickstart: Translator Speech API with Node.js](https://docs.microsoft.com/en-us/azure/cognitive-services/translator-speech/quickstarts/nodejs)
