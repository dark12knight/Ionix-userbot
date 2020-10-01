# 𝗜𝗢𝗡𝗜𝗫 𝗨𝗦𝗘𝗥𝗕𝗢𝗧

<p align="center">
<img src="https://telegra.ph/file/146232d08048652cb7ca2.jpg" alt="Ionix userbot">


[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)



Most powerful userbot ever
## 𝗠𝗼𝘀𝘁 𝗽𝗼𝘄𝗲𝗿𝗳𝘂𝗹𝗹 𝘂𝘀𝗲𝗿𝗯𝗼𝘁 𝘁𝗼 𝗺𝗮𝗻𝗮𝗴𝗲 𝘂𝗿 𝘁𝗲𝗹𝗲𝗴𝗿𝗮𝗺 𝗮𝗰𝗰𝗼𝘂𝗻𝘁

## © By Team #S

### For any query or want to know how it works join Group And Channel 

<a href="https://t.me/ionox_ot_"><img src="https://img.shields.io/badge/Join-Telegram%20Group-red.svg?logo=Telegram"></a>
<a href="https://t.me/Ionix_updates"><img src="https://img.shields.io/badge/Join-Telegram%20channel-blue.svg?logo=telegram"></a>

## HOW TO DEPLOY 




### Deploy Ionix In Heroku

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://githubhttps://github.com/matrixhackz/Ionix-userbot)

## Telegram-String

[![Run on Repl.it](http://repl.it/badge/github/Matrixhackz)](https://generatestringsession.devagyasharma.repl.run/)


### The Normal Way

Simply clone the repository and run the main file:
```sh
git clone https://github.com/starkGang/Fridayuserbot
cd FridayUserbot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```


### UniBorg Configuration


The UniBorg Config is situated in `userbot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.

## Credits 
```- Thanks To All Contributers For This Project 
- $ Full Repo - X-Tra Telegram 
- $ Lyrics Plugin // Inline Fix - @MrConfused
- $ Sudo Credits - Uniborg , @MrConfused
- $ Some Bug Fixes - @Adarsh_xD , @Aid_3n, @Sur_vivor, @Everythingsuckz, @PureindiaLover 

Check More Contribution At https://github.com/StarkGang/FridayUserbot/graphs/contributors
