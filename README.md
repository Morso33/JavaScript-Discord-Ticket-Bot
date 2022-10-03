# JavaScript-Discord-Ticket-Bot



### A Simple Discord Ticket Bot Written In NodeJS, using DiscordJS.

## Features:

### Users being able to create private tickets between them and the Discord Guild's moderators.
### Users being able to close tickets via a button interaction
### Users being limited to one active ticket at a time (Prevents "nuking" of the server).
### Ticket history being saved in a private channel. It can be downloaded easily if you desire to do so.



## Setup:
### Create a Discord bot and add it to your server. This is a great tutorial if you are not familiar with this: https://discordpy.readthedocs.io/en/stable/discord.html
## Allow the following intents here: 
![Screenshot 2022-10-03 223335](https://user-images.githubusercontent.com/69962221/193672162-d4b2d5a9-e2b1-4e2d-ae72-2491652219fb.png)
### Update The bot's token on line 24 (index.js)
### Start the bot.
## Windows
### Run .bat in the root directory.
### -> npm i
### -> node .
## Linux
### -> CD to the root directory
### -> npm i
### -> node .
## The bot should be operational now. If everything worked you will see "started" in the console.
### Create a new category in Discord and paste the category ID into guilds.JSON (class_support)
### Create a new channel in Discord and paste the channel ID into guilds.JSON (saved_tickets)
### Create a channel for support and type . (or your own prefix) ticketsystem (example .ticketsystem)
### Congratulations, the ticket system is complete.


## Showcase

