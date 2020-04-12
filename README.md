The Super Dogpit Minecraft server is a private Spigot server for the Dogpit Discord channel.

This document lists all installed plugins on the server, along with usage instructions from a player's perspective.

# Non-Plugin Notes and Modifications
- **Cats** (not ocelots), **wolves** (both wild and tame), and **parrots** are ***INVULNERABLE** on this server.
- There is a **community storage** center in the building at spawn where you can donate resources to other players.
- The **Dogpit Teleport Network** (DTN) central hub is located adjacent to spawn. You can use the booths there to travel to far away places.
- All players get a free **elytra** automatically, and more can be found in community storage.

# Installed Plugins
A brief list of all currently installed plugins, and a link to their Spigot/Bukkit page, as well as a ⏬ quick link to their respective sections in this document.

- [Dynmap](https://www.spigotmc.org/resources/dynmap.274/) [⏬](#dynmap)
- [Essentials X](https://www.spigotmc.org/resources/essentialsx.9089/) [⏬](#essentials-x)
- [Grappling Hook](https://www.spigotmc.org/resources/grappling-hook.70854/) [⏬](#grappling-hook)
- [Marriage Master](https://www.spigotmc.org/resources/marriage-master-mc-1-7-1-15.19273/) [⏬](#marriage-master)
- [mcMMO](https://www.spigotmc.org/resources/official-mcmmo-original-author-returns.64348/) [⏬](#mcmmo)
- [Minepacks](https://www.spigotmc.org/resources/minepacks-backpack-plugin-mc-1-7-1-15.19286/) [⏬](#minepacks)
- [No Mob Griefing](https://dev.bukkit.org/projects/no-mob-griefing) [⏬](#no-mob-griefing)
- [Poop](https://www.spigotmc.org/resources/poop-make-animals-useful.77186/) [⏬](#poop)
- [Vault](https://www.spigotmc.org/resources/vault.34315/) [⏬](#vault)
- [Voteday](https://www.spigotmc.org/resources/voteday.77077/) [⏬](#voteday)
- [Wholesome Healing Bandages](https://www.spigotmc.org/resources/wholesome-healing-bandages.77004/) [⏬](#wholesome-healing-bandages)
- [XP Trading Cards](https://www.spigotmc.org/resources/xp-trading-cards.9378/) [⏬](#xp-trading-cards)


# Dynmap
[http://superdogpit.apexmc.co:8123/](http://superdogpit.apexmc.co:8123/)

Generates a *GoogleMaps-esque* map of all server worlds at the link above.

You can also **chat** directly from the map using the chatbox on the bottom of the page *(assuming you've logged into the server recently)*.

You can share a specific location by clicking the **link** button on the bottom left.

The map updates constantly, but don't expect your exploratory boat excursions to be reflected on the map very quickly. It can take minutes to hours for changes and new chunks to appear on the map.


# Essentials X

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

Lastly, you can also **send players offline messages** by using the `/mail` command.

For example, `send PlayerName Hey how are you?`.

You will be notified if you have new mail, and can read it with `/mail read`.

Once you've read your mail, you can use `/mail clear` to empty your mailbox.


# Grappling Hook
You can craft grappling hooks, with different usage amounts, using the recipes below.

Simply hold the grappling hook and right click. If the hook grabs something, it'll pull you to it. It's a nifty way to cross gaps or stop yourself from falling!

Once you've exhausted a grappling hook, it will break.

![alt text](https://rlseaton.github.io/superdogpit/images/wooden-grappling-hook.png "Wooden Grappling Hook")
![alt text](https://rlseaton.github.io/superdogpit/images/iron-grappling-hook.png "Iron Grappling Hook")
![alt text](https://rlseaton.github.io/superdogpit/images/gold-grappling-hook.png "Gold Grappling Hook")
![alt text](https://rlseaton.github.io/superdogpit/images/diamond-grappling-hook.png "Diamond Grappling Hook")

# Marriage Master
# mcMMO
# Minepacks
# No Mob Griefing
# Poop
# Vault
# Voteday
# Wholesome Healing Bandages
# XP Trading Cards
