# Welcome to Smart Raid Bot

This bot was written to facilitate the routine work associated with the game Raid Shads of Legends.
The program is developing and in the future, it is planned to introduce new automation (for example, automatic farming of arena, tower and so on). I can't say the exact timeframe, since the project is being developed purely on enthusiasm.

# Quick Start

Currently, only two language versions of the game are supported. English version and Ukrainian.

 - Start the game
 - Start the Raid Bot and you will see a window: ![Main Window](https://github.com/Pavlo-dua/RaidBotPublic/blob/master/MainWindow.png)
 - Select the required scenario (look at the photo, point 1). There are 
	  - Currently two scenarios available: 
	  1. Food farming. Food Farming can farm food even if it is a background window. Knows how to sell artifacts and replace food in different modes (does not support    
   background window)
	  2. Dungeons. Can farm artifacts in background window. Knows how to sell artifacts depending on the rarity and the presence of speed in it (everything is configurable)
 - In the window number 3 in the photo, you can configure the bot behavior for the selected scenario.
 - In the settings (number 4 in the photo), you can configure the Telegram (messaging program) so that the bot can send notifications with the photo that it is changing food or has finished the work. **Also, here you can switch between the languages in which the game is running.** 
 - In the game, you need to launch the desired level of dungeons, after which you can launch the bot (number 4 in the photo)
 - 
## Script execution setup details
This section is devoted to the specifics of setting up the scenario (number 3 in the photo):
 - **Exact number of battles:** The exact number of battles. That is, if there is not enough energy, then an attempt will be made to buy energy.
 - **How many times do they buy energy:** How many times to buy energy. This item can be combined with the previous one.
 - **Only current energy:** Energy will not be bought. Can be combined with the first item (for example, if you want to run 40 fights, but do not  to want energy to be bought if it is not enough)
 - **Sell artifacts:** Whether to sell all the artifacts - *This action does not support background window*
 - **Up the champions to the maximum:** When the champion has reached the maximum level, whether it is necessary to make an automatic replacing with a new champion. - *This action does not support background window*
 - 
