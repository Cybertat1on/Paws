[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/PAWSOG_bot/PAWS?startapp=paJVq74B)
[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/CyberToolz)


#  Bot for Paws

![start-paws](https://github.com/user-attachments/assets/69d1d3e6-6366-4513-be84-23dbda3ed128)


# 🔥🔥 Use PYTHON 3.11.5 🔥🔥

> 🇷 🇺 README in russian available [here](README-RU.md)

## Features  
| Feature                                                     | Supported |
|---------------------------------------------------------------|:---------:|
| Multithreading                                                |     ✔     |
| Proxy binding to session                                      |     ✔     |
| Auto ref                                                      |     ✔     |
| Auto tasks                                                    |     ✔     |
| Support for pyrogram .session / Query                         |     ✔     |

## [Settings](https://github.com/Cybertat1on/Paws/blob/main/.env-example)
| Settings                |                                Description                                 |
|-------------------------|:--------------------------------------------------------------------------:|
| **API_ID / API_HASH**   |  Platform data from which to run the Telegram session (default - android)  |       
| **REF_LINK**            |                           Put your ref link here                           |
| **AUTO_TASK**           |                       Auto do tasks (default: True)                        |
| **DELAY_EACH_ACCOUNT**  |             Random delay bewteen accounts (default: [20, 30])              |
| **USE_PROXY_FROM_FILE** | Whether to use a proxy from the bot/config/proxies.txt file (True / False) |



## Quick Start

To install libraries and run bot - open run.bat on Windows

## Prerequisites
Before you begin, make sure you have the following installed:
- [**Python**](https://www.python.org/downloads/release/python-3115/) **IMPORTANT**: Make sure to use **3.11.5**. 

## Obtaining API Keys
1. Go to [**my.telegram.org**](https://my.telegram.org/auth) and log in using your phone number.
2. Select `API development tools` and fill out the form to register a new application.
3. Record the `API_ID` and `API_HASH` provided after registering your application in the `.env` file.

## Installation
You can download the [**repository**](https://github.com/Cybertat1on/Paws) by cloning it to your system and installing the necessary dependencies:
```shell
git clone https://github.com/Cybertat1on/Paws.git
cd Paws
```

Then you can do automatic installation by typing:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

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
~/Paws >>> python3 main.py --action (1/2)
# Or
~/Paws >>> python3 main.py -a (1/2)

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
~/Paws >>> python3 main.py --action (1/2)
# Or
~/Paws >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Termux manual installation
```
> pkg update && pkg upgrade -y
> pkg install python rust git -y
> git clone https://github.com/Cybertat1on/Paws.git
> cd Memelabs
> pip install -r requirements.txt
> python main.py
```

You can also use arguments for quick start, for example:
```termux
~/Paws > python main.py --action (1/2)
# Or
~/Paws > python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session 
```
