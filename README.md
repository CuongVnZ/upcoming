# Athena 1.1.0

Original source:
Author: Sucy

## Dependencies
* HikariCP (https://github.com/brettwooldridge/HikariCP)
* Spigot (https://github.com/SpigotMC)
* EffectLib (https://github.com/dmulloy2/ProtocolLib)
* Citizens (https://github.com/CitizensDev/Citizens2)
* LibsDisguises (https://github.com/libraryaddict/LibsDisguises) - Not implemented yet
* uVotifier ()

## Features

Please note that these features are for my personal server. It probably will not work in any other setup.
* Characters
  * Only one character per account.
* Classes
  * You have to select a class for your character when you are creating one.
  * There are 9 different classes you can select;
  * Crusader: Deals heavy damage with their two handed weapons but slow on feet
  * Archer: Good at dealing high damage to a single target, also dual wielding daggers looks cool
  * Wizard: Filling up tank role with thier heavy armor and shield
  * Paladin: Supports their allies with buffs and heals
  * Assassin: Deals damage from long ranged and has the ability kit to keep that range
  * Samurai: Deals high damage from long range with their crossbows. Uses traps to hunt their targets
  * Bard: Musician?
  * Monk: Nam mo a di da phak
* Spells
  * Class spells and mob spells.
  * Each class has from 6-7 spells.
  * Using spell point to upgrade spell.
* Skills (Removed? Remake)
  * Life skills:
  * Gathering, Smithing, Miner, ...
* Quests
  * Icons: 
    Quest icons appear on NPCs and disguises themselfs to each player differently. 
    If player has a completed quest from this NPC, he/she will see a 3D Q icon.
    Else if player can accept a new quest from this NPC,  he/she will see a 3D ? icon.
    Else if player has a quest in progress from this NPC,  he/she will see a 3D ! icon.
    Else he/she will see nothing.
  * Gui: 
    Players can open a gui including quests of a NPC and accept/complete them.
  * Actions: 
    Perform specific actions when player accepts, completes and turns in a quest.
  * Tasks: 
    Add specific tasks for your players to complete. You perform can actions on task complete too.
  * Rewards: 
    Give experience, money and/or items to your players when they turn in a quest.
* GuiBook
  * Create gui with unlimited pages.
    Think of items as words. Make a line from items. Make a page from lines. Make a book from pages.
* Merchants/Traders
  * Open a gui on right click to NPC.
    Select specific actions from this gui like buying/selling items...
* Spawners
  * Configuration for mob spawners.
* RPG Items/Equips
  * Material items
  * Armors/Weapons
  * Accessories
* Trade
  * Player 1:1 item trading
  * Invite a player to trade. If he/she accepts a Trade-Gui will open for both players.
  * Add/remove items you will give to other player. Also you can see which items you will receive from other player.
  * Lock the trade. Once locked players can't add/remove items.
  * Accept the trade. When both players accept the trade finishes and items on Trade-Gui gets traded.
* Party
  * Fight together with your friends
  * Share experience gained from monsters with party members
  * Progress at your quests' together
* Guild
  * Create guild to gather a strong army and fight for power
  * Manage your guild with commands such as guild members' ranks
* GuildWars
  * Guild leader or commanders can join your guild to a GuildWar
  * The goal is conquering the castles on map
  * Each castle will give your team +1 point per second
  * First team that reaches the goal point wins the GuildWar
* Minigames (Not yet)
  * Escape the dungeon?
* Dungeons (Disabled
  * I'm fucking to try to make instance dungeon :< 
* Jobs
  * There are 4 type of jobs. Weaponsmith, armorsmith, alchemist, jeweller
  * Weaponsmith crafts ranged & melee weapons. Armorsmith crafts heavy & light armor. Alchemist crafts potions & foods(buff). Jeweller crafts jewels & enchanting stones.
  * There are 4 type of gathering tools. Axe, hoe, pickaxe, fishing rod. Tools lose durability when you gather ingredients with them.
  * There are 6 types of gathering. Woodcutting, harvesting_flower, fishing, mining_ore, mining_jewelry, hunting
  * You can open crafting gui by right clicking certain blocks like anvil, grindstone etc
  * On crafting gui, select the level of items you want to create, then craft by clicking on items at cost of ingredients
  * You can gain job experience by crafting and unlock higher level crafts
* Pets
  * Useless pet :v. For decorating/some abilities?
* Respawn
  * Revive at closest town
  * Then you can choose to revive here or become a soul and search for your tomb. If you can find your tomb in 2 minutes, left click to revive there
