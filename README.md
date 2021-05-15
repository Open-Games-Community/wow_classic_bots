# Wow Classic With Bots

Hello everyone, this release is a Wow Mangos with Bots, they got included TBC & WOTLK expansions, but are not stable at this moment, so you can enjoy the game playing on Vanilla.

## Installation

* DO NOT install this repack over old one. This update is not a "copy and replace old files" kind.
* Download the installer (if you haven't done this before) - SPP_Classics_V2.exe.
* Installer is a 7z self exctacting archive, it will extract "SPP_Classics V2" folder where you put it.
* It is recommended to use SSD if you have one
* Run it and click Extract
* Open the unpacked SPP_Classics_V2 folder and run Server_Update.bat and wait for it to download all necessary files. (~300 MB).
* After it is ready you will see Expansion selection menu.
* Expansions are downloaded "per request", e.g. TBC files (maps/mmaps...) are only downloaded if you select TBC expansion.
* Select desired expansion by typing expansion menu number and hit Enter. Expansion files will be downloaded and installed automatically.
* DO NOT close the launcher during the process! I'm serious!
* When its ready you will see Expansion menu, with "Start Servers (Win64)" and other options.
* Bot Addon
* You can find latest Mangosbot Addon for WoW in SPP_Server/Addons folder. Copy Mangosbot folder in WoW/Interface/AddOns/
  When you start the game make sure "Load out-of-date Addons" is enabled in Addons list.
Settings
* Before you start, you can edit the Settings in SPP_Classics_V2/SPP_Server/Settings/%expansion%/ folder
aiplayerbot.conf:
Find these settings:
AiPlayerbot.MinRandomBots = 1000
AiPlayerbot.MaxRandomBots = 1000
AiPlayerbot.RandomBotMinLevel = 1
AiPlayerbot.RandomBotMaxLevel = 60

* By default bot number is 1000. If you experience lag after 30+ minutes of running the server, try lowering bot number.
* Important!: if you change bot number later, you will need to do "6 - Bots Menu -> Reset Random Bots" for changes to take effect.

AiPlayerbot.SyncQuestWithPlayer = 0

* If you set this to 1, bots in group will automatically complete & get reward from quest (If they have it) when you complete it.
E.g. you take quest to loot 10 items. You have 4 bots in group, they also take it. You loot 10 items, go back and complete the quest. Bots will complete it automatically and get rewards. So you won't have to loot 40 more items. Bots will ignore looting quest items.
AiPlayerbot.AutoLearnTrainerSpells = 0
AiPlayerbot.AutoLearnQuestSpells = 0

With this set to 1 bots will learn new spells/quest spells on levelup.
You can leave other settings unchanged.


## Other

In Spp / addons you will find Mangosbot, for the vanilla extension, download a client founded on ethernet , then place mangosbot addon in interface/addons.




