How to make a discord bot.


Creating the Bot App.

1-Go to https://discordapp.com/    and pick from the menu.  "Developers --> Developer Portal".  Login with your discord account.
 
![Preview](https://raw.githubusercontent.com/socializemeserver/Tutorial/master/df/01.png)



2-Choose "New Aplication" , pick whatever name and press "create".

![Preview2](https://raw.githubusercontent.com/socializemeserver/Tutorial/master/df/02.png)


3-Copy the Client ID and paste it in some place  you will need it. For this tutorial the Client id is: 620008032692207627

4- Now select BOT from the left menu and click on "Add Bot". Discord gonna ask you some shit.. you press "yes do it." and then copy the Token and paste it in some 
place.

Our token for this tutorial is: NjIwMDA4MDMyNjkyMjA3NjI3.XXQipQ.etUqi_mawR7SW_kaVAOxSuauag4

5-Now in the same page scroll down to give your bot the perms you want. in this tutorial we gonna select "administrator" perms. it allow all perms for the bot.

Copy the number for those perms in some place. in this tutorial the perms code is : 8.

6- Our bot app is done. Now we need invite the bot to the server so below replace CLIENT ID AND PERMISION CODE with the codes you copy before.

https://discordapp.com/oauth2/authorize?&client_id=CLIENT ID GOES HERE&permissions=PERMISION CODE GOES HERE&scope=bot 

Example:

https://discordapp.com/oauth2/authorize?&client_id=620008032692207627&permissions=8&scope=bot 

7-Now open your internet browser and paste this address in the browser bar. Press enter.. discord gonna ask you for login with your account then you gonna choose
which server you want to add the bot and you gonna have to solve a captcha.


We have done our bot app. What we need now is a plataform to run it. So we gonna use glitch for it.

1- go to https://glitch.com/ and login with a facebook, ghitub, gmail or email account. (I use ghitub account).

2-Choose "New Project" and "hello express" 

3-Now you will see a new page. Look for a file called "server.js" and rename it as "index.js"

4-Once you did the rename thing go here https://github.com/socializemeserver/Tutorial/blob/master/index.js  copy the whole code and replace your index.js

5-Now go here https://github.com/socializemeserver/Tutorial/blob/master/package.json copy the whole code and replace your package.json

6-find the file called .env and entry TOKEN= and paste the token you copy before.
example:
TOKEN=NjIwMDA4MDMyNjkyMjA3NjI3.XXQipQ.etUqi_mawR7SW_kaVAOxSuauag4

7-Now we gonna create a new file called "watch.json" and we gonna copy the whole code from here: https://github.com/socializemeserver/Tutorial/blob/master/watch.json

8-Now we check if the bot is working. Find "TOOLS"--> "LOGS"  if is working fine u will see something like: Logged in as tutorial#2464!

9-Now to give a test go to the server where you invited the bot and type !hello  the bot gonna answer "hello"
