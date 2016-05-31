# [Sphero](https://telegram.me/Sphero) *And Professionall* [Helper](http://telegram.me/Spherorobot)

_Open Source For all_

_A new And Best Anti-Spam For Telegram Cli _

_Based on Yagop _

# *install req packages*
```sh
 sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
```
# *install redis

```sh
#Before you install redis, there are a couple of prerequisites that need to be downloaded to make the installation as easy as possible.

#Start off by updating all of the apt-get packages:

sudo apt-get update

#Once the process finishes, download a compiler with build essential which will help us install Redis from source:

sudo apt-get install build-essential

#Finally, we need to download tcl:

sudo apt-get install tcl8.5

# *Installing Redis*

#With all of the prerequisites and dependencies downloaded to the server, we can go ahead and begin to install redis from source
```

# *Download the latest stable release tarball from Redis.io.*

```sh
wget http://download.redis.io/releases/redis-stable.tar.gz

#Untar it and switch into that directory:

tar xzf redis-stable.tar.gz

cd redis-stable

#Proceed to with the make command:

make

#Run the recommended make test:

make test

#Finish up by running make install, which installs the program system-wide.

sudo make install

#Once the program has been installed, Redis comes with a built in script that sets up Redis to run as a background daemon.

#To access the script move into the utils directory:

cd utils

#From there, run the Ubuntu/Debian install script:

sudo ./install_server.sh

#As the script runs, you can choose the default options by pressing enter. Once the script completes, the redis-server will be running in the background.

sudo service redis_6379 start

#You can then access the redis database by typing the following command:

redis-cli

#You now have Redis installed and running. The prompt will look like this:

redis 127.0.0.1:6379>
```

# *To set Redis to automatically start at boot, run:*

*sudo update-rc.d redis_6379 defaults

# *to install sphero run this commands*

```sh
git clone https://github.com/3pehrdev/Sphero

cd Sphero

./launch.sh install

./launch.sh #Run Bot And Give Your Number
```

# *for installing anticrash run this commands

*Note: Anticrash does not work in free server likes C9

*tmux new-session -s script "bash steady.sh -t

# Please Check the *bot/utils.lua : line 962* and putt your api token
And check *bot/seedbot.lua : line 229* and putt your ID
* Good Source Is ready for you :)

*Dev by [MrBlackLife](http://telegram.me/mrblacklife)*

*edit by @RezaGameMaker*

# *Good Luck with your bot* 
