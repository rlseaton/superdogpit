The Dogpit Discord now has two, count'em, *TWO*, Minecraft servers: **Dogpit** and **Dogpit: Unleashed**.

This document contains all the information you need to connect and play on either one!

Skip to [Dogpit](#dogpit)

Skip to [Dogpit: Unleashed](#dogpit-unleashed)

---
&nbsp;  
&nbsp;  

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

- [Dynmap](https://www.spigotmc.org/resources/dynmap.274/) [⏬](#dynmap)
- [Essentials X](https://www.spigotmc.org/resources/essentialsx.9089/) [⏬](#essentials-x)
- [Grappling Hook](https://www.spigotmc.org/resources/grappling-hook.70854/) [⏬](#grappling-hook)
- [Marriage Master](https://www.spigotmc.org/resources/marriage-master-mc-1-7-1-15.19273/) [⏬](#marriage-master)
- [mcMMO](https://www.spigotmc.org/resources/official-mcmmo-original-author-returns.64348/) [⏬](#mcmmo)
- [Minepacks](https://www.spigotmc.org/resources/minepacks-backpack-plugin-mc-1-7-1-15.19286/) [⏬](#minepacks)
- [No Mob Griefing](https://dev.bukkit.org/projects/no-mob-griefing) [⏬](#no-mob-griefing)
- [Voteday](https://www.spigotmc.org/resources/voteday.77077/) [⏬](#voteday)
- [XP Trading Cards](https://www.spigotmc.org/resources/xp-trading-cards.9378/) [⏬](#xp-trading-cards)


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


## Grappling Hook
You can craft grappling hooks, with different usage amounts, using the recipes below.

Simply hold the grappling hook and right click. If the hook grabs something, it'll pull you to it. It's a nifty way to cross gaps or stop yourself from falling!

Once you've exhausted a grappling hook, it will break.

![alt text](https://rlseaton.github.io/superdogpit/images/wooden-grappling-hook.png "Wooden Grappling Hook")
![alt text](https://rlseaton.github.io/superdogpit/images/iron-grappling-hook.png "Iron Grappling Hook")
![alt text](https://rlseaton.github.io/superdogpit/images/gold-grappling-hook.png "Gold Grappling Hook")
![alt text](https://rlseaton.github.io/superdogpit/images/diamond-grappling-hook.png "Diamond Grappling Hook")


## Marriage Master
You can get married any other player! Married players get benefits such as shared XP, the ability to share backpacks, send gifts from *anywhere*, the ability to kiss, turn off friendly fire, teleport to your spouse, and a lot more!

The first thing you'll want to do is **find a priest**. You can do that with `/marry listpriests`. Ops are priests automatically, and can ordain other players as priests if necessary.

Once you've found a priest, the two of you need to be in the priest's vicinity, and the priest can then marry you by typing `/marry marry PlayerName1 PlayerName2`.

You'll be notified and must then either `/marry accept` or `/marry deny`. If you both accept, congrats! You tied the knot!

You can type `/marry` to get a full list of commands and what they do. Note that `sethome` and `delhome` are for setting where you'll end up if you type `/marry home`.


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


## XP Trading Cards
As you're out killing mobs, you might notice that they now occasionally drop trading cards! Most of them will be for all of the classic Minecraft characters we all know and love such as Pig, Zombie, Cow, etc.

But sometimes you'll get a card based on one of the players on the server, or even cards for characters who have appeared in game jams or games being actively developed on the Dogpit Discord!

![alt text](https://rlseaton.github.io/superdogpit/images/card.png "Trading Card")

**Over time, new cards might be added, along with flavor text! You can even get "shiny" versions of cards.**

So... what do you do with these? 

Well, you can collect them, obviously, and trade them with other players.

You can also organize them into **decks**, which are ultimately freely available card-only inventories *(if you put non-card items in them those items pop out when you close them)*. Decks are labeled by numbers (so you can have Deck #1 with all of your zombies, Deck #23 with all of your rares, etc.). To get, for example, your #2 deck, simply type `/cards getdeck 2`.

Decks are kinda weird in the fact that they are like little individual card-only Ender Chests. You can type `/cards getdeck 2` over and over and get 10 of your #2 decks. You can even stash those decks in chests, or give them to other players. But those decks will always be *yours*, and changes you make in any deck with the same label (#2, or #153, etc.) will be made to all copies. These are really for **organization only**.

What else can you do with them...?

You can also get **rewards** for collecting all cards from any given "rarity" (common, uncommon, legendary, etc.).

To see your progress, type `/cards list`. If you see a rarity listed as **"complete"** then you can turn it in for money and prizes!

To collect your reward, for example let's say you've collected all of the "Very Rare" cards, make sure all of the cards are in a deck, then type `/cards reward Very_Rare`. You will lose one of all of your "Very Rare" cards and receive a reward!

**Note:** The list and reward commands only take into consideration **cards in your decks**. So you must put cards into decks before checking your progress or collecting your reward! Otherwise it won't know you own them!

**Note:** Be careful because the reward command can, and will, eat "shiny" versions of cards. These are no different from non-shiny cards, but players may value them more!

&nbsp;  
&nbsp;  
&nbsp;  

---
&nbsp;  
&nbsp;  
&nbsp;  

# Dogpit: Unleashed
The Dogpit: Unleashed Minecraft server is a private server for the Dogpit Discord channel. It's running the **Attack of the B-Team** modpack from Technic.

Unlike Dogpit, which is a collection of Spigot plugins, Dogpit: Unleashed is a truly modded server, and therefore requires a special client to play. The modpack is a curated collection of mods managed by the good folks at Technic.

*Keep in mind that this modpack runs on a very old version of Minecraft: 1.6.4. So many of the new features you might be accustomed to in 1.15.x may be missing or implemented by a mod in a different way.*


## Unleash Yourself and Face to Bloodshed
The easiest way to connect to Dogpit: Unleashed is to use the **Technic Launcher** available at: [https://www.technicpack.net/download](https://www.technicpack.net/download)

Once you've downloaded and installed the Launcher (or just downloaded the portable version), start it up and login with your usual Minecraft credentials.

Click the **"Modpacks"** tab at the top of the launcher window. In the modpack list on the left, find the one named **"Attack of the B-Team"** and click it. You can then install the modpack using the "Install" button on the bottom-right.

This takes care of making sure you have all the right mods in all the right places, and manages individual modpack installations for you. It really does take a lot of the hassle out of connected to a modded server.

From this point forward, connecting to and playing on the Dogpit: Unleashed server works exactly like any other Minecraft experience.


## Mooooooooods
You can find a list of all mods in use by Attack of the B-Team here: [https://www.technicpack.net/modpack/attack-of-the-bteam.552556/mods](https://www.technicpack.net/modpack/attack-of-the-bteam.552556/mods)

Listing every single feature from every single mod is out of the scope of this document. There's just waaaaaaaaay too much.

Instead, this document will occasionally be updated with some of the more frequently used, or frequently confusing, features. Most of the mods listed in the link above have their own wikis where you can find all sorts of information on how to use them. Remember: ***just because a mod is in use doesn't mean you have to use it***. Feel free to do whatever you want, play however you want, and don't feel forced to use all the mods. You are, in fact, *unleashed*, after all.


## Minimap
Dogpit: Unleashed does not have a Dynmap map like the regular Dogpit server. Instead, at any time, you can press **m** to bring up your own minimap. 

You can set your own markers/waypoints by right-clicking the minimap. It's pretty nifty!

The mod in use is called **MapWriter** and you can learn more about it at [https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1286882-mapwriter-an-open-source-mini-map](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1286882-mapwriter-an-open-source-mini-map).

