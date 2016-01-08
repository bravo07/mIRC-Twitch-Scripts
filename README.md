# mIRC-Twitch-Scripts
The main focus of the scripts on this GitHub are for use with a Twitch mIRC bot that works in conjunction with AnkhBot and AnkhBot's point system.  [AnkhBot](http://marcinswierzowski.com/Code/AnkhBotR2/) is a free and versatile Twitch bot, yet like most things, there is always room for improvement.  These scripts are designed to compliment and enchance a Twitch channel that is currently running AnkhBot, however, many of the scripts can also be easily modified to use without AnkhBot.  See the [wiki](https://github.com/Blasman/mIRC-Twitch-Scripts/wiki) for more information regarding each script.

# Installation

### If You Do Not Have a mIRC Twitch Bot, Set One Up

1. Download and install mIRC. UNCHECK EVERYTHING except "Scripts" and "Help Files" on the "Choose Components" section of the install, as you don't need most of it. http://www.mirc.com/get.html

2. Get your bot's Twitch account up and running with mIRC, and set up your Twitch channel as an auto-join channel as well. See http://help.twitch.tv/customer/portal/articles/1302780-twitch-irc#mIRC%20guide or https://www.youtube.com/watch?v=k7ULgVCZ3Ns

## Once You Do Have a mIRC Twitch Bot
### Download Required Scripts
To use any of the games scripts in this GitHub, you will need to download the following scripts to your mIRC directory.  If you did not change the default install directory of mIRC, you can find the directory by typing %APPDATA%/mIRC into your Windows Folder Titlebar.
* [JSONForMirc.mrc](https://raw.githubusercontent.com/SReject/mTwitch/master/resources/JSONForMirc.mrc): right click this link and "save link as..." to your mIRC directory.
* [mTwitch.Core.mrc](https://raw.githubusercontent.com/SReject/mTwitch/master/mTwitch.Core.mrc): right click this link and "save link as..." to your mIRC directory.
* [mTwitch.GroupChat.mrc](https://raw.githubusercontent.com/SReject/mTwitch/master/mTwitch.GroupChat.mrc): right click this link and "save link as..." to your mIRC directory.
* [mIRC SQLite](http://hawkee.com/scripts/11648275/): Extract the .zip file from this webpage to your mIRC directory.
* [ankhbot.mrc](http://raw.githubusercontent.com/Blasman/mIRC-Twitch-Scripts/master/ankhbot.mrc) : right click this link and "save link as..." to your mIRC directory. **Before loading, be sure to read and edit the variables at the beginning of the script.**

### Install Required Scripts
First, edit and save the ankhbot.mrc script in a text editor, and read the info at the beginning of the script, and change the needed variables.  Then, in mIRC, type in the following commands anywhere:  

/load -rs JSONForMirc.mrc  
/load -rs mTwitch.Core.mrc  
/load -rs mTwitch.GroupChat.mrc  
/load -rs msqlite.mrc  
/load -rs ankhbot.mrc  

### Download and Install Desired Scripts
For information on each script, see the [wiki](https://github.com/Blasman/mIRC-Twitch-Scripts/wiki).  You can also right click the links on the wiki and select "save link as..." and then use */load -rs script.mrc* just like the previous install instructions.  Do Not "save link as..." using the links on the main page, as they are links to the GitHub html pages.
