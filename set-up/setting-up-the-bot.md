# Setting up the Bot

1. Once the required software is installed on your system, open up the command prompt, and set the directory which you'd like to store the bot in using `cd` as seen here: `cd C:\Users\RockyRoss\Documents\RoMinistrator`
2. Next, run: `git clone https://github.com/RockyRosso/RoMinistrator`
3. Then run: `cd RoMinistrator`
4. Next, to install all the packages, run: `npm i`
5. Before running the bot, make sure to create a `.env` file and to add the following variables:

* BOT\_TOKEN
* API\_KEY

6. Set the `BOT_TOKEN` variable to the created bot, and set the `API_KEY` variable to your created Roblox API key.
7. Open up the `config.json` file which can be found in the `src` folder. Set the `guildid` to the server you added the bot into, and set the `universe_id` to the universe ID of the game you wish to manage. To find the universe ID for your game, go to [https://creator.roblox.com](https://create.roblox.com/). If the game is a group game, select your profile on the left side underneath `CREATOR`, and select the group which the game is in. Find the game in the `EXPERIENCES` tab, then hover over the game, and click on the three dots. You can then click `Copy Universe ID` to acquire it. Otherwise within the config file, feel free to change the settings to your pleasing.
8. Once everything is configured and set up, go back into your command pallet and type:

```
node index.js
```

Your bot should then turn online and be ready to go.
