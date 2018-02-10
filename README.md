# Resto-Bot
The purpose of this repository is for eventual testing on Discord.

I am creating this bot as part of my final semester at college. The goal is to teach myself a programming language or framework my teachers did not cover in class. I chose node.js and it looks like I'll also be using the discord.js library to compliment it.

This bot will be designed to -eventually- scan user roles and update them in a backup database periodically in the event of an accidental kick, server crash, or any sort of "I left and want to come back". Upon re-entry to a server, all previous roles will be re-added to the user. 

Planned features:
Role backup as roles are added and taken away from users
Role re-adding upon rentry to the server
Basic moderation - I.E. Features that will prevent bot abuse to regain roles you should no longer have.
Auto-deletion - If you leave a server, after X days, it'll remove that server and associated roles from you in the database

If you have any ideas for other features, send me a message. I just started learning node, but I'll try my best to eventually doing more with the bot.
