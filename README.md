<style>body {<br />
  background: #f1f1f1;<br />
  font-family: 'Poppins', sans-serif;<br />
}</p>
<p>h1 {<br />
  text-align: center;<br />
  text-transform: uppercase;<br />
  background: linear-gradient(45deg, #f47d0d, #0621e0);<br />
  letter-spacing: 10px;<br />
  -webkit-background-clip: text;<br />
  -webkit-text-fill-color: transparent;<br />
} </p>
<p>.fa {<br />
  width: 40px;<br />
  height: 40px;<br />
  line-height: 40px;<br />
  border-radius: 50%;<br />
  border: 2px solid #FFF;<br />
  margin-right: 10px;<br />
  text-align: center;<br />
}</p>
<p>.gradient-btn {<br />
  color: #FFF;<br />
  display: inline-block;<br />
  height: 70px;<br />
  line-height: 70px;<br />
  width: 240px;<br />
  margin: 10px;<br />
  padding-left: 20px;<br />
  border-radius: 50px;<br />
  box-shadow: 5px 5px 2px -2px #a5a5a5;<br />
}</p>
<p>.btn-1 {<br />
  background-image: linear-gradient(to right top, #fdbe25, #fec928, #ffd42b, #ffdf31, #ffea37);<br />
}</p>
<p>.btn-2 {<br />
  background-image: linear-gradient(to right top, #fab823, #f9a315, #f68d0c, #f3770d, #ee5f13);<br />
}</p>
<p>.btn-3 {<br />
  background-image: linear-gradient(to right top, #eb4f12, #e74717, #e23f1b, #de361e, #d92d21);<br />
}</p>
<p>.btn-4 {<br />
  background-image: linear-gradient(to right top, #ed433f, #df3a37, #d2302f, #c42627, #b71b1f);<br />
}</p>
<p>.btn-5 {<br />
  background-image: linear-gradient(to right top, #b71c24, #c41c3c, #cf2154, #d72c6d, #db3a86);<br />
}</p>
<p>.btn-6 {<br />
  background-image: linear-gradient(to top, #d83f91, #d0409b, #c743a5, #bb47af, #ae4bb8);<br />
}</p>
<p>.btn-7 {<br />
  background-image: linear-gradient(to top, #a94bb9, #9b46b7, #8d42b5, #7d3eb2, #6d3ab0);<br />
}</p>
<p>.btn-8 {<br />
  background-image: linear-gradient(to top, #5540cd, #493fc7, #3c3ec0, #2e3dba, #1e3bb3);<br />
}</p>
<p>.btn-9 {<br />
  background-image: linear-gradient(to top, #1c3eb4, #154cbd, #1059c6, #1266ce, #1b73d5);<br />
}</p>
<p>.btn-10 {<br />
  background-image: linear-gradient(to top, #4292ff, #388cff, #2e86ff, #2380ff, #177aff);<br />
}</p>
<p>.btn-11 {<br />
  background: linear-gradient(to right, #11998e, #38ef7d);<br />
}</p>
<p>.btn-12 {<br />
  background: linear-gradient(to right, #aaffa9, #11ffbd);<br />
}</p>
<p>.btn-13 {<br />
  background: linear-gradient(to right, #348f50, #56b4d3);<br />
}</p>
<p>.btn-14 {<br />
  background: linear-gradient(to right, #403b4a, #bbbbb4);<br />
}</p>
<p>.gradient-btn:nth-child(odd):hover {<br />
  cursor: pointer;<br />
  box-shadow: -6px -9px 2px -2px #a5a5a5;<br />
  transition: all 2s ease;<br />
  transform: translateX(10px);<br />
}</p>
<p>.gradient-btn:nth-child(even):hover {<br />
  cursor: pointer;<br />
  box-shadow: 8px 8px 2px -2px #a5a5a5;<br />
  transition: all 2s ease;<br />
  transform: translateX(-10px);<br />
}<br />
</style>
<p align="center"><img src="https://telegra.ph/file/cb7d19dc04371dd81b747.jpg" /></p>
## Lucy Heartfilia Robot

### Telegram Group
<div class="gradient-buttons">
<div class="gradient-btn btn-10"><i class="fa fa-telegram"></i>
Telegram Group</div>
<p align="left"><a href="https://telegram.dog/LucyHelpSupport"> <img src="https://aleen42.github.io/badges/src/telegram.svg" /> </a></p>
### Bot And Channel

* Bot Link: <a href="http://t.me/Lucy_Heartfilia_Robot"> <img src="https://img.shields.io/badge/%F0%9F%A4%96%20-GabiBraun-blue" /></a>
<div class="gradient-btn btn-2"><i class="fa fa-telegram"></i>
LucyHeartfilia</div>
* Log Channel: <a href="https://t.me/Lucylogs"> <img src="https://img.shields.io/badge/%F0%9F%92%A1-gabibraun%20Log%20Channel-9cf" /></a>
<div class="gradient-btn btn-3"><i class="fa fa-telegram"></i>
Telegram Channel</div>
&nbsp;

### Creating your own modules.

Creating a module has been simplified as much as possible - but do not hesitate to suggest further simplification.

All that is needed is that your .py file is in the modules folder.

To add commands, make sure to import the dispatcher via

Lucy Heartfilia import dispatcher.

You can then add commands using the usual

dispatcher.add_handler().

Assigning the help variable to a string describing this modules' available
commands will allow the bot to load it and add the documentation for
your module to the /help command. Setting the mod_name variable will also allow you to use a nicer, user-friendly name for a module.

The migrate() function is used for migrating chats - when a chat is upgraded to a supergroup, the ID changes, so
it is necessary to migrate it in the DB.

The stats() function is for retrieving module statistics, eg number of users, number of chats. This is accessed
through the /stats command, which is only available to the bot owner.

## Starting the bot.

Once you've set up your database and your configuration is complete, simply run the bat file(if on windows) or run (Linux):

python3 -m GabiBraunRobot

You can use nssm to install the bot as a service on windows and set it to restart on /gitpull
Make sure to edit the start and restart bats to your needs.
Note: the restart bat requires that User account control be disabled.

For queries or any issues regarding the bot please open an issue ticket or visit us at
<div class="gradient-buttons">
<div class="gradient-btn btn-10"><i class="fa fa-telegram"></i>
Telegram</div>
## How to setup on Heroku
For starters click on this button

## Our Telegram Channel and Group

* [Support](https://t.me/LucyHelpSupport)
<h1><strong> Credits</strong></h1>
The original builder of this bot
* [The Ghost Hunter](https://telegram.dog/The_Ghost_Hunter)

All original credits go to <a href="https://telegram.dog/The_Ghost_Hunter">The Ghost Hunter</a>, Without his efforts, this fork would not have been possible

</div>
</div>
