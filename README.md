Microsoft Teams Chat Bot
========================

This project implements a chat bot for Microsoft Teams using Python. The bot has basic functionality to post random messages in a specific Teams chat and an advanced feature to echo messages posted in the same chat.


### Base Assignment

The bot can post a random message when executed through the CLI or when called via an API. It is attached to a specific chat in Microsoft Teams.

### Advanced Assignment

The bot implements an "Echo" service. It listens to a specific chat in Microsoft Teams, captures messages posted in that chat, and echoes back a copy of the user's message to the same chat.


### Quick Start

- Prerequisites: Install Docker.
- Build `docker-compose build`
- Run:  `docker-compose up`


## Testing the bot using Bot Framework Emulator

[Bot Framework Emulator](https://github.com/microsoft/botframework-emulator) is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

- Install the Bot Framework Emulator version 4.3.0 or greater from [here](https://github.com/Microsoft/BotFramework-Emulator/releases)

### Connect to the bot using Bot Framework Emulator

- Launch Bot Framework Emulator
- Enter a Bot URL of `http://localhost:3978/api/messages`


