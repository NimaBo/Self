# <p align="center">How To Run This Source ?

```sh
# Install dependencies.
# Tested on Ubuntu 14.04. For other OSs, check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev

# Install Self Bot
cd $HOME
git clone https://github.com/EhsanFox/Self-Bot-V3
cd Self-Bot-V3

# Set Sudo
Go to bot/self-bot.lua
Line [268] :
    sudo_users = {},
Add Telegram ID [[Not username]] ( For Get Your Telegram ID go to ThisBot > https://telegram.me/userinfobot )
And Save It

# Resume Run
cd ..
chmod +x launch.sh
./launch.sh install
./launch.sh # Phone Number # Telegram Code

```
#Nim_BO