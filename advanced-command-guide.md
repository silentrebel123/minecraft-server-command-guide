# Advanced Command Guide

Complete reference for all player commands organized by plugin.

[← Back to Home](./)

---

## Help

| Command | Description |
|---------|-------------|
| `/help` | Opens the help menu for the server |
| `/helpop` | Sends a message to admin chat, use it to ask for help or make a request to staff |

## ArmorStandEditor

| Command | Description |
|---------|-------------|
| `/ase` | Open the armor stand editing menu (sneak + right-click an armor stand to edit it) |

## AxGraves

| Command | Description |
|---------|-------------|
| `/axgraves list` | Lists your current axgraves if you have any |

## AxTrade

| Command | Description |
|---------|-------------|
| `/axtrade help` | List commands |
| `/axtrade <player>` or `/trade <player>` | Send a trade request to another player |
| `/axtrade accept <player>` | Accept a trade request |
| `/axtrade deny <player>` | Deny a trade request |
| `/axtrade toggle` | Toggle trade requests |

## BannerMaker

| Command | Description |
|---------|-------------|
| `/bm` | Open the banner maker GUI |
| `/bm help` | Display command list |
| `/bm hand` | View banner info of the banner in your hand |
| `/bm see` | View banner info of the banner you're looking at |

## CarbonChat

| Command | Description |
|---------|-------------|
| `/globalchat` | Switch to the global channel (cross server chat) |
| `/localchat` | Switch to the local channel (only sends message on the current server) |

## ChestSort

| Command | Description |
|---------|-------------|
| `/sort` or `/chestsort` | Toggle your sorting settings using a 100% customizable GUI |
| `/sort on\|off\|toggle` or `/chestsort on\|off\|toggle` | Enable/disable automatic chest sorting |
| `/sort hotkeys` or `/chestsort hotkeys` | Open the hotkeys GUI to enable/disable hotkeys per player |
| `/sort help` or `/chestsort help` | Display help about the `/sort` command |
| `/invsort` or `/isort` | Sort the player's inventory |
| `/invsort hotbar` or `/isort hotbar` | Sort the player's hotbar |
| `/invsort all` or `/isort all` | Sort the player's inventory and hotbar |
| `/invsort toggle` or `/isort toggle` | Toggle automatic inventory sorting |
| `/invsort on\|off` or `/isort on\|off` | Enable/disable automatic inventory sorting |
| `/invsort help` or `/isort help` | Display help about the `/invsort` command |

## CraftBook5

CraftBook5 adds various mechanics that enhance gameplay. Everything except custom AI is enabled on the survival/creative server.

### Available Mechanics

- **Elevators** - Jump between floors quickly using signs
- **Chairs** - Sit on stairs and slabs
- **Better Physics** - Enhanced physics interactions for items and blocks
- **Better Plants** - Plants grow and spread more naturally
- **Better Sponge** - Sponges act as water force fields in a spherical radius
- **Snow** - Realistic snow dispersion and enhanced snow mechanics
- **Bridges** - Toggle-able bridges with redstone
- **Gates** - Toggle-able fence gates with redstone
- **Doors** - Enhanced door mechanics with redstone
- **Minecarts** - Overhauled minecart system with boosters and more

### Commands

| Command | Description |
|---------|-------------|
| `/cb mech list` | View and toggle mechanics (click entries to enable/disable) |

For full documentation, visit: https://craftbook.enginehub.org/en/5.0.0/mechanics/

## DeluxeMenus

| Command | Description |
|---------|-------------|
| `/dm open <menu name>` | Manually open any specific menu by name |

## Drop2InventoryPlus

| Command | Description |
|---------|-------------|
| `/drop2inv` or `/drop2inventory` | Toggles automatic drop collection per player |

## EliteMobs

| Command | Description |
|---------|-------------|
| `/em` | Opens the EliteMobs menu |
| `/ag` | Teleport to the Adventurer's Guild |
| `/elitemobs language <language>` | Change your language settings |

## Essentials

### Home Commands

| Command | Description |
|---------|-------------|
| `/home` | Teleport to your home |
| `/home <name>` | Teleport to a named home |
| `/sethome` | Set your home at current location |
| `/sethome <name>` | Set a named home |
| `/delhome <name>` | Delete a home |
| `/homes` | List all your homes |

### Teleport Requests

| Command | Description |
|---------|-------------|
| `/tpa <player>` | Request to teleport to a player |
| `/tpahere <player>` | Request a player to teleport to you |
| `/tpaccept` | Accept a teleport request |
| `/tpdeny` | Deny a teleport request |
| `/tpacancel` | Cancel your outgoing teleport request |
| `/tptoggle` | Toggle whether you receive teleport requests |

### Navigation

| Command | Description |
|---------|-------------|
| `/back` | Return to your previous location (after teleport or death) |
| `/spawn` | Teleport to spawn |
| `/warp` | List available warps |
| `/warp <name>` | Teleport to a warp point |

### Communication

| Command | Description |
|---------|-------------|
| `/msg <player> <message>` | Send a private message |
| `/r <message>` | Reply to the last private message |
| `/mail` | Read your mail |
| `/mail send <player> <message>` | Send mail to a player |
| `/mail clear` | Clear your mail |
| `/me <action>` | Display an action message |
| `/ignore <player>` | Ignore a player's messages |

### Economy

| Command | Description |
|---------|-------------|
| `/balance` or `/bal` | Check your balance |
| `/balancetop` or `/baltop` | View richest players |
| `/pay <player> <amount>` | Pay another player |
| `/sell hand` | Sell the item in your hand |
| `/sell all` | Sell all sellable items in your inventory |

### Utilities

| Command | Description |
|---------|-------------|
| `/afk` | Toggle AFK status |
| `/afk <message>` | Set AFK with a message |
| `/compass` | Describe your current bearing |
| `/depth` | Show your current depth relative to sea level |
| `/getpos` | Get your current coordinates |
| `/itemdb` | Show information about the item in hand |
| `/kit` | View available kits |
| `/kit <name>` | Obtain a kit |
| `/list` | List online players |
| `/motd` | View the message of the day |
| `/near` | List nearby players |
| `/nick <name>` | Change your nickname |
| `/ping` | Check your connection |
| `/realname <nickname>` | Show the real name behind a nickname |
| `/rules` | View server rules |
| `/seen <player>` | Check when a player was last online |
| `/time` | Display the current in-game time |
| `/worth` or `/price` | Check the value of an item |

### Signs (Interact by right-clicking)

| Sign | Description |
|------|-------------|
| `[Buy]` signs | Purchase items |
| `[Sell]` signs | Sell items |
| `[Trade]` signs | Trade items |
| `[Free]` signs | Get free items |
| `[Disposal]` signs | Dispose of items |
| `[Heal]` signs | Heal yourself |
| `[Warp]` signs | Warp to locations |

## EvenMoreFish

| Command | Description |
|---------|-------------|
| `/emf gui` | Open the fishing GUI menu |
| `/emf top` | View the current fishing competition leaderboard |
| `/emf toggle` | Toggle fishing notifications |
| `/emf shop` | Open the fish shop |
| `/emf journal` | Open your fish journal to track caught fish |
| `/emf applybaits` | Open the GUI for applying baits to your fishing rod |

## ExcellentEnchants

| Command | Description |
|---------|-------------|
| `/eenchants` or `/excellentenchants` | Display plugin help |
| `/eenchants list` | Open a GUI displaying all custom enchantments |

## FastAsyncWorldEdit (Creative Server)

### Selection & Wand

| Command | Description |
|---------|-------------|
| `//wand` | Get the selection wand (wooden axe). Left-click for pos1, right-click for pos2 |
| `//pos1` | Set position 1 to your current location |
| `//pos2` | Set position 2 to your current location |
| `//sel` | Choose selection mode (cuboid, poly, sphere, etc.) |
| `//desel` or `//deselect` | Clear your selection |
| `//expand <amount> [direction]` | Expand selection |
| `//contract <amount> [direction]` | Contract selection |
| `//shift <amount> [direction]` | Shift selection |
| `//size` | Get selection size info |
| `//count <block>` | Count blocks in selection |

### Clipboard Operations

| Command | Description |
|---------|-------------|
| `//copy` | Copy selection to clipboard |
| `//copy -e` | Copy including entities |
| `//cut` | Cut selection to clipboard |
| `//paste` | Paste clipboard contents |
| `//paste -a` | Paste without air blocks |
| `//paste -o` | Paste at original position |
| `//rotate <angle>` | Rotate clipboard (90, 180, 270) |
| `//flip <direction>` | Flip clipboard (n/s/e/w/u/d) |

### Block Operations

| Command | Description |
|---------|-------------|
| `//set <block>` | Set all blocks in selection |
| `//replace <from> <to>` | Replace blocks in selection |
| `//replace <to>` | Replace non-air blocks with specified block |
| `//walls <block>` | Build walls around selection |
| `//faces <block>` | Build walls, ceiling, and floor |
| `//overlay <block>` | Overlay blocks on top of terrain |
| `//naturalize` | Add grass, dirt layers to terrain |
| `//smooth [iterations]` | Smooth terrain |

### Generation

| Command | Description |
|---------|-------------|
| `//hcyl <block> <radius> [height]` | Generate hollow cylinder |
| `//cyl <block> <radius> [height]` | Generate filled cylinder |
| `//hsphere <block> <radius>` | Generate hollow sphere |
| `//sphere <block> <radius>` | Generate filled sphere |
| `//pyramid <block> <size>` | Generate pyramid |
| `//hpyramid <block> <size>` | Generate hollow pyramid |

### History

| Command | Description |
|---------|-------------|
| `//undo [count]` | Undo operations |
| `//redo [count]` | Redo operations |
| `/clearhistory` | Clear your history |

### Schematics

| Command | Description |
|---------|-------------|
| `//schematic save <name>` | Save selection as schematic |
| `//schematic load <name>` | Load a schematic |
| `//schematic list` | List available schematics |
| `//schematic delete <name>` | Delete a schematic |

### Brushes

| Command | Description |
|---------|-------------|
| `/br sphere <block> <radius>` | Sphere brush |
| `/br cyl <block> <radius>` | Cylinder brush |
| `/br smooth [radius]` | Smooth brush |
| `/br gravity` | Gravity brush (makes blocks fall) |
| `/br butcher` | Kill mobs brush |

### Tools

| Command | Description |
|---------|-------------|
| `/tool none` | Unbind current tool |
| `/tool info` | Block info tool |
| `/tool tree <type>` | Tree generation tool |
| `/tool repl <block>` | Block replacer tool |
| `/tool farwand` | Long-range selection wand |

### Navigation

| Command | Description |
|---------|-------------|
| `/jumpto` | Teleport to where you're looking |
| `/thru` | Pass through walls |
| `/ascend` | Go up one floor |
| `/descend` | Go down one floor |
| `/ceil` | Go to ceiling |
| `/up <distance>` | Go up with a platform |
| `/unstuck` | Escape from being stuck |

### Masks & Patterns

| Command | Description |
|---------|-------------|
| `//gmask <mask>` | Set a global mask |
| `//mask <mask>` | Set a brush mask |

## Jobs

| Command | Description |
|---------|-------------|
| `/jobs browse` | Displays information about the given job |
| `/jobs info <job name>` | Displays information about the given job |
| `/jobs info <job name> 2` | Displays information about the given job from page 2 |
| `/jobs info <job name> place` | Displays information about the given job with the specified action type |
| `/jobs join <job name>` | Joins to the given job |
| `/jobs leave <job name>` | Leaves the specified job |
| `/jobs leaveall` | Leaves all the jobs |
| `/jobs quests` | Displays the available quests for the player |
| `/jobs stats` | Prints the player's job statistics |

## JustHorse (Creative Server)

| Command | Description |
|---------|-------------|
| `/horse` | Spawn a horse that you can use, open inventory while riding to customize the horse |

## Lands

### Basic Commands

| Command | Description |
|---------|-------------|
| `/lands` | Opens the Lands GUI menu |
| `/lands help [page]` | Display all Lands commands |
| `/lands create <name>` | Create a new land |
| `/lands rename <name>` | Rename your land |
| `/lands delete` | Delete your land |
| `/lands menu` | Open the GUI menu |

### Claiming

| Command | Description |
|---------|-------------|
| `/lands claim` | Claim the chunk you're standing in |
| `/lands claim auto` | Automatically claim chunks as you walk |
| `/lands unclaim` | Unclaim the chunk you're standing in |
| `/lands unclaim auto` | Automatically unclaim chunks as you walk |
| `/lands selection` | Enter selection mode for claiming multiple chunks |

### Map & Info

| Command | Description |
|---------|-------------|
| `/lands map` | View a map of claimed chunks around you |
| `/lands map chat` | View the map in chat instead of GUI |
| `/lands info` | View information about the land you're standing in |
| `/lands player <player>` | View information about a player |
| `/lands list` | View all lands on the server |

### Teleportation

| Command | Description |
|---------|-------------|
| `/lands spawn [land]` | Teleport to a land's spawn |
| `/lands setspawn` | Set the spawn for your land |

### Trusting Players

| Command | Description |
|---------|-------------|
| `/lands trust <player>` | Trust a player in your land |
| `/lands untrust <player>` | Remove a player from your land |
| `/lands setrole <player> <area\|*> <role>` | Set a player's role |
| `/lands setowner <player>` | Transfer ownership to another player |

### Banning

| Command | Description |
|---------|-------------|
| `/lands ban <player>` | Ban a player from your land |
| `/lands unban <player>` | Unban a player from your land |

### Invitations

| Command | Description |
|---------|-------------|
| `/lands accept <land>` | Accept an invitation |
| `/lands deny <land>` | Deny an invitation |
| `/lands leave` | Leave a land you're a member of |

### Flags & Settings

| Command | Description |
|---------|-------------|
| `/lands flags` | Open the flags menu |
| `/lands balance` | View your land's bank balance |
| `/lands deposit <amount>` | Deposit money into land bank |
| `/lands withdraw <amount>` | Withdraw money from land bank |
| `/lands taxes` | View tax information |
| `/lands rent` | View and manage rentable areas |
| `/lands level` | View your land's level progress |
| `/lands top` | View the top lands |

### Relations

| Command | Description |
|---------|-------------|
| `/lands relations` | View land relations |
| `/lands chat [land] <message>` | Send a message to land members |

### Nations

| Command | Description |
|---------|-------------|
| `/nations create <name>` | Create a nation |
| `/nations chat [nation] <message>` | Send a message to nation members |
| `/nations info [nation]` | View nation information |
| `/nations level` | View nation level progress |

### Wars

| Command | Description |
|---------|-------------|
| `/wars menu` | Open the war menu |
| `/wars declare <land\|nation>` | Declare war |

## LotterySix

| Command | Description |
|---------|-------------|
| `/lotterysix play` | Open the lottery GUI |

## mcMMO

### General Commands

| Command | Description |
|---------|-------------|
| `/mcmmo help` | Display all mcMMO commands |
| `/mcstats` | View your skill levels and XP progress |
| `/mctop` | View the top players by power level |
| `/mctop <skill>` | View leaderboard for a specific skill |
| `/mctop <skill> <page>` | View specific page of skill leaderboard |
| `/mcrank` | View your skill rankings |
| `/mcrank <player>` | View another player's rankings |

### Ability & Settings

| Command | Description |
|---------|-------------|
| `/mcability` | Toggle ability activation (right-click abilities) |
| `/mcnotify` | Toggle mcMMO notifications |
| `/mcscoreboard` | Toggle the mcMMO scoreboard |
| `/mccooldown` | View your ability cooldowns |

### Skill Commands

| Command | Description |
|---------|-------------|
| `/<skill>` | View information about a skill (e.g., `/mining`, `/woodcutting`) |
| `/<skill> ?` | Get detailed help about a skill |

**Available Skills:**

| Command | Description |
|---------|-------------|
| `/acrobatics` | Dodge, roll, and graceful roll info |
| `/alchemy` | Potion brewing info |
| `/archery` | Arrow skills and daze info |
| `/axes` | Axe combat abilities info |
| `/excavation` | Digging treasures info |
| `/fishing` | Fishing treasures and shake info |
| `/herbalism` | Plant gathering abilities info |
| `/mining` | Mining abilities and super breaker info |
| `/repair` | Item repair info |
| `/salvage` | Item salvaging info |
| `/smelting` | Furnace efficiency info |
| `/swords` | Sword combat abilities info |
| `/taming` | Wolf/pet abilities info |
| `/unarmed` | Fist fighting abilities info |
| `/woodcutting` | Tree felling abilities info |

### Party Commands

| Command | Description |
|---------|-------------|
| `/party` | View party information |
| `/party help` | Display party commands |
| `/party create <name> [password]` | Create a party |
| `/party join <player> [password]` | Join a player's party |
| `/party invite <player>` | Invite a player to your party |
| `/party accept <player>` | Accept a party invitation |
| `/party disband` | Disband your party (leader only) |
| `/party leave` | Leave your current party |
| `/party kick <player>` | Kick a player from the party |
| `/party leader <player>` | Transfer party leadership |
| `/party password <password>` | Set party password |
| `/party lock` | Lock party to invites only |
| `/party unlock` | Allow anyone to join |
| `/party chat` or `/pc` | Toggle party chat mode |
| `/party chat <message>` | Send a party message |

### Party Sharing

| Command | Description |
|---------|-------------|
| `/party itemshare` | Toggle item sharing |
| `/party itemshare equal` | Share items equally |
| `/party itemshare random` | Share items randomly |
| `/party itemshare none` | Disable item sharing |
| `/party xpshare equal` | Share XP equally |
| `/party xpshare none` | Disable XP sharing |

### Party Teleport

| Command | Description |
|---------|-------------|
| `/ptp <player>` | Teleport to a party member |
| `/ptp accept` | Accept a party teleport request |
| `/ptp deny` | Deny a party teleport request |
| `/ptp toggle` | Toggle party teleport requests |

## PlayerParticles (Creative Server)

| Command | Description |
|---------|-------------|
| `/pp` | Open player particles menu |

## PlotSquared (Creative Server)

### Claiming Plots

| Command | Description |
|---------|-------------|
| `/plot claim` or `/p claim` | Claim the plot you're standing on |
| `/plot auto` or `/p auto` | Automatically claim the nearest unclaimed plot |
| `/plot delete` or `/p delete` | Delete your plot (unclaim and clear) |

### Plot Info

| Command | Description |
|---------|-------------|
| `/plot info` or `/p info` | View information about the current plot |
| `/plot list mine` | List all your owned plots |
| `/plot list shared` | List plots shared with you |

### Teleportation

| Command | Description |
|---------|-------------|
| `/plot home` or `/p home` | Teleport to your plot |
| `/plot home <number>` | Teleport to a specific plot |
| `/plot visit <player>` or `/p visit <player>` | Visit another player's plot |
| `/plot middle` or `/p middle` | Teleport to the center of your plot |
| `/plot sethome` | Set the teleport point for your plot |

### Player Trust

| Command | Description |
|---------|-------------|
| `/plot add <player>` | Add a player as a member (can build while you're online) |
| `/plot trust <player>` | Trust a player (can build anytime + use WorldEdit) |
| `/plot deny <player>` | Deny a player from entering your plot |
| `/plot remove <player>` | Remove a player from your plot |
| `/plot kick <player>` | Kick a player from your plot |

### Plot Merging

| Command | Description |
|---------|-------------|
| `/plot merge` | Merge with adjacent plot(s) |
| `/plot merge all` | Merge with all connected plots you own |
| `/plot unlink` | Unlink (unmerge) plots |

### Plot Settings

| Command | Description |
|---------|-------------|
| `/plot toggle <setting>` | Toggle plot settings |
| `/plot flag set <flag> <value>` | Set plot flags |
| `/plot flag remove <flag>` | Remove a plot flag |
| `/plot flag list` | List available flags |
| `/plot setbiome <biome>` | Set the plot biome |
| `/plot setdescription <text>` | Set plot description |

### Plot Clearing & Maintenance

| Command | Description |
|---------|-------------|
| `/plot clear` | Clear your plot to default state |
| `/plot set <component> <block>` | Set plot components (floor, wall, border, etc.) |
| `/plot music <song>` | Set plot background music |

### Ratings & Comments

| Command | Description |
|---------|-------------|
| `/plot like` | Like a plot |
| `/plot dislike` | Dislike a plot |
| `/plot rate <1-10>` | Rate a plot |
| `/plot comment <message>` | Leave a comment on a plot |
| `/plot inbox` | View plot comments |

## Quests

| Command | Description |
|---------|-------------|
| `/quests` | Display plugin help |
| `/quests list <page>` | List available quests |
| `/quests take <quest>` | Accept a quest via command |
| `/quests quit <quest>` | Quit a current quest |
| `/quests stats` | View quest statistics |
| `/quests top <number>` | View plugin leaderboards |
| `/quests info` | View plugin information |
| `/quests journal` | Toggle the Quest Journal |
| `/quest` | View current quest objectives |
| `/quest <quest>` | View information about a quest |

## QuickShop (Player Shops)

### Creating Shops

To create a shop: Place a chest, then while holding the item you want to sell, hit the chest with it. Follow the prompts to set the price.

| Command | Description |
|---------|-------------|
| `/qs create <price>` | Create a shop on a chest you're looking at |
| `/qs buy` | Change your shop to buying mode |
| `/qs sell` | Change your shop to selling mode |

### Managing Shops

| Command | Description |
|---------|-------------|
| `/qs price <price>` | Change shop price (supports abbreviations like 2.5k) |
| `/qs find <item>` | Find the nearest shop selling an item |
| `/qs fetchmessage` | Fetch shop transaction messages |
| `/qs staff add <player>` | Add a staff member to your shop |
| `/qs staff remove <player>` | Remove a staff member from your shop |
| `/qs staff list` | List shop staff |
| `/qs setowner <player>` | Transfer shop ownership |
| `/qs unlimited` | Toggle unlimited stock mode |
| `/qs remove` | Remove a shop |
| `/qs size` | Change bulk purchase size |
| `/qs currency <currency>` | Set shop currency |

### Shop Info

| Command | Description |
|---------|-------------|
| `/qs info` | View shop information |
| `/qs preview` | Preview shop contents |

## SilkSpawners

| Command | Description |
|---------|-------------|
| `/ss help` | Display help menu |
| `/ss list` or `/ss all` | Display all available creature types |
| `/ss view` | Display information about a spawner you're looking at |

## TAB

| Command | Description |
|---------|-------------|
| `/tab scoreboard` | Toggle the scoreboard visibility |

## UltraCosmetics (Creative Server)

| Command | Description |
|---------|-------------|
| `/uc` | Open cosmetics menu |
| `/uc menu` | Open cosmetics menu |
| `/uc clear` | Clears all your cosmetics |
| `/uc gadgets` | Toggle gadgets |
| `/uc selfview` | Toggle self view for morphs |

## Voicechat

| Command | Description |
|---------|-------------|
| `/voicechat` | Open voice chat settings |
