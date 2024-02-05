# Shops

- [Back](/docs)
- [Back to Commands](/docs/commands)

Chest shops are a quick and easy way to sell items for diamonds, even when you're not online to do the trading yourself.

##### Contents
- [Creating a Shop](#creating-a-shop)
- [Shop Permissions](#shop-permissions)


## Buying from a Shop

![gif of buying from a shop ingame](src/shop-buying.gif)

1. Punch the sign on the front of a shop
2. Information and instructions will appear in chat
3. Walk away to cancel, or enter how many you would like to buy in chat
4. Diamonds will first be deducted from your [Bank Account](banking), then from your inventory if there are not enough (the bank will not let you go into debt). 

## Creating a Shop

1. Place a chest where you want to have your shop
2. Hold the item you want to sell (if you want to sell multiple at once, hold that many in your hand)
3. Hit the front of the chest with your item, and instructions will appear in chat. Just enter how many diamonds it should cost per unit.
4. Now, anyone can purchase items from your shop by clicking on the sign on the front, and only for the price you specified. Restock by refilling the chest with more of the item you're selling.


## Shop Permissions

Use the following commands to add staff or change ownership of your shop. Make sure you're looking directly at the shop you wish to edit while performing the following commands.

- `/shop staff`: Manage staff members for your shop
- `/shop staff add <player>`: Add a player as a staff member 
- `/shop staff del <player>`: Remove a staff member
- `/shop staff clear`: Remove all staff members
- `/shop staff list`: List current staff members

<!-- -->
- `/shop setowner <player>`: Transfer ownership of your shop to another player


## Shop Settings

Use the following commands to change settings for your shop. Make sure you're looking directly at the shop you wish to edit while performing the following commands.

- `/shop [buy|sell]`: Switch your shop type between buying and selling
- `/shop price <price>`: Change the price per bulk of your shop
- `/shop size <price>`: Set how many items per bulk of your shop
- `/shop name <name>`: Set the name for your shop (leave `<name>` blank to reset)

## Other Commands

- `/shop info`: Show information about a shop you're looking at
- `/shop find <query>`: Find the nearby shops selling items that start with `<query>` (within 45 blocks)