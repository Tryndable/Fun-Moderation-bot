# Fun-Moderation-bot
a Fun moderation bot that contains 20+ commands and is made with discord.js v12

 <a href="https://discord.gg/uDyJGDpCw3">Join the community</a><br>
  <hr>

# Install 
to install the bot you go to the config.js and you can change the prefix 
and the Token to take the token you go to the Discord Developer portal you make the bot you go in the bot section and you copy the Token 
then you go the console and type npm install to install packages and then you type node.index.js and your bot is running as well
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

