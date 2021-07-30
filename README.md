<h1 align="center"><b>Inline media search Bot 🇱🇰</b></h1>

# Features 

* Index channel or group files for inline search.
* When you post file on telegram channel or group this bot will save that file in database, so you can search easily in inline mode.
* Supports document, video and audio file formats with caption support.
* Broadcast to the all of users in database
* Can view user stats in bot's database
* Can ban or unban any user from database

### Deploy to Heroku 🔥🕺 

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/youtubeslgeekshow/Inline-media-search-Bot)

###              The easiest way to deploy this  Bot
<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/youtubeslgeekshow/Inline-media-search-Bot"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="210" height="34.45"/></a></p>




### Easy Way

  


### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB]
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com)
* `BOT_OWNER` : user id of the owner
* `SESSION` : A session name for save users in db.
* `BOT_USERNAME` : Bot' username . Get it from botfather..
* `UPDATES_CHANNEL`: Username or ID of channel. Without subscribing this channel users cannot use bot.

### Optional Variables
* `COLLECTION_NAME`: Name of the collections. Defaults to Telegram_files. If you going to use same database, then use different collection name for each bot
* `MAX_RESULTS`: Maximum limit for inline search results
* `CACHE_TIME`: The maximum amount of time in seconds that the result of the inline query may be cached on the server
* `USE_CAPTION_FILTER`: Whether bot should use captions to improve search results. (True/False)
* `AUTH_USERS`: Username or ID of users to give access of inline search. Separate multiple users by space. Leave it empty if you don't want to restrict bot usage.
* `LOG_CHANNEL`: a channel id for save all the logs of bot
* `START_MSG`: Bot's Start Msg.
* `USERBOT_STRING_SESSION`: User bot string session.

## Admin commands
```
channel - Get basic infomation about channels
total - Show total of saved files
delete - Delete file from database
index - Index all files from channel or group
logger - Get log file
stats - get recent user stats
broadcast - broascast any message to all the users of the bot
```

