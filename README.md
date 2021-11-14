# Zip Emojis Bot

Exports all emojis in a guild to a zip file.

> Use `!zip` to generate the zip file, only usable by those with `MANAGE_EMOJIS` permissions.

Written in [Node.js](https://nodejs.org) and uses [discord.js](https://discord.js.org).

## Setup

### Clone the repository:

```bash
$ git clone https://github.com/KevinZMa/cl-bot.git
$ cd cl-bot
```

### Requirements:

You must have [Node.js v16.6.0+](https://nodejs.org) installed.

### Dependencies

Install all the dependencies using the following command:

```bash
$ npm install
```

### `.env` file:

```dosini
DISCORD_TOKEN="your_token"
```

### Invite

```
https://discord.com/api/oauth2/authorize?client_id=CLIENT_ID&permissions=379030899712&scope=bot
```

> Replace `CLIENT_ID` with your bot's id.

### Start the Bot

```bash
$ npm start
```