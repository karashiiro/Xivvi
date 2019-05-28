# Xivvi
(WIP) A production version of Prima.

# Adding Xivvi to Your Discord Server
This is the easy way to use Xivvi, just click the link below to add Rimap to your server and then follow the other directions:

No link here yet.

Create a channel called `#bot-stuff` for Xivvi to post random data to, and make sure you have a role called "Moderator".

# Commands

`~addclock <voice channel ID> <Linux-formatted timezone` - Turns a voice channel into a clock.

`~deleteclock <voice channel ID>` - Smashes a clock.

# Installation
(WIP)

If you want to host a copy of Xivvi yourself, it's a little more involved. First, get a bot token from the [Discord Developer Portal](https://discordapp.com/developers/docs/intro) and install [Node.js](https://nodejs.org/en/). Also get yourself your four access keys from Twitter's REST API.

There's a fair number of commands to be run to install the node.js dependencies into your Rimap folder, listed below:

`npm init` - Hit enter until it asks for your project file (default: index.js) and then set that to rimap.js.

`npm i common-tags`

`npm i config`

`npm i cron`

`npm i discord.js`

`npm i gm` - You also need to install [Graphicsmagick.](http://www.graphicsmagick.org/)

`npm i moment`

`npm i moment-timezone`

`npm i mongodb` - Also install [MongoDB.](https://docs.mongodb.com/manual/administration/install-community/)

`npm i twitter`

`npm i winston`

`npm i winston-daily-rotate-file`

# Configuration
`common.bot_admin` should be your Discord ID.

`discord.prefix` is the command prefix.

`discord.token` is your bot token.

`discord.status_channel` is the channel you want Xivvi to tell you random information in.

`discord.report_channel` is the channel you want Xivvi to send user reports to.

`discord.mod_roles` is an array of roles that can use the administrative commands like `~bulkdelete` etc.

`twitter.consumer_key`, along with the other three keys below, are your Twitter access tokens.

`twitter.consumer_secret`

`twitter.access_token`

`twitter.access_secret`
