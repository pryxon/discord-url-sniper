Hello!

Discord URL Sniper is a bot tool that automatically captures new invite links created in Discord servers. To use this bot, you need to meet some requirements.

Python must be installed. If you don't have it installed, you can download and install it from https://www.python.org/downloads/.

The Discord.py module must be installed. You can install it by running the following command in your terminal or command prompt:

Copy code
pip install discord.py
If you encounter an error, try running the pip install --upgrade pip command to upgrade pip, and then try installing it again.

The Selenium module must be installed. You can install it by running the following command in your terminal or command prompt:

Copy code
pip install selenium
If you encounter an error, you may need to first download and install the Chrome browser. Then, you can download ChromeDriver from https://sites.google.com/a/chromium.org/chromedriver/downloads, add it to your PATH variable, and try again.

Once you have met these requirements, you can follow these steps to run Discord URL Sniper:

First, create a Discord account for your bot and join a server with it.

Download the code for Discord URL Sniper. You can download the code from the bot's official GitHub page: https://github.com/pryxon/discord-url-sniper

Open the code in a text editor and find the line token = "BOT_TOKEN". Replace BOT_TOKEN with your Discord bot's token.

In the line prefix = "BOT_PREFIX", replace BOT_PREFIX with the command prefix value for your bot. This prefix will help your bot recognize its commands. For example, you can use "!" as the prefix.

Run the main.py file.

The bot will start running and will send a message to the relevant channel when a new invite link is created. Enjoy using it!
