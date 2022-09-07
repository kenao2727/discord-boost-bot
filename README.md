<h1 align="center">
 <br>
  <a href="https://github.com/crusions"><img src="[https://cdn.discordapp.com/attachments/1009659952148774912/1014160903614234644/giphy.gif]"></a>
  <br>
  Encrypted Services Boost Bot!
 <br>
</h1>

<h3 align=center>A fully customizable bot written in Python 3.9</h3>

<div align=center>

 <a href="https://crusions.xyz">
    <img src="https://img.shields.io/badge/Encrypted-Services-black" alt="dad">
  </a>
  
  <a href="https://python.org">
    <img src="https://img.shields.io/badge/Python-v3.9-orange.svg?logo=python" alt="python">
  </a>

  <a href="https://www.eclipse.org/legal/epl-2.0/">
    <img src="https://img.shields.io/badge/license-Eclipse%202.0-orange" alt="license">
  </a>

</div>

<p align="center">
  <a href="#features">Features</a>
  •
  <a href="#installation">Installation</a>
  •
  <a href="#setting-up">Setting Up</a>
  •
  <a href="#license">License</a>
  •
  <a href="#donate">Donate</a>
</p>


If you liked this repository, feel free to leave a star ⭐

## Features

- **/addadmin**
- **/boost** 
- **/cashapp** 
- **/restock** 
- **/stock**
- **/vccgen**
- **/whitelist**



## Installation

First clone the repo:

```
git clone https://github.com/crusions/discord-boost-bot.git
```

After cloning,

```
run main.exe
```

## Setting Up

Your `settings.json` should follow

- "capmonsterKey": Capmonster API Key for completing Captchas,
- "botToken": Your bot Token,
- "guildID": The server you are going to be running the commands in,
- "botAdminId": This is your bot Admin ID (They are able to boost & whitelist),
- "botWhitelistedId": Any Users you'd like to be able to use the bot (you can put yours in all),


	## Tutorial for dummies
 
 How to use Discord Nitro Boost Bot:
 
	* First make sure you have your bot token and everything need for this, turn on developer mode in your discord client if you havent already.
	  (You can get your bot token from https://discord.com/developers/applications)

	  a) Make sure you have extracted the files to your desktop or somewhere you know how to access its directory.

	* Second, in main.py scroll all the way down to line 505

	    a) Open Command Prompt and type in "wmic csproduct get uuid" it should output your uuid.
	    b) Go to pastebin and paste your hwid & create a new paste.
	    c) Copy the link and replace in main.py

	* Replace your bot token, guild id & your own id inside settings.json

	* Type https://capmonster.cloud in your browser and create a new account (this is for solving captchas, you MUST have money on the account for your key  to work.)

	* Enter Capmonster Cloud API key into settings.json aswell. (Create a ticket in the discord if you'd like to use my key)

	* Run install.bat to install the neccesary packages.

	* Finally, you should be able to run start.bat


	PS: If you'd like to make this file into an exe, make sure you're in the directory "cd boostsrc" then run "pyinstaller --onefile main.py". The file will be in /boostsrc/dist/
 

## License

Released under the [Eclipse License](https://www.eclipse.org/legal/epl-2.0/) license.


## Donate

You can donate and make my dick bigger than ever [by clicking here](https://paypal.me/daddycrusions)!
