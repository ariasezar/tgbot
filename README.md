 
    <div align="center">
    <a href="https://telegram.me/sezarinfo">
        <img src="http://upir.ir/951/guest/Untitled-7.png" hspace="10" width="150">
    </a>
    <a href="https://telegram.me/SsS_ARIA_SsS">
        <img src="http://upir.ir/951/guest/Untitled-6.png" width="150">
    </a>
</div>
<a href="https://telegram.me/sezarinfo"><font size="100"></font></a>)


* * *


# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/sezarvip/tgbot.git
cd tgbot
chmod +x sezar.sh
./sezar.sh install
./sezar.sh 
# Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/sezarvip/tgbot.git && cd tgbot && chmod +x sezar.sh && ./sezar.sh install && ./sezar.sh
```

* * *

### launch Bot

```
killall -9 bash
cd tgbot && killall screen && screen ./sezar.sh
```

* * *


### auto launch 
```
bi pv :)
@sezarinfo
```

* * *


### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    377450049,
    0,
    YourID
  }
