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
![createTicket](https://user-images.githubusercontent.com/69962221/193672628-d62bd897-7328-46e1-bbc3-a900b9fda5f3.png)
### Pressing the button will open a ticket
![Screenshot 2022-10-03 223752](https://user-images.githubusercontent.com/69962221/193672918-ad30c644-9410-49a5-8714-6abe3960ad62.png)
### Typing .resolve will bring up a notification asking if the client wants to close the ticket.
![Screenshot 2022-10-03 224028](https://user-images.githubusercontent.com/69962221/193673734-a2b20728-42fb-4379-ab39-45319581c044.png)
### Pressing the close button will start a five second timer, after which the channel is indexed and deleted.
![Screenshot 2022-10-03 224044](https://user-images.githubusercontent.com/69962221/193673552-f330b86e-c9bf-4c31-8cdc-58cffcd9cd29.png)
### The tickets history (Last 100 messages) will be saved in the channel you specified in guild.json
![Screenshot 2022-10-03 224137](https://user-images.githubusercontent.com/69962221/193674243-533ab10a-63a8-4c7b-a670-e1b47212b0b8.png)

