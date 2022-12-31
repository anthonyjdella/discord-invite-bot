# Creating Discord Bot

## Create a playground server
> Create a server to test your application
1. In the Discord app, create a new server with the + button

## Create a discord application
1. In the [developer dashboard](https://discord.com/developers/applications), create a new app

## Create a discord bot
1. On the left side bar, create a new bot
2. There is a token associated to the bot, to authorize the API requests and carry out permissions
> Don't share your token

## Set scopes and permission to the bot
> You need to set permissions to each discord bot
1. On the left side, click OAuth2 then URL generator (a link with the scopes and permissions for your bot)
2. Select `application.commands` to access /slash commands
3. Select `bot` to enable the bot, then give it permissions to `Send Messages` and `Use Slash Commands`
4. Copy the generated URL and paste it into a browser
5. Allow the bot to access your Discord account and add it to a server (the playground server)

> Discord does not maintain any official SDKs so you can use a community built one for your language
> Or you can use [discord-interactions](https://github.com/discord/discord-interactions-js) which provide helper functions

> Glitch is an online code editor and way to deploy apps. Remix in Glitch is like forking a project

