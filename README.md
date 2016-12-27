# DragonBot Version 4

#Installation
### Install dependencies.
### Tested on Ubuntu 16.
```sh

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev


cd $HOME
git clone https://github.com/doroodzan/DragonBot.git
cd DragonBot
chmod +x launch.sh
./launch.sh install
./launch.sh
 بعد از زدن این دستور از شما شماره و کد تایید میخواد
Then Enter Your Phone And Confirmation Code
 ```
 

#برای ران کردن ربات با اتو لانچ از دستورات زیر استفاده کنید.
###For Launch With AutoLaunch :
```
chmod 777 DragonBot.sh
screen ./DragonBot.sh
```
و یا

```
cd DragonBot
killall screen
killall tmux
killall telegram-cli
tmux new-session -s script "bash steady.sh -t"
```

