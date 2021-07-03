# Welcome to Smart Raid Bot

This bot was written to facilitate the routine work associated with the game Raid Shads of Legends.
The program is developing and in the future, it is planned to introduce new automation (for example, automatic farming of arena, tower and so on). I can't say the exact timeframe, since the project is being developed purely on enthusiasm.

# Quick Start

Currently, only two language versions of the game are supported. English version and Ukrainian.

#### Important Notice
When launched, the bot will adjust the size and position of the game window. IMPORTANT: You cannot resize the game window while the bot is running! It is also not recommended moving this window (it is allowed if the sale of artifacts or the replacement of food is not expected), as this may disrupt the Raid Bot work (I am currently working on an improvement to remove this limitation, but when this problem will be solved is still unknown)
### Quick Start
 - Start the game
 - Start the Raid Bot and you will see a window: ![Main Window](https://github.com/Pavlo-dua/RaidBotPublic/blob/master/MainWindow.png)
 - Select the required scenario (look at the photo, point 1). There are 
	  - Currently two scenarios available: 
	  1. Food farming. Food Farming can farm food even if it is a background window. Knows how to sell artifacts and replace food in different modes (does not support    
   background window)
	  2. Dungeons. Can farm artifacts in background window. Knows how to sell artifacts depending on the rarity and the presence of speed in it (everything is configurable)
 - In the window number 3 in the photo, you can configure the bot behavior for the selected scenario.
 - In the settings (number 4 in the photo), you can configure the [Telegram](https://telegram.org/) (messaging program) so that the bot can send notifications with the photo that it is changing food or has finished the work. **Also, here you can switch between the languages in which the game is running.** 
 - In the game, you need to launch the desired level of dungeons, after which you can launch the bot (number 4 in the photo)
 - 
## Script execution setup details
This section is devoted to the specifics of setting up the scenario (number 3 in the photo):
### Food Farming
 - **Exact number of battles:** The exact number of battles. That is, if there is not enough energy, then an attempt will be made to buy energy.
 - **How many times do they buy energy:** How many times to buy energy. This item can be combined with the previous one.
 - **Only current energy:** Energy will not be bought. Can be combined with the first item (for example, if you want to run 40 fights, but do not  to want energy to be bought if it is not enough)
 - **Sell artifacts:** Whether to sell all the artifacts - *This action does not support background window*
 - **Up the champions to the maximum:** When the champion has reached the maximum level, whether it is necessary to make an automatic replacing with a new champion. - *This action does not support background window*
 - **Send with Photos:** If [Telegram](https://telegram.org/) is configured, you will receive notifications with a screenshot of the game.
- **Stop the script if the champion(s) have reached the maximum (for example, if you want the script to work even if the Raid window is not on top of all windows):** 
- **Up champions once for Tournaments:** Will train all the champions once and immediately replace them with new champions. This is useful if you need to quickly earn a lot of points to win the Tournaments.

### Dungeons
 - **Exact number of battles:** The exact number of battles. That is, if there is not enough energy, then an attempt will be made to buy energy.
 - **How many times do they buy energy:** How many times to buy energy. This item can be combined with the previous one.
 - **Only current energy:** Energy will not be bought. Can be combined with the first item (for example, if you want to run 40 fights, but do not  to want energy to be bought if it is not enough)
 - **Sell artifacts:** Whether to sell all the artifacts - *This action does not support background window*
 - **Sell all rare artifacts (Depends, Never, All):** Sell all rare artifacts. This item can take 3 values: Depends, Never, All.
 -- Depends: Depends on the state of the item "Leave only artifacts with speed". If this item is active, it will sell all rare artifacts except those with speed in their parameters.
 -- Never: Don't sell rare artifacts
 -- All: Sell all rare artifacts
 - **Sell all epic artifacts (Depends, Never, All):** By analogy with the previous item
 - **Leave only artifacts with speed:** See item "Sell all rare artifacts"
 ## Bot Settings
 ![Settings](https://github.com/Pavlo-dua/RaidBotPublic/blob/master/Settings.png)

In this window, you can configure [Telegram](https://telegram.org/) to receive messages about current status of the bot.
How do I create a bot? There's a… bot for that. Just talk to [BotFather](https://t.me/botfather) (described below) and follow a few simple steps:
Use the  **/newbot**  command to create a new bot. The BotFather will ask you for a name and username, then generate an authorization token for your new bot.

The  **name**  of your bot is displayed in contact details and elsewhere.

The  **Username**  is a short name, to be used in mentions and t.me links. Usernames are 5-32 characters long and are case insensitive, but may only include Latin characters, numbers, and underscores. Your bot's username  **must**  end in 'bot', e.g. 'tetris_bot' or 'TetrisBot'.

The  **token**  is a string along the lines of  `110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw`  that is required to authorize the bot and send messages. Keep your token secure and store it safely, it can be used by anyone to control your bot.
More details you can find here: [Telegram Bot](https://core.telegram.org/bots#6-botfather)
After you have created a Telegram Bot and received a token, you can enter it in the Telegram Bot Token field and then click the "Get" button. ![Settings Toke](https://github.com/Pavlo-dua/RaidBotPublic/blob/master/SettingsToken.png) A window will appear waiting for the input of any message to the Telegram Bot. That is, you need to open a Telegram and go to the chat of the created Telegram Bot and write any message there. Raid Bot immediately considers the Chat number of your Telegram Bo chat (if everything went well, the waiting window will close) and then click the save button.

