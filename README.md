# Download and install LuaSocket, LuaSec, Redis-Lua, ansicolors and serpent

 wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz
 tar zxpf luarocks-2.2.2.tar.gz
 cd luarocks-2.2.2
 ./configure; sudo make bootstrap
 sudo luarocks install luasocket
 sudo luarocks install luasec
 sudo luarocks install redis-lua
 sudo luarocks install lua-term
 sudo luarocks install serpent
 cd ..

 #Launch BOT!
 git clone https://github.com/saleh6020/pvBotXlinkGP.git
----------------------------------------------------------------- 
 local bot_api_key = "" --BOT TOKEN تو کن ربات خود را در اینجا قرار دهید
    local You = 188548712 --ID ADMIN ایدی خود را اینجا قرار دهید
    local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
    local BASE_FOLDER = ""
    
    --------------------------------------------------------------------------------
 #Launch BOT!
 cd pvBotXlinkGP
 chmod +x ./launch.sh
 ./launch.sh
 
 
 ------------------------------------------
بعد وارد ربات خود در تلگرام شده و دستور زیر را تایپ کنید

    /unbroadcast

    ربات شما حاظر است
    
    -----------------------------------------------------------------
    
    /ban

/unban

/users

/broadcast

/unbroadcast

/start

/id 
