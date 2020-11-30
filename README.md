# Dogpit
The Dogpit Minecraft server is a private Spigot server for the Dogpit Discord channel. It's essentially Vanilla minecraft with some extra bells and whistles attached. You **do not** need a special client to connect to Dogpit.

This document lists all installed plugins on the server, along with usage instructions from a player's perspective.

## Non-Plugin Notes and Modifications
- **Cats** (not ocelots), **wolves** (both wild and tame), and **parrots** are ***INVULNERABLE** on this server.
- There is a **community storage** center in the building at spawn where you can donate resources to other players.
- The **Dogpit Teleport Network** (DTN) central hub is located adjacent to spawn. You can use the booths there to travel to far away places.
- All players get a free **elytra** automatically, and more can be found in community storage.
- When a player **dies**, they do **not** lose items or experience. Take risks!

## Installed Plugins
A brief list of all currently installed plugins, and a link to their Spigot/Bukkit page, as well as a ⏬ quick link to their respective sections in this document.

- [OneStopShop](https://www.spigotmc.org/resources/onestopshop-free-gui-item-shop.76640/) [⏬](#onestopshop)
- [Dynmap](https://www.spigotmc.org/resources/dynmap.274/) [⏬](#dynmap)
- [Essentials X](https://www.spigotmc.org/resources/essentialsx.9089/) [⏬](#essentials-x)
- [mcMMO](https://www.spigotmc.org/resources/official-mcmmo-original-author-returns.64348/) [⏬](#mcmmo)
- [Minepacks](https://www.spigotmc.org/resources/minepacks-backpack-plugin-mc-1-7-1-15.19286/) [⏬](#minepacks)
- [No Mob Griefing](https://dev.bukkit.org/projects/no-mob-griefing) [⏬](#no-mob-griefing)
- [Voteday](https://www.spigotmc.org/resources/voteday.77077/) [⏬](#voteday)


## Dynmap
[http://dogpitmcmap.xezton.com:8123](http://dogpitmcmap.xezton.com:8123)

Generates a *GoogleMaps-esque* map of all server worlds at the link above.

You can also **chat** directly from the map using the chatbox on the bottom of the page *(assuming you've logged into the server recently)*.

You can share a specific location by clicking the **link** button on the bottom left.

The map updates constantly, but don't expect your exploratory boat excursions to be reflected on the map very quickly. It can take minutes to hours for changes and new chunks to appear on the map.

#### Adding Markers to the Map
You can now add markers to the map! To do so, just stand where you want the marker to show up on the map, and type `/dmarker add MarkerNameHere icon:icon_name`. Replace "MarkerNameHere" with whatever you want the marker to be called, and replace icon_name with one of the icons in the image below, making sure to **remove spaces** from the name if it has any.

If you need to **remove a marker** contact an op!

![alt text](https://rlseaton.github.io/superdogpit/images/dynmap-marker-icons.png "Dynmap Marker Icons")


## OneStopShop
This plugin adds a GUI to your shopping experience! It uses the same money and prices as the Essentials X plugin below, but makes it a little easier to buy and sell things. *Note: There are some items you can sell in the shop, but not through the sell command.*

To access the shop, use the command `/shop`.

This will bring up the shop and show you all available categories:

![alt text](https://rlseaton.github.io/superdogpit/images/shop.png "Shop Interface")

Once you've clicked an individual item, you can **buy** it in quantities of 1, 8, or 64 by clicking the **green boxes** next to it.

You can **sell** that item (if you have any) by clicking the **red boxes**.

You can also buy enough of that item to fill your inventory, or sell all items in your inventory, with the inventory buttons.

If something is missing from the shop, contact an op and we'll see about adding it!


## Essentials X

This plugin adds more features than would fit in the scope of this document.

The main things you'll probably use it for are **money**, **trading**, and interacting with op-provided **sign shops**.

You can see how much money you have with the `/money` or `/balance` commands.

**Send** other players money directly with `/pay PlayerName amount`.

You can also **sell** items to the server for money! The easiest way is to hold the item in your hand and run `/sell hand amount`. You can see how much the thing in your hand is worth by running `/worth hand`.
*Note that not all items can be sold, but most can!*


The other interesting thing you an do with this plugin is create **Trade Signs**. You can put these anywhere you want and people can trade items with you by interacting with the sign.

First create a sign. Fill out the four lines like this:
1. `[Trade]`
2. What you are **asking** for in the format of money `$200` or a quantity of items `10 dirt`.
3. What you are **giving** in the format of money `$200` or a quantity of items along with the total number loaded into the sign `10 dirt:100`.
4. Leave this line *blank*. This will fill itself in with the name of the player who made the sign.

So for example, if you made a sign that looked like this:
```
[Trade]
$5
10 dirt:100

```
...the game would take 100 dirt from your inventory (assuming you have it) and load it into the sign.
Then, when anyone else (besides you) right clicks the sign, they will pay $5 and get 10 dirt, and the total dirt in the sign will be decreased by 10 until it's empty.

You can **restock** the sign by holding the item you're trading in your hand and right-clicking the sign.

You can **collect** the items/money stored in the sign by right clicking it with an empty hand.

If you don't know the **name of the item** you should use, hold the item in your hand and type the `/itemdb` command. It will provide a list of possible names that you can type into the sign.

Similarly, you might find `[Buy]` and `[Sell]` signs scattered around. These are created by ops, and their function is pretty self explanatory. 

If you see a `[Buy]` sign with something you'd like to buy, right-click it and, assuming you have the cost (4th line) it'll buy the item in the amount specified on the 2nd line. 

`[Sell]` signs will take your items and give you the item/money listed on the 4th line.

You can also **send players offline messages** by using the `/mail` command.

For example, `send PlayerName Hey how are you?`.

You will be notified if you have new mail, and can read it with `/mail read`.

Once you've read your mail, you can use `/mail clear` to empty your mailbox.

Lastly, there are a couple of **convenient warp commands** available to you: `/home` and `/spawn`. Home will take you to your bed, spawn will take you to spawn.


## mcMMO
This is *by far* the biggest and most game-changing plugin installed on this server. 

mcMMO adds skills and abilities, as well as a leveling system, for pretty much *everything* in the game, including fighting, mining, woodcutting, taming, jumping, making potions, and more.

As soon as you start doing... well almost anything, you'll begin leveling up. Over time you'll start to gain skills and abilities (both passive and active). You can right-click while holding a tool, for example, to activate its super ability.

You can type `/mcmmo help` for a list of commands.

To check on your skills, you can use skill name commands such as `/mining`, `fishing`, `/axes`, etc. to check you abilities, or you can just type `/mcstats` for an overview of each skill, including your level and how much XP you need to level up.

The plugin makes itself pretty obvious, so I won't go into much more detail here.

You should really give their wiki a look if you'd like to learn everything you can do with mcMMO! [https://mcmmo.org/wiki/Main_Page](https://mcmmo.org/wiki/Main_Page)

Or, if the information on the *official* wiki is lacking, you can try the community-driven wiki! [https://mcmmo.fandom.com/wiki/McMMO_Wiki](https://mcmmo.fandom.com/wiki/McMMO_Wiki)


## Minepacks
This one is simple and straightforward. **Everyone** gets an item called `Backpack`. If you use (right-click while holding) the Backpack, it'll open up what essentially amounts to a *portable **double-chest***.

Basically your inventory has more than doubled. Better yet, you'll never lose anything you put in there!

**If you ever (somehow) lose your Backpack item**, you can still access it via the `/backpack` command. Contact an op and they can give you a new Backpack item.


## No Mob Griefing
Players don't need to do anything with this plugin, but they will certainly see its effects.

With it, **creeper explosions** no longer destroy blocks (but they still damage players), **endermen** no longer steal blocks, and **ghast and wither fireballs** no longer destroy blocks (but they still damage players).

So basically you no longer need to worry about mobs destroying your wonderful creations! But don't let your guard down, because they certainly can still hurt *you*!


## Voteday
It's night, dozens of monsters are around, there's no op online, and no one is anywhere near their beds, but **everyone really wishes it could just be daytime already**!!!

Have no fear! Simply type `/voteday` and it will start a server-wide vote. If enough other players (ignoring AFK players) type `/voteday confirm`, it will magically become daytime!

It's that simple! You can read more by typing `/voteday help`.
