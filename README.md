# reddit-stream
Gets top Reddit posts from specified subreddits.

## To Install:
Simply running `install.bat` will install all node.js dependencies, and create the `run.bat` file.

## To Setup:
If you're going to be running this on your computer, create a bot account by going to 
[this](https://discordapp.com/developers/applications/me) page.

Once you've created a new application, create a bot account for it by clicking the corresponding button on the above page.
Then, get your bot's 'token', by clicking the 'reveal token' button on that same page. Copy-paste this into `config.json`, 
in the token field (currently it should say "your_bot_token").

The penultimate task is to get your guild and channel IDs for the channel the bot will be posting to. To do this, 
open discord and navigate through the 'User Settings' menu to 'Appearance', then scroll down and enable 'Developer Mode' option.
This will allow you to right-click on servers, channels and users to get their ID. For this step, you're only going to need a 
server and channel ID, corresponding to the server and that server's channels you want to post to through the bot.

Lastly, you'll need a Reddit API token. If you're reading this, htcmoneyzzz, message me and I'll give you one I made for this 
already. Other people using this will need to supply their own.

Oh, you'll need `ws` as well. You probably have it, but if not you can get it [here](http://go.microsoft.com/?linkid=9816758), 
as long as you're Windows. I'm not sure how other OS work with this, so you might need some research.

## To Run:
Running is easy - just run `run.bat`. Suspicious? Good, you're not stupid. Feel free to check it out, but it's just a 
script to run the bot, without you needing to waste your time opening cmd, etc.
The command format is `dm:top [subreddit name] [number of results]`, for example: `dm:top dankmemes 5`. 
Note because of the way I've written the bot, you can provide the subreddit as just the name or '/r/subreddit'
