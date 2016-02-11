# xkcd Telegram bot
## Thanks to Randall Munroe for all the fun

All contents come from [xkcd.com](http://xkcd.com)

Chat with [@xkcd_unofficial_bot](https://telegram.me/xkcd_unofficial_bot)

# Commands
- `/latest`
- `/random`
- `/getxkcd N` (specify a number, e.g. `/getxkcd 30`)
- `/now`

# Configuration
The configuration file must be placed in **config/** directory and must be named **config.json**. Look at the **config/sample-config.json** to know what you should and shouldn't config!

By the way, here there's a list:
- Bot token
- Host server and Web Hook
- SSL certificate and key directory
- Latest comic polling rate

# Available debug envvars
- 'debug'
- 'cmd'
- 'request'

Debug usage:
        
        $ DEBUG='debug|cmd|request' node index.js
