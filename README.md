# Fun-Moderation-bot
a Fun moderation bot that contains 20+ commands and is made with discord.js


 <a href="https://discord.gg/uDyJGDpCw3">Join the community</a><br>
  <hr>
 
 #### Requirements & Steps
* This Project
* Node.js, Discord.js Installed
* Discord Bot Token, Prefix
* Edit the `config.js and owner.json` file
* Run `npm i` once in Terminal to install Dependencies
* Run `node index.js` to ***RUN*** the bot.

#### Features & Info
* Author: `Tryndable#7777`
* Moderation Bot built to manage discord servers.
* This bot has all the premium commands too. Hackban/forceban [Type of ip ban] is also available
* Modular Discord bot built entirely on pure JavaScript using Discord.JS.
* Modlogs for all the actions.

#### Moderation Commands
* Ban | Unban
* Deafen | Undeafen
* DisableModLogChannel | SetModLogChannel
* DisableMuteRole | SetMuteRole
* Dm 
* Hackban/Forceban | Unban
* Kick
* Lock channel | Unlock
* Lockdown [Only for emergency scenarios] | Unlock
* Mute | Unmute
* Purge
* RoleAdd
* RoleInfo
* RoleMemberInfo
* SetNick
* Slowmode
* Svr [Server Region change]
* VoiceMove [Move a peerson from one vc to another]
* Warn
* Whois
### Fun Commands
* Hug
* Kiss
* Slap
* Avatar
* Jail
* Hack 

# Install 
to install the bot you go to the config.js and you can change the prefix 
and the Token to take the token you go to the Discord Developer portal you make the bot you go in the bot section and you copy the Token 
then you go the console and type npm install to install packages and then you type node.index.js and your bot is running as well
and the last one you go to owner.js and you replace the id 
# 24/7 online 
if you want to host your bot 24/7 online you create a file with the name server.js and you take this code and you put on your server.js file 

const express = require("express");
const server = express();
 
server.all('/', (req, res) => {
  res.send("type whatever you want here")
})
 
function keepAlive() {
  server.listen(3000, () => { console.log("Server is Ready!!" + Date.now()) });
}
 
module.exports = keepAlive;
 
 when you have this code in your server.js fille you go in the index.js file and you put this codes 
 const keepAlive = require('./server.js');

const keepAlive = require('./server.js');

Type npm install 
And your can copy the link in the console and you go to UptimeRobot and your bot is online 24/7

# Show your Support 
if you like this project and helped you  give a ⭐ 

# Credits 
Bot Made by Tryndable#777



