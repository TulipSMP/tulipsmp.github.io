# Commands

- [Back](/docs)

> **Tip!** Command options marked like `[this]` are required, ones marked with `<these>` are optional. 

### Contents

- [For Players](#for-players)
- [For Jr. Moderators](#for-jr-moderators)
- [For Moderators](#for-moderators)
- [For Administrators](#for-administrators)


## For Players

Commands players and above can use.

(Almost) all commands you can use ingame are listed here.

#### /art

- `/art`

Open a UI for [ArtMap](/docs/artmap).

#### /artmap

*Alias for [/art](#art).*

#### /msgtoggle

- `/msgtoggle`

Toggles whether you can recieve private messages via [/msg](#msg)

#### /help

- `/help`

Get info on using different commands.


#### /tptoggle

- `/tptoggle`

Toggles whether you can use teleportation related commands.

> Moderators can still teleport you or teleport to you.

#### /disposal

- `/disposal`

Opens a trash can to put items in, which will be deleted.

#### /trash

*Alias for [/disposal](#disposal).*

#### /condense

- `/condense`

Compresses what you are holding into more compact blocks.

#### /mail

- `/mail read`
- `/mail clear <number>`
- `/mail send [to] [message]`
- `/mail sendtemp [to] [message] [expire time]`

Send, read, or clear mail. Players are also alerted of mail they recieve when they join.

> Moderators can toggle whether they are watching players' mail with [/socialspy](#socialspy).


#### /hat

- `/hat`

Puts the item you are holding in your helmet slot.

#### /info

- `/info`

See information about the server and links to resources.

#### /realname

- `/realname [player]`

Check the real username of a player (useful if they have a nickname you do not recognize).

#### /rules

- `/rules`

View server rules. This list may be outdated, always check discord for the latest iteration.

#### /warpinfo

- `/warpinfo [warp]`

View informations about a [warp](#warp).

#### /warp

- `/warp [name]`

Warp to a set location. You can view information about these locations with [/warpinfo](#warpinfo).

> Moderators and above can set warps with [/setwarp]
(#setwarp).

#### /compass

- `/compass`

Describes your current bearing.

#### /me

- `/me [message]`

Send a message in chat starting with "* YourUserName".

#### /payconfirmtoggle

- `/payconfirmtoggle`

Toggle whether you need to confirm before making payments with <a href="#pay">/pay</a>.

#### /list

- `/list`

See who else is online.

#### /ignore

- `/ignore`

Effectively blocks another user ingame. 

> *If you ever need to use this, there is probably something very wrong. Please open a Ticket and speak to the Moderators if you need to use this. It is only provided as an emergency safeguard.*

#### /near

- `/near`

See who's near you ingame.

#### /nearby

*Alias for [/near](#near).*

#### /workbench

- `/workbench`

Opens a crafting table.

#### /stonecutter

- `/stonecutter`

Opens a stonecutter.

#### /enderchest

#### /motd

- `/motd`

Views the MOTD shown when you join the server.

#### /back

- `/back`

Teleport to your previous location.

#### /return

*Alias for [/back](#back).#

#### /seen

- `/seen [player]`

Shows the last logout time of a player.

#### /home

- `/home`

Teleport to your bed.

#### /getpos

- `/getpos`

Get your current position.

#### /helpop

- `/helpop [message]`

Sends a message to all online Moderators.

#### /skull

- `/skull <owner>`

Get the player head of you, or that of another `<owner>`.

#### /head

*Alias for [/skull](#skull).*

#### /heads

- `/heads`

Opens a UI to get various player heads.

> *Not to be confused with [/head](#head)!*

#### /itemlore

- `/itemlore [add|set|clear] <text|line> <text>`

Adds lore to an item.

Examples:

  - `/itemlore clear`: Clears your item's itemlore.
  - `/itemlore add Hello World!`: Adds "Hello World!" to the itemlore.
  - `/itemlore set 3 Sussus Amongus`: Sets the third line of itemlore to "Sussus Amongus".

#### /ilore

*Alias for [/itemlore](#itemlore).*

#### /itemname

- `/itemname <name>`

Rename an item, or omit `<name>` to clear the name.

#### /iname

*Alias for [/itemname](#itemname).*

#### /afk

- `/afk`

Marks you as away from keyboard.

#### /away

*Alias for [/afk](#afk).*

#### /nick

- `/nick [name|off]`

Set your nickname or turn it off.

> Moderators can use the following to change or reset a player's username:
> - `/nick [player] [name|off]`

#### /r

- `/r [message]`

Quick reply to the last player to message you.

#### /reply

*Alias for [/r](#r).*

#### /rtoggle

- `/rtoggle`

Change whether the recipient of replies in [/r](#r) is the last recipient or last sender.

#### /showkit

- `/showkit [kit name]`

Show contents of a kit.

#### /playtime

- `/playtime [player]`

Shows your or a `[player]`'s ingame playtime.

#### /spawn

- `/spawn`

Teleport to world spawn.

#### /msg

- `/msg [player] [message]`

Send a private `[message]` to a `[player]`.

#### /recipe

- `/recipe <item>`

View how to craft an item.

#### /blockprot

See [Block Protection](/docs/blockprot).

#### /tags

- `/tags`

Opens the [Tags Menu](/docs/tags)

#### /tag

*Alias for [/tags](#tags).*

#### /sit

- `/sit`

Sit down.

#### /crawl

- `/crawl`

Crawl.

#### /lay

- `/lay`

Lay down.

#### /bellyflop

- `/bellyflop`

Do a belly flop.

#### /spin

- `/spin`

Spin around.

#### /dc

- `/dc list`

List your death chests

- `/dc remove`

Remove all your death chests

#### /quickshop

- `/quickshop`

Manage your Chest Shop

<!--- [21:40:37 INFO]: QuickShop help
[21:40:37 INFO]: /qs about - Shows QuickShop info
[21:40:37 INFO]: /qs amount - To set the amount of items (Useful when having chat issues)
[21:40:37 INFO]: /qs benefit - Settings of divide benefits between shop owner and other players
[21:40:37 INFO]: /qs buy - Changes a shop to BUY mode
[21:40:37 INFO]: /qs clean - Removes all (loaded) shops without any stock
[21:40:37 INFO]: /qs create - Creates a new shop from the targeted chest
[21:40:37 INFO]: /qs currency - Set or remove the currency setting of the shop
[21:40:37 INFO]: /qs database - View and maintain the QuickShop Database
[21:40:37 INFO]: /qs debug - Enables Developer mode
[21:40:37 INFO]: /qs empty - Removes all items from a shop
[21:40:37 INFO]: /qs fetchmessage - Show unread shop messages
[21:40:37 INFO]: /qs find - Locates the nearest shop of a specific type.
[21:40:37 INFO]: /qs help - Shows the QuickShop help
[21:40:37 INFO]: /qs info - Show QuickShop statistics
[21:40:37 INFO]: /qs item - Change shop item of a shop
[21:40:37 INFO]: /qs lookup - Manage lookup-able items table
[21:40:37 INFO]: /qs name - Changes the name of a specific shop
[21:40:37 INFO]: /qs paste - Uploads server data to Pastebin
[21:40:37 INFO]: /qs permission - Shop permission management
[21:40:37 INFO]: /qs price - Changes the buy/sell price of a shop
[21:40:37 INFO]: /qs purge - This feature is not enabled in the config file.
[21:40:37 INFO]: /qs refill - Adds a given number of items to a shop
[21:40:37 INFO]: /qs reload - Reloads the config.yml of QuickShop
[21:40:37 INFO]: /qs remove - Removes the shop you're looking at
[21:40:37 INFO]: /qs removeall - Remove ALL shops of a specified player
[21:40:37 INFO]: /qs removeworld - Remove ALL shops in a specified world
[21:40:37 INFO]: /qs sell - Changes a shop to SELL mode
[21:40:37 INFO]: /qs setowner - Changes the ownership of a shop.
[21:40:37 INFO]: /qs size - Change per-bulk amount of a shop
[21:40:37 INFO]: /qs staff - Manage your shop staff
[21:40:37 INFO]: /qs supercreate - Create a shop while bypassing all protection checks
[21:40:37 INFO]: /qs taxaccount - Set the tax account that the shop using
[21:40:37 INFO]: /qs toggledisplay - Toggle the shop's display-item status
[21:40:37 INFO]: /qs transfer - Transfer ALL shops of a player to someone else
[21:40:37 INFO]: /qs unlimited - Gives a shop unlimited stock --->

#### /qs

*Alias for [/quickshop](#quickshop).*

#### /shop

*Alias for [/quickshop](#quickshop).*

#### /bank

- `/bank [balance|baltop]`
- `/bank [deposit|withdraw] [amount|all]`
- `/bank [pay|transfer] <player> <amount>`

Manage your diamonds in the bank.

## For Jr. Moderators

Commands Jr. Moderators and above can use

#### /mute

- `/mute [player]`
- `/mute [player] <duration> <reason>`

Permanately mute a player, unmute a player, or temporarily mute a player for the specified `<duration>` with an optional `<reason>`.

#### /kickall

- `/kickall`

Kicks all players from the server.

#### /kick

- `/kick [player] <reason>`

Kick `[player]` with optional `<reason>`.

#### /jail

- `/jail [player] [jailname] <duration>`

Jail a player `[jailname]` indefinitely, or for optional `<duration>`.

#### /togglejail

*Alias for [/jail](#jail).*


#### /vanish

- `/vanish`

Toggle being invisible.

#### /tempban

- `/tempban [player] [duration] <reason>`

Temporarily ban `[player]` for `[duration]` with optional `<reason>`.

#### /socialspy

- `/socialspy`

Toggles social spy, which shows you all direct messages and other correspondence between players in the server.
 
## For Moderators

Commands Moderators and above can use

#### /whois

- `/whois [player]`

Gives basic information about a player.

#### /gamemode

- `/gamemode [survival|spectator]`

Change your gamemode.

#### /tp

- `/tp [player]`
- `/tp [player] [destination player]`

Teleport yourself to `[player]`, or teleport `[player]` to `[destination player]` .

#### /tpoffline

- `/tpoffline [player]`

Teleports you to where `[player]` logged out.

#### /book

- `/book`

Locks/Unlocks the book you are holding.

#### /tpaall

- `/tpaall`

Sends a teleport request to all players to teleport to you.

#### /world

- `/world`
- `/world [name]`

Teleports you between the overworld and nether, or into specified world `[name]`.

#### /ext

- `/ext`
- `/ext [player]`

Extinguish yourself, or the specified `[player]` if they are on fire.

#### /invsee

- `/invsee [player]`

View `[player]`'s inventory.

#### /banip

- `/banip [address] <reason>`

Ban the specified IP `[address]` with optional `<reason>`.

#### /jump

- `/jump`

Teleport yourself to the block you're looking at.

#### /broadcast

- `/broadcast [message]`

Sends a server-wide message.

#### /clearinventory

- `/clearinventory <player>`

Clears your inventory or that of the specified `<player>`.

#### /heal

- `/heal <player>`

Heals yourself or the specified `<player>`

#### /tempbanip

- `/tempbanip [player|address] [duration] <reason>`

Temporarily bans all connections from IP `[address]` or the IP of `[player]` for specified `[duration]`, with optional `<reason>`.

#### /tphere

- `/tphere [plaeyr]`

Teleports a player to yourself.

#### /tppos

- `/tppos [x] [y] [z] <yaw> <pitch> <world>`

Teleport to coordinates `[x] [y] [z]`, with optional `<yaw>` and `<pitch>`, into optional `<world>`.

#### /unban

- `/unban [player]`

Unbans the specified player.

#### /unbanip

- `/unbanip [address]`

Unbans the specified IP `[address]`.

#### /unjail

- `/unjail [player]`

Removes specified `[player]` from jail.


## For Administrators

Commands only Administrators can use

*Specifics for commands here are not listed,*

#### /spawnmob

Spawns a mob.

#### /lp

Manage permissions with LuckPerms.

#### /ess

Manage EssentialsX.

#### /delkit

Remove a kit.

#### /lag

Check server performance.

#### /loom

Open a loom/

#### /weather

Change the weather.

#### /essentials

*Alias for [/ess](#ess).*

#### /discordsrv

Manage DiscordSRV.

#### /exp

Manage Player Experience Points.

#### /sky

*Alias for [/weather](#weather).*

#### /rain

Change the weather to rain.

#### /give

Give items to yourself or others.

#### /item

*Alias for [/give](#give).*

#### /setjail

Create a jail.

#### /suicide

Kills yourself ingame.

#### /playerweather

Manage a player's percieved weather seperately from the server.

#### /tree

Creates a tree.

#### /setspawn

Sets the world spawn point

#### /grindstone

Opens a grindstone.


#### /bigtree

Creates a big tree.

#### /feed

Refills your or another player's hunger.

#### /tpall

Teleports everyone to you.

#### /discord

*Alias for [/discordsrv](#discordsrv).*

#### /stop

Stops the server.

#### /minecraft:gamemode

Use builtin gamemode command.

#### /repair

Restore an item's durability.

#### /anvil

Opens an anvil.

#### /ping

Pong!

#### /squaremap

Manage the [map](https://tulip.krafterdev.xyz).

#### /deljail

Remove a jail.

#### /sun

Set the weather to clear.

#### /kitreset

Resets the cooldown on a kit for you or another player.

#### /remove

Remove mobs by type, radius, and world.

#### /smithingtable

Opens a Smithing Table.

#### /mem

*Alias for [/lag](#lag).*

#### /top

Teleports you atop the highest block above you.

#### /playertime

Manages a player's time separate from the server's.

#### /settpr

Manage [/tpr](#tpr) settings.

#### /sudo

Execute a command as another player.

#### /gc

*Alias for [/lag](#lag).*

#### /ptime

*Alias for [/playertime](#playertime).*

#### /tpohere

Teleport player, overriding [/tptoggle](#tptoggle) prefrences.

#### /map

*Alias for [/squaremap](#squaremap).*

#### /rest

Resets time since player slept to 0.

#### /burn

Light someone on fire.

#### /op

All your base are belong to us.

#### /potion

Manage potion effects.

#### /storm

Set the weather to stormy.

#### /break

Break the block you are looking at.

#### /more

Refills what you are holding in your hand to a full stack.

#### /cartographytable

Opens a cartography table.

#### /unlimited

Allow unlimited placing of items.

#### /i

*Alias for [/give](#give).*

#### /pweather

*Alias for [/playerweather](#playerweather).*

#### /kill

Commit murder.

#### /itemdb

Shows information about the item you are holding.

#### /createkit

Create a kit.

#### /fly

Fly.

#### /tpo

Teleport, overriding [/tptoggle](#tptoggle) prefrences.

#### /depth

View your altitude in relation to sea level.

#### /cw

Manage the Command Whitelist.

#### /broadcastworld

Broadcast, but only to players in the specified world.

#### /enchant

Enchant the item you or another player are holding.

#### /xp

*Alias for [/exp](#exp).*

#### /time

Manage the time.

#### /hologram

Manage Holograms.

#### /setwarp

Set a warp at your current location.

> Players can teleport to these locations with [/warp](#warp).

#### /delwarp

Delete warps.

#### /dc

Manage DeadChests.