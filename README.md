## Recommendation before use

# 🔥🔥 Use PYTHON 3.11.5 🔥🔥

## Features  
| Feature                                                   | Supported |
|-----------------------------------------------------------|:---------:|
| Multithreading                                            |     ✅     |
| Proxy binding to session                                  |     ✅     |
| Support for tdata / pyrogram .session / telethon .session |     ✅     |
| Auto-farming                                              |     ✅     |
| Auto-tasks                                                |     ✅     |
| Auto-upgrade                                              |     ✅     |
| Auto-check-in                                             |     ✅     |
| Auto-hunt                                                 |     ✅     |
| Auto-sell worms                                           |     ✅     |


## [Settings](https://github.com/vanhbakaa/Seed-App-Mine-Seed-BOT-Telegram/blob/main/.env-example)

# Use default setting for best performance !
| Settings                |                                 Description                                 |
|-------------------------|:---------------------------------------------------------------------------:|
| **API_ID / API_HASH**   | Platform data from which to run the Telegram session (by default - android) |
| **AUTO_UPGRADE_STORAGE**|                   Auto upgrade storage  (by default - True)                 |
| **AUTO_UPGRADE_MINING** |                  Auto upgrade mining speed (by default - True)              |
| **AUTO_UPGRADE_HOLY**   |                    Auto upgrade holy (by default - True)                    |
| **AUTO_TASK**           |                       Auto tasks (default - True)                           |
| **AUTO_START_HUNT**     |                    Auto start hunt (default - True)                         |
| **AUTO_SELL_WORMS**     |    Auto sell worms (default - True)           |
| **WORM_LVL_TO_SELL**     |    Auto sell worms by rarity (1 is common - 2 is uncommon - 3 is rare - 4 is epic) (default - 2)           |
| **PRICE_TO_SELL**       |                   Price to sell worms (0 is auto) (default - 0)             |
| **QUANTITY_FOR_SALE**   |                  Max worms to put on sale (default - 3)                     |
| **USE_PROXY_FROM_FILE** | Whether to use a proxy from the bot/config/proxies.txt file (True / False)  |

## Quick Start 📚

To fast install libraries and run bot - open run.bat on Windows or run.sh on Linux

## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **version 3.10**

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.


# Linux manual installation
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

You can also use arguments for quick start, for example:
```shell
~/Seed-App-Mine-Seed-BOT-Telegram >>> python3 main.py --action (1/2)
# Or
~/Seed-App-Mine-Seed-BOT-Telegram >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows manual installation
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```

You can also use arguments for quick start, for example:
```shell
~/Seed-App-Mine-Seed-BOT-Telegram >>> python main.py --action (1/2)
# Or
~/Seed-App-Mine-Seed-BOT-Telegram >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

### Contacts

For support or questions, you can contact me [![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/airdrop_tool_vanh)
