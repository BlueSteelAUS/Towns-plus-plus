﻿[size=200][color=#0000FF]Towns++ v14e2 (for Towns v14e)[/color][/size]

[size=200][color=#FF0000]NOT a MODLOADER mod. DO NOT INSTALL in .towns/mods![/color][/size]
[size=100][color=#FFFF00]May or may not be compatable with Vanilla Towns saves or prevous versions of Towns++
Be sure to backup your old saves before running Towns++[/color][/size]

[code]
Known problems awaiting patches to Towns (already spoken to Xavi about them)
=========================================
1. If you trying to fill in a hole with them and there's something in it, it'll go through the motions of placing the terrain block costing you those resources but the block you're trying to place just disappears.
2. If you try to place it on water again it goes through the motions of doing everything but again won't place the terrain, it disappears. This is because you can't place things on water
3. The Campaign menu(New Game): At the moment its not displaying the campaign names its a bug in towns v14d It still works and everything is still clickable and runable
4. Auto Production level of Animals: needs countable stock of animals (which at the time of implimentation of this part of the mod was/is on the drwawing board. So I pre-empted the changes to the farming system)

Changes since Towns++_v14e
===========================
BlueSteel's Contributions
===========================
-> Fixed some blocks that weren't walls into walls (IE: can no longer walk through. EG: Claystonebrick blocks)
-> Changed Requirements for Smelter -> uses masonsbench not Anvil , requires 1 Wood , 2 Stone
-> Changed Requirements for Anvil -> uses Smelter not Masonsbench, same resources required
-> Added Stone hammer to utilities production menu (Yes its still in Weapons too)
-> Fixed Orientation and Rotation of Statues (well sort of needs more rotations for some, waiting on graphics)
-> Removed antiquated Del_ actions for some items (now handled in game using remove
-> Retitled Beds and some statues To make it easier to distinguish
-> Added some furnature and decorations into Buildings->Tavern section of right hand menu
(Hint:Hero's are attracted by certian things, they won't come unless you have the items they want in their rooms)
-> Added Hammer and Tongs to Buildings->Forge section of right hand menu
-> Added bone knife to Buildings->Carperntry section of right hand menu
-> Added some (not all) furnishings to Buildings->Personal space section of right hand menu
(for some different things look under furnature and decorations in right hand menu)
-> Added/Fixed missing half blocks view mode for some blocks that were showing full blocks
-> Fixed Statues rotations
(Still need more graphics for some, so graphics for North/South are the same as East/west for some, some have full rotation)
-> Renamed beds so that they know which beds are needed for Hero's
-> Updated readme and ToDoList

[/code]

To Install:
============
1. Backup your Towns Folder/Directory. This is usually C:\Program Files (x86)\Steam\SteamApps\common\towns
   if you installed the game through Steam. (I'm not responsible for any losses or damages)
2. Copy the contents of the Towns++ zip into your main Towns Folder/Directory.
3. Launch Towns as normal!
4. As always feel free to leave comments, bug reports, suggestions.

[quote]
Stable Downloads:
=================
-> https://github.com/BlueSteelAUS/Towns-plus-plus/archive/14e2.zip
-> http://townsmods.net/projects/view/101
-> http://www.nexusmods.com/towns/mods/3/?

Unstable Download:
==================
NOTE: the unstable Download is always in a state of flux you take your changes with the absolute latest under development version of the Towns++

-> https://github.com/BlueSteelAUS/Towns-plus-plus/archive/master.zip

Towns++ Media
=============
My Live streaming is at http://www.twitch.tv/bluesteelaus
My YouTube play list for Towns++ : http://www.youtube.com/playlist?list=PL388A502D490AE834

Neen's Towns lets play , using this mod: http://www.youtube.com/watch?v=ZjWw0eiQpZc

Another Twitch streamer that has Streamed Towns++ mod games is
p00bles http://www.twitch.tv/p00bles

More videos and live streams will be done as time permits
[/quote]

[code]
When ever you have questions or have suggestions or find bugs ,
please raise an issue on https://github.com/BlueSteelAUS/Towns-plus-plus/issues?state=open
so that we can have all the support related stuff in one area that can be looked at quickly
and where we can keep better track of errors and fixes

its also good for checking to see if anyone else is having same problems or making the same suggestion.
if they are please add a comment to the existing issue report.
This lets us know how popular the suggestion is, or how big of an issue the bug is and whether its repeatable
[/code]

ABOUT TOWNS++
=============

Welcome to the longest running and I believe still one of the best and largest mod for Towns.

This mod changes the layout of the right menu panel and the main (bottom)menu panel,
zones are now treated as the floors in the buildings.

Adds a lot more Stairs, Furniture, Walls, Decorations, Workshops, Food, Items, Walls,
 Monsters, maps, flowers, statues, flags ... the list goes on and on.
(Basically adds a ton of stuff to the game)

I see you might be a little confused. What I've done is taken workshops and added
each as a building in the buildings menu, placing the appropriate zone in that
building along with its utilities into a sub menu for that type of workshop (room or building).
This provides quick and easy access to what your trying to build and furnish all in the one menu.

Zones menu is still accessable by hitting the right hand red button on the bottom menu thus scrollong to it

A new button has been added to the main menu its the Destruction button.
You can now quickly and easily remove or Un-Till selected item types or land
when you no longer need it. Items are removed not destroyed, they can be re-used in other places or sold

The Dining Room has been removed. Now your villagers will join your heroes and eat in the Tavern.
This will make your taverns much busier, as they should be.

The production menu has also been tweaked and added to so that you can make things
without placing them, this is handy for quickly replacing doors etc.
it will also allow for a latter addition to my mod where you'll also be able
to SELL them to markets as they are interested in buying (Still being worked on).

Farms have been converted from buildings to items, like the carpentry bench.
Currently you can control production from the left hand menu,
however the game does not count living creatures at the moment.
If you set any production with the right arrow maximum above 1 they will automatically produce more animals,
It continue doing so until you turn it back to 0. resources permitting
Using the left Arrow should produce a set amount then stop producing

In order to construct the new farms you need a male and a female of the animal you want
to farm (or two of animals with only one gender) and some wood. In order to produce
an animal, you need the food type that they eat.
After producing an animal there is be a cool down period

Note: also while going through the data files I noticed that there is a hero that
kills bulls and boars (this is in the standard game, I haven't edited them at all)
so you have been warned.

Added beer and wine making (in the Tavern, naturally.)

Tavern Rooms can now be build seperate to tavern, so you can place them up/down stairs

Changed from one generic mine type to a mine for each raw material, including ores
that you couldn't mine before. The mines now only need one square of ore. 
The new mines have lights on them which identify if the mine is ready to harvest or not. 
If a mineshaft isn't used in a certain period of time it collapses to rubble due to lack of 
use and maintenance (this is the pay off for being able to mine everything and only using
one square). If you have a large area of rubble you can clear it using the command 
located in the Terraform area in the menu. You also now need a sample of the resource your 
going to mine to build the mineshaft, eg: a gold mineshaft requires one gold to build a mine 
for gold. This can be costly if you aren't mining all the time (Which is done via the production 
menu) so keep in mind not to use ALL your mined resources or you may not be able to build 
another mine when your last one collapses due to lack of use.
You have been warned...

Changed the Font to use Metamorphous size 18 for easier reading (license included in main directory) 

Added in Terraforming (on the right menu.)
Terraforming and terrain blocks require 4 of the resouce gathered from that terrain type to convert/build it.
(as of Towns v14d you can now add terrain blocks which i've remaned from terrraforming to add terrain , to distinguish from my terraforming which changes the existing terrain thats there)

Nearly all item placement (right menu) is now set to QUEUEANDPLACEAREA/CREATEANDPLACEAREA
this makes the game more accessible to disabled people like myself,
who can't easily hold down keys and move the mouse at the same time.

Split the priorities so that they are now more logical and diverse

You can now resurrect dead Citizens that have been burried using shrines (via the right production menu)

Tasks and their Priorities have been re-organised for better control of your citizens

Crops once tilled and some have been planted , will (slowly) spread over the tilled area
Crops will cycle if not harvested in time, eg: wheat will go back to seed if not harvested in time


Remember
========
The right menu is for building and placing.

The left menu is for building and storing.
NOTE: Not all items can be pre-built eg: things that activate straight away like campfires)
The bottom menu is the action menu.

This is a big mod (Fluctuating in size every release as the developers add more
stuff into the game similar to that i've added and removed when they've implimented
the same or similar changes to keep gameplay balanced and as true where possible
to the vanilla for easier implimentation of others mods using modloader,
Note: your experience of using a mod nod sesigned on Towns++ mod will vary dramatically or even fail)

There are a total of 21+ files edited and extended, also several new files.
There are so many changes in them (with both the layout/ordering) that at the moment I don't think that
there is a modloader out there that can handle everything that I can do for the same effect
this means that this modpack is basically a standalone modpack.

I'm always on the lookout for others Ideas to add into my modpack
(credit is and will be given to others works Iinclude with their permission of course.
So, if you'd like me to try to combine others mods into my modpack contact the authors
of that mod and get them to contact me expressing their interest / permission.
Note: the mods may have to be tweaked so that they work and play well with what's already in Towns++.

You can also Write your Own Mods to modify Towns++, Just make sure that people
know that they'll need Towns++ installed to use your Modloader compatable mod.
I'm Not Responsable If they don't work or break, It'll be up to those Modwriters to keep them up to date with any changes made to Towns++

Permissions to include their work received from:
================================================
Niranufoti
Kasdar
JackPS9
YetiChow
Cobalt262
ericb1800
FONDZ
Ricky
RedValkyrie
Wolfy
Brigadon
dw420
Jontis_00 (upon request per mod) so yes only certain mods of his
(and a few others really early on who's mods are now no long in or have been edited way beyond
what was originally their mod. these mods were way back in the early days, some of which
(including some of my own work) have even made their way into the main game of Towns in one form or another 

Just because I have permission doesn't mean that I have any of their work in my mod

Meet the team
=============
Some members on the Towns forum have asked me if they can help me and that I have
accepted these people them as part of the team they are
Welcome them aboard.

If you wish to help in the mod please feel free to approach me about becoming a member of the team.
Just because you approach me doesn't necesseraly mean that you will become part of the team.

People who have contributed in the past and no longer on the Team
=================================================================
-> LittleMikey

Public Domain art by:
=====================
yd http://opengameart.org/users/yd (merchant tents)

Disclaimer/Rant
===============
I am the lead coder and Owner / Distributor of this mod, so my decisions on
what to include and how is final. Sometimes I'll use others mods in my pack,
these inclusions mean that I have Tweaked them to work with my mod and to try
to keep balance in the game so that it is still difficult enough to enjoy.
Its not a meant as Cheating mechanism or a dedicate creative mod where you
get stuff for nothing.

IF you want to use part of my mod as a separate mod for distribution please ask and give Credit
Feel free to link to this tread and my mod's links (d/loads,YouTube,Streaming)
But do not place this mod anywhere else for Distribution

Still on my to do list
=======================
(see the text file Towns++ToDo.txt included in the archive)



change logs
===========
[spoiler]
Changes since Towns++_v14d2
===========================
BlueSteel's Contributions
===========================
-> Fixed missing Skootenbeeten graphics
-> Fixed missing female animals on deep dungeon map
-> Updated to 14e
Adding Terrain block: (in original called terraforming, renamed in towns++ to Terrain because of my own True Terraforming (actually converting the existing terrains not adding blocks of terrain)


LittleMikey's Contributions:
============================
-> Fixed slight graphical glitch with log bridges.

Changes since Towns++_v14d
===========================
BlueSteel's Contributions
===========================
-> added caged female animals to production menu
(need to get new graphics for them , currently using same as male)
-> fixed graphics for caged female sheep
-> minor bug fixes and tweaks
-> edited readme to addin and re-organise what the Towns++ mod actually provides/changes
-> fixed missing graphics for milkedfemaleunifallow and layedeggskootenbeeten

LittleMikey's Contributions:
============================
-> fixed tilling of jungle tiles
-> canyon map tweaks to livingentities

Changes since Towns++_v14c
===========================
BlueSteel's Contributions
===========================
-> updated to work with Towns v14d
-> Added in female Skootenbeeten, Unifallows, Snoats, Badgers and their associated farms
-> All farms now need a male and a female of that animal to make
-> Fixed some killing of farmed animals only , no wild animals should be being auto killed for production any more
-> Added all the wild female animals to the default maps and tweaked their numbers as there are now a lot more animals
-> Female animals that can produce like: milk, eggs, feathers, wool
   are NOT auto butchered when auto producing like bones , hides or meat
   As usual you can still kill them when right clicking them
   It also gives you a reason to have the male / female animal farms apart from breeding
NOTE: the changes to the animals in the game has changed a LOT, so there will probably be bugs. Please report them on the issue tracker so that we can fix them
-> changed Skootenbeeten diet, they now eat and require banana or blue radish to breed and keep tame alive
-> changed Snoats diet, they now eat and require snow cherries to breed and keep tame alive
-> Tweaked maps living / items generated
-> Fixed animal breeding in production menu and right clicking
-> minor bug fixes and tweaks

LittleMikey's Contributions:
============================
-> Added new wood walls, graphics by dw420
-> Added new stone walls, graphics by dw420
-> Added new stone stairs, graphics by dw420
-> Added new ITE Well, stores 100 instead of the 25 you can have in a chest.
-> Converted Caprontos' Canyon map 
-> Reduced value for Wood, Dirt, Stone and Sand when trading

Changes since Towns++_v14b2
===========================
BlueSteel's Contributions
===========================
 -> updated for Towns v14c
  
LittleMikey's Contributions:
============================

Changes since Towns++_v14b
===========================
BlueSteel's Contributions
===========================
-> Fixed bakeroven rotation and decoration
-> fixed bread sign not sticking to wall
-> tweaks to fleeing system
-> added rawfood.harvested,gathered,processed,meat to food caravan
 -> made it so that you can grow flowers on any tilled terrain
  
LittleMikey's Contributions:
============================
-> Added rotation to chairs.
-> Changed Sandstone Stairs to use new rotation system.


Changes since Towns++_v14a
===========================
BlueSteel's Contributions
=========================
-> updated to v14b of towns
-> commented out sheep farm in buildings.xml (we no longer use buildings.xml for anything and haven't for quite some time)        
-> some bug fixes and fixed some rotations that got missed when updating to v14a
-> temporarialy re-added stonesteps1a and other stuff that was prematurly deleted from to items and graphics
(should never have been called as that should have been saved as vanilla name, will also have conversion to default items)

-> changed terraform gravel to 2 flint and 2 stone From timtanton@yahoo.com 's email, thanks
-> changed dormbrd to use only straw no wool (cheap bed) (idea was a straw only bed)From timtanton@yahoo.com 's email, thanks
-> fixed black and white colours in production menu From timtanton@yahoo.com 's email, thanks
  
LittleMikey's Contributions:
============================
-> Fix carpentry bench
-> Fix crash on Oasis map
-> cb262 Stairs are now rotatable using Vanilla system. If you have existing modded stairs on your map, either right click
    them and rotate them back to the default position, or remove them and build them again.
-> Removed rotations and decorations for the Baker's oven. They were not getting used during baking.
-> Removed rotations for Market Tents until new graphics can be made.

[/code]

Changes since Towns++_v13a3
===========================
BlueSteel's Contributions
=========================
-> updated to v14 of towns
-> Fixed right menu QUEUEANDPLACE TO QUEUEANDPLACEAREA    
-> Cows, Milkedcows, chickens,layedeggchickens removed from butcher list
   The Right button action remains so that you can kill them manually
    (will also change unifallow and milkedunifallow,
                      snoat and milkedsnoat and skinnedmilkedsnoat,
                      skootenbeeten and layedeggskootenbeeten
    when we've added in the male counterparts to them ;) )
        
LittleMikey's Contributions:
============================
-> updated to v14
-> Added loads of new graphics by dw420 on the forums! Including but not limited to:
*New Statues
*New ITE graphics
*New Log Walls
*New Stone Blocks
--Massive thanks to dw420 for making all these!--
Changes since Towns++_v13a3
===========================
BlueSteel's Contributions
=========================
-> Fixed right menu QUEUEANDPLACE TO QUEUEANDPLACEAREA    
-> Cows, Milkedcows, chickens,layedeggchickens removed from butcher list
   The Right button action remains so that you can kill them manually
    (will also change unifallow and milkedunifallow,
                      snoat and milkedsnoat and skinnedmilkedsnoat,
                      skootenbeeten and layedeggskootenbeeten
    when we've added in the male counterparts to them ;) )
        
LittleMikey's Contributions:
============================
-> Added loads of new graphics by dw420 on the forums! Including but not limited to:
*New Statues
*New ITE graphics
*New Log Walls
*New Stone Blocks
--Massive thanks to dw420 for making all these!---

Changes since Towns++_v13a2
===========================
BlueSteel's Contributions
=========================
-> Added Niranufoti's Spiral Staircase mod (edited to fit with rest of Towns++ now takes 3 wood)
-> fixed terrafom to stone (thanks to Litcube for finding this bug)
-> fixed requirements for terraforming to DenseStone (there wasn't any , now requires rmstone*4)
-> fixed terraforming when interupted by fighting with mob and placing in wrong spot
(when testing, i had my cits attack an enemy and get drawn off the grid you want terraformed.
 it then terraformed where the fight ended not the grid you selected)
    
LittleMikey's Contributions:
============================
-> Re-added gatheringharvesting priority from vanilla, renamed it to "Breeding" and assigned it to
   breeding animals. This will mean all your other Towns mods should be compatible now.
-> Re-added buildings priority. This should stop vanilla saves crashing. However the priority isn't
   used by anything in Towns++ currently so it's at the bottom of the priority order.
-> Fixed crashes/errors with Gifts.
-> New barn graphics by Brigadon!
-> Priority fixes/changes.
-> New walls by Brigadon!
-> Added Shearing Bench. Now if you want to shear your Sheep, Snoats or Skootenbeeten you can use this comfy bench!
-> Small tweaks to Oasis map.
-> Cacti will now no longer disappear from your maps.
-> Cakes now require Milk and Eggs. Since they taste way better now they fill your townies up more!
-> Added Construction Caravan. This caravan will sell you walls, windows and the like, and buy them 
   as well.
-> Added generic values to construction items so you can sell/buy them. Please post if you find any I missed!

Changes since Towns++_v13a1
===========================
BlueSteel's Contributions
=========================
-> Miscellaneous fixes/tweaks in actions.xml
-> Miscellaneous fixes/tweaks in items.xml
-> Added New citizens, You need to have buried people and a shrine to be able to reclaim them through the Production menu
   This limits the number of cits you can re-gain back up to a max of the total cits you've had in the game already
-> Re-added (again) as per request Zones menu (to the far right of the main menu. scroll to get there)
-> Changed All prepared food to same value, so that they should now eat all foods(at random) not just the higher liked foods
    
LittleMikey's Contributions:
============================
-> Added missing <type> tag to Clock.
-> Changed some of the rotatable stairs to the vanilla stairs. Now you won't need to click the "Make me rotate" action
   on any stairs you have added from any vanilla saves.
-> Reorganised default priorities layout slightly.
-> Fixed graphical glitch with decorated tavern benches.
-> Changed "Crops" to "Agriculture" in the right menu, because Trees aren't really a crop.

Changes since Towns++_v13a
============================
BlueSteel's Contributions
=========================
-> Incorporated Bookshelves mod - thanks Niranufoti for their permission to incorporate it into Towns++
   (Niranufoti has now joined the esteemed list of Authors who have given us permission to incorporate
   their mods into Towns++, so that you the players of our mod don't miss out of the latest and greatest mods.
   See below the updated list of Authors of which we have incorporated their mods, graphics into Towns++)
-> Moved containers back out of Decorations into main of the right hand menu
-> Updated Campaigns.xml to Display "Press F1 in Game for instructions" for Tutorials and BlueSteel's maps
-> Fixed qchesstable (somehow i missed putting lock on carpentry bench)
-> Fixed qbamboostick (somehow i missed putting locks on the workbenches)
-> Added artisan table to atelier zone for doing all the crafty stuff that used
   to be done at the skinner freeing up the skinner so that it can do what its designed to do.. 
-> Coloured items now require the appropriate color dyes to make eg: beds,chairs,lights,signs,books,scrolls...
-> changed purple throne now required wool as well
-> changed banners (small ones now require 1 wool but no more iron) (large ones require 2 wool and iron to take the weight) and appropriate dyes
-> some chairs require wool now too
-> beds now all require , wheat,timber,wool and appropriate dyes (the default bed doesn't require dyes)
-> added missing <lock> tags to making out modded items
-> fixed some stuff being made at wrong workbenches,
   You'll now require a wider more realistic setup to make the finer things in life
-> Fixed wine making requiring beerbarrel bug , now requires the wine barrel
-> Added badger and snoat to killforbones
-> Miscellaneous fixes thanks to Palindine for these fixes
     
LittleMikey's Contributions:
============================
-> Changed food types so Evil Badgers no longer steal Raw Food Barrels.
-> Removed milking Does from Production Menu.
-> Moved Furniture back to Right Menu.
-> Added Paper. Books and Scrolls now need Paper to craft. You make Paper at a Mill using Water and Wood.
-> Added White, Black and Blood slimes, more flavours of Jelly for you!
-> Added White and Black colour graphics.
-> Graves now require the remains first before they will begin finding the other materials.
-> Condensed several image files down to one file to reduce mod size.
-> Added Sushi. Not completely filling, but does not require cooking if low on resources.
-> New graphic for Cooked Fish. Sushi now uses old graphic. 
-> Removed "Buildings" priority since nothing uses it.
-> Added ability to queue caged animals in the production menu.
-> Added new priority for mining resource mines. It seems to work better now.
-> Removed wild animal tasks from production menu.


Changes since Towns++_v12b1
============================
BlueSteel's Contributions
=========================
-> updated to Towns v13a
   
LittleMikey's Contributions:
============================

Changes since Towns++_v12b
============================
BlueSteel's Contributions
=========================
-> All new games citizens and new immigrants now have the knowledge of how/when to
   run away when their hit points are low
-> Added in the Cloud of Knowledge. Build a medicine cabinet and then have your
   citizens go around there (within 250 squares, same level and in Line of Sight
   of the Cloud of Knowledge that appears when you first place a medicine cabinet.
   (If you already have one built just delete and rebuild/place it)
   Inspired by the idea of the chickenheart/chickenritual mods by Dremire
-> All zones can now be as small as 1x1 grid
-> Change materials from iron to iron or copper for cookingbowl, skinner, stove.
-> More tweaking on my map
   
LittleMikey's Contributions:
============================
-> Types changed on various items to make more sense. 
-> Added new caged animals, and a new caravan who sells them.
-> Added the ability to cage animals, and sell them to the new caravan.
-> Added new stockpile for caged animals.
-> Changed breeding animals to use the Feed priority instead of itemConstruction.
-> Added remove command to rest of hero tombs.
-> Fixed error with armor/weapon cabinets.
-> Fixed graphical issue with rotating some coloured stairs.
-> Added mine/dig ladder command to Snow, Desert and Jungle tiles
-> Changes to Oasis map. Now able to go up to level 20, also added more levels
   underground before hitting the dungeon.
Changes since Towns++_v12a1
============================
BlueSteel's Contributions
=========================
-> More work done on snoats
-> 1st of many new maps by me (starting to rework my old maps mod)
-> updated to towns12b

LittleMikey's Contributions:
============================
-> Fixed crash with Flower Drawer.

Changes since Towns++_v12a
============================
BlueSteel's Contributions
=========================
-> Made it so that shearing (trimming) now happens in a barn for that animal type,
   eg: snoat in a snoat barn, sheep in a sheep barn(includes the wild ones, no shed = no shearing)
-> Changed mines to <type>mine</type> (hopefully stop monsters dropping the mines as loot)
-> Added shearing of milked snoat (trimmedmilkedsnoat)         
-> Scaffold is now on main menu and removed from production and right hand menu's
-> Made animal farm menu in production menu;shifted breeding,butchering,animal produce into there
-> Added more flowers into generated default maps
-> Made sub menu for timber in materials production menu
-> Moved Colors,Hides,Flowers into materials production menu
-> Changed beer/wine now only requires 2 resources to brew + 1 waterbucket
-> Changed Beer/Wine Happiness calculation (twice as happy as normal drinking)
-> Fixed wearing hat/mask happiness similar to Kasdar's Hat Happiness Fixed
-> Reduced breeding costs to 1 of the resource
-> Changed pig and boar feed and breed to apple or pear or wheat
-> Fixed unifallow feed and breed to cactus fruit
-> Set Snoats feed and breed to apple or pear or wheat
-> Added all sheep to butchercow (only till we come up with Lamb Chops)
-> Revamped food submenu in production menu
-> Revamped militaries submenu in production menu (combined armors and weapons by material type)
-> Re-organised decorations. eg: combined indoor/furniture / outdoor .
-> Also added appropriate containers to the buildings
-> Separated decorations into furniture, plants, signs, statues/poles,  flags/banners, winter items, lighting
-> Move mines and graves the main right menu because they really didn't belong where we had them anymore
-> Added Beds sub menu to Appropriate rooms

   NOTE: Terraforming is Still there(Hit the red button on the right side of the main menu)

LittleMikey's Contributions:
============================
-> Edited main game menu
-> Fixed errors


Changes since Towns++_v12
============================
BlueSteel's Contributions
=========================
-> added missing untill dirt action to terrain.xml
-> Tidy'd up items.xml for better comparing
-> changed road (75), pavement (65) walk speeds to be constant
-> re-added Beer and wine to production menu
-> re-organised food production menu
-> updated to 12A
-> added missing breed sheep to menu_production
-> changes to menu_right and menu_production

LittleMikey's Contributions:
============================
-> New type for Graves, so they don't show up in Caravans.
-> Fixed missing action for Sheep Farms.
-> Removed duplicate items from items.xml

Changes since Towns++_v11a7
============================
BlueSteel's Contributions
=========================
-> Finished terraforming , now requires 4x resource obtained from what you're converting to
-> Deleted rotatable gifts (difference not very noticeable when rotated)
-> Rebalanced resources gained from mining/digging
-> Added rmmud to all forests when digging/mining

LittleMikey's Contributions:
============================
-> Fixed butcher Boars for Pork.
-> New Names by ericb1800.
-> New Oasis map by me. This map features a large Oasis, with a very empty desert surrounding it.
   Resources are hard to find, it's very rare to get surface minerals, and the only easy to get
   food sources are Fish from the Oasis and Cactus Fruit. You will need to rely on Market Caravans
   to bring you more food types if you want to expand!
-> Integrated blurpsl's Removable Items mod. Enhanced original mod to allow removal of all rotatable
   furniture, roads and stairs.
   NOTE: Removing a rotated item will return you the original rotation. This is necessary so you can
   place the item back down again from the right menu, as well as sell it at a caravan if applicable.
-> Added "Kill area" order for clearing an area of animals. Use with caution!
-> Cactus Soup can now be made on a cooking fire.
-> Fixed removing Market Stalls. 
-> Integrated ericb1800's Complete Colours mod, and added a few new colours of Flower, Garden and Hedge.
   Flowers can be found naturally in new maps, but have also been added to some Caravans so you can 
   still find them on old save games.
-> Also from ericb1800, added new Slime colours. Now you will find Yellow, Orange and Purple Slimes.
   These slimes currently have the same stats and rarity as Red Slimes. New slimes will only spawn in
   the Oasis and Deeper Dungeons map for now.
-> All slimes drop different coloured Gel, and this can be made into a new food item, Jelly! Jelly
   doesn't fill as much as meat products, but it does provide a happiness boost to anyone who eats it.
-> Fixed removal of Graves. Graves now produce "Unearthed Remains" when removed, so you can use these
   to rebuild any type of grave with the one you unearthed. You will still need the usual materials to
   build the new grave.   
-> Fixed crash with Ancient Stone Stairs right click context menu.
-> Added remove ability to cb262's Coloured Stairs.
-> Spanish translations by frenchiveruti
-> Sheep farm updated to use new method of farming.
-> Fixed types for some rotated items showing up in stock menu.
-> New Tomb/Corpse for Santa. Sorry kids!

Changes since Towns++_v11a6
============================
LittleMikey's Contributions:
============================
-> Townies now eat in the Tavern with Heroes. Dining Room removed. 
-> Added new stalls for the Market. No purpose as of yet, just decorative.
-> Added Rope Bridges made by GreyFalcon and edited by LittleMikey.
-> Moved the indoor chimney/fireplace from "Roofs" to "Decorations - Indoor".
-> Changed EFloors' Zones so Townies don't idle on them. 
-> Fixed Coal Mines being able to be built anywhere.
-> Swapped East & West rotations for beds so now the feet of the bed "points" in that direction.
-> Fixed issues with butchering new animals for bones.
-> Added new decorations for Tavern Tables.
-> Added lighting to more decorations.
-> Fixed mine action name for mine-shafts.
-> Fixed tilling Jungle tiles.
-> Fixed tilling Desert tiles
-> Made changes to Winter Items, including some snowmen that didn't fit in, and changed one of the hats to green.
-> Fixed issue with shadows on log stairs.
-> Fixed issue with creating a Desert map.
-> Added new stockpile for Construction items. Now you can store your building parts and construct buildings much faster!
   NOTE: There is no container for the Construction Stockpile. Have you ever tried to put a wall into a barrel? 
-> Added new farms, with graphics by me! (Sorry about them). These count as items instead of buildings, so they only 
   take up a 1x1 space. However they still have the same wait time as a building to produce a new animal.
   NOTE: Queue production in the left menu. The game will not tell you how many of an animal you have, but as long
   as you set production above 0 your villagers will produce more animals.
-> Added "Destruction" menu tab. Currently it contains delete scaffold and delete rubble from mine-shafts. It will 
   be expanded in the future.
-> Changed dead female sound effect. Now quieter and shorter. 
-> Reduced number of birds spawning on "Normal" and "Deeper Dungeons" maps.
-> Removed ability to terraform tilled land, you need to turn it back into regular terrain first. 

BlueSteel's Contributions
=========================
-> DEV work for later releases
-> Mentoring LittleMikey

Changes since Towns++_v11a5
============================
LittleMikey's Contributions:
============================
-> Added Fishing to menu_production.xml
-> New Mine graphics with lighting! Thanks to Ricky for the graphics!
-> Fixed Rubble graphics

BlueSteel's Contributions
=========================
-> Fixed Mikey's mistakes

Changes since Towns++_v11a4
============================

LittleMikey's Contributions:
============================
-> Added Mikehendi's Deeper Dungeons map option.
-> Integrated Table Decorations by ericb1800
-> Integrated Winter Items by ericb1800 (You can spawn items for free with Winter Items.)
   He changed the levels down from 1-20 to 1-3 so it should only spawn hats and cheap items,
   before he was getting Direite stuff which I felt was quite OP XD)
-> Added the ability to create Coal to the Burner menu using wood.
-> Changed Barbarian to eat in the Tavern like the other heroes.
-> Moved untill to Terraform menu just so the menu all fits on the bottom bar, without need to scroll.
-> Changed mines to drop rubble (negative happiness) instead of wood.
-> Added clear rubble to menu.xml and as right click action on rubble.
-> Fixed bug with rotated ovens not cooking properly.

BlueSteel's Contributions
=========================
-> Made a separate campaign for Mikehendi's maps (same will be done for anyone else's maps I decide to include)
-> added winter items to production menu and vanity stock panel for the time being, until i redo the stock panel
-> removed Bones from the butchers production panel as they are in the rawmats production panel
-> changed Burner-> coal to mats-> coal to keep things straight in the production panel (The way the burner panel 
 is set up it'll limit the amount of stock you have set it to burning off the excess, so I have read on the forums)
-> Added make coal from 2 wood to right click action of burner



Changes since Towns++_v11a3
============================
Re-Organised menu_right again,
-> Combined walls,doors,roofs,floors into a submenu called Construction (not happy with the name but it'll do for now)
-> Moved Animal farms out of buildings menu into its own spot next to Crops menu(was Planting)

Re-organised and added lots of Stuff to menu_production to better synchronise with the menu_right

Split terrainchange into Tilling and terrainchange (for Terraforming)
Split gathering and harvesting job/priority (gathering is anything non plant related, eg: water,snow buckets, milk, eggs etc)
To make sugar you now need to use the mill just as you do with flour
Moved making sugar to processing jobs/priority



Changes since BSMP_11a2
========================
Changed all CREATEANDPLACE's etc to CREATEANDPLACEAREA so now you can place a
group of anything down at a time

Added TerraneChange to other miscellaneous terrains, now you convert any terrain
(except water and air and lava) to any other main terrain

Split the tererrainchange priority into terrainchange and chopping,
now chopping trees has a separate priority to tilling and terraforming 

Split foodcooking priority into baking, processing, cooking,
making separate jobs for each (processing is making flour,sugar,salad at the moment)

Changes since BSMP_11a
========================
Changed the Font to use Metamorphous size 18 for easier reading (licence included in main directory) 
Incorporated Cobalt262's Rotating stairs mod 
Incorporated Cobalt262's Rotating furniture mod (adds some new stuff and changes barrels capacities to 25,
still have more things to make rotatable though)
Incorporated JackPS9 Fishing hobby priority setting mod and altered the Default order of the priorities
Added in Terraforming (on the bottom menu. hit the red button on the right to scroll across to it)
Edited all the menu's again because of the huge number of additions


Changes since BSMP_10b.1
========================
Implemented graphics from morefarms mod by EricB1800
Implemented EFloors mod by EricB1800

tweaked animal feeding times making them only need food half as fast same for them starving
added apples/pears to pigs and boars diets
fixed typo in graphics.ini (from 10b release of towns)


Changes since BSMP10b.2
=======================
updated for towns 11a
tidied up some of the items again
fixed moving mineshafts (when inactive)


Changes since BSMP_8a_20121115_1207
===================================
Updated to Towns V10b
lots of fixes / tweaks but basically remains the same

Changes made to BSMP_8a_20121111_1308 version.
=============================================
fixed: missing butchering of bulls,roosters,boars
fixed: missing butcherforbones of bulls,boars
fixed: wrong UI images for rooster and boar farms
added: gather red/yellow/blue flowers to vanity / materials production menu
 

Changes to previous version.

updated to run on 8a
minor tweaks for consistency
updated to run on 0.60
removed old custom maps

on the way
looking into problems with spawned wheat seedlings able to be being moved
looking into making my own categories in the stock panel for better grouping in-line with my UI
work on new custom maps / difficulty / terrain  etc...

Changes in BS_MP_0-47b_20120606_1225 from previous version of mod pack
====================================
Updated to 0.47b

Re-implemented wheat crop aging. (which they took out of 0.47b)
The main reason I added it in the first place was because as crops age and aren't harvested they eventually turn to back to seed
and the plants die off leaving a new crop in its place, it also balanced to the old 9 grid farms where you used to get 1 wheat every xx ticks,
now with the new farming your really getting 9 wheat every xx ticks, so the idea was to have it like stagger the crops according to when they were last harvested/planted.
ie: you could have say 50 grids of farms but depending on cycles / times not all of them would be available all at the same time to be harvested,
nor waiting with full crops forever till you harvest them.


Changes in BS_MP_0-47a_20120605_1353 from previous version of mod pack
====================================
Fixed mushrooms plants (jungle and cave) and blue radish plants so that they disappear when picked in wild like they used to  (so make sure you set up farms if you want to keep harvesting them)

Made it so that ALL planted crops/trees will self populate given time.
IE: Not harvested/chops down as soon as they are ready to be chopped/harvested they will spawn seedlings on neighboring appropriate humus and so that they won't grow on anything else)

Added some palm tree bushes spawn in wild.

Tidied up some of the XML crop coding in the process of doing the above listed features

Doubled the max age for mine shafts (asked for feature .. i thought they were long enough myself.. if it unbalances the game they'll be going back to old max age)

Added walls, bridges and roads to the furniture stockpile / containers (because doors were already in there)
(I might eventually make dedicated stockpiles for these  if possible and if someone can make up some icons for them for me for in the UI.png)

Tested changes by playing game (testing the changes made for about 24 hours)

While testing i got attacked by a ware pig and my pop drooped to 4 , when i let them catch up with their work orders and hauling it was the 6/2/1 and i got another 3 immigrants
So immigrants do arrive IF and WHEN you let your Civs IDLE. (do nothing, stand around for a lengthy bit of time)
They were only replacing what they were eating, from a wide variety crops and bakery,
with dining room with chairs and tables ,
12 personal spaces with beds,doors, pot plants,
and 2 statues near the ladder going down to their rooms


still have to remove old commented out XML code

Thoughts and plans:

maybe make it so that cactus plants don't repopulate in wild when harvested
(Desert maps are supposed to be hard)

maybe add gold and silver mines at the moment I'm thinking no at the moment .  these are supposed to be a limited resources
The other mines are there because they are every day resources eg: sand,gravel,dirt,stone that don't really impact the balance of the game

Look into (or find someone to have a go at) making my mod pack mod-loader compatible..
I'm against this as i can see it'll bring in incompatibilities and conflicts, as this mod-pack doesn't just add stuff,
it does a hell of a lot of tweaking and editing and sometimes removal of existing code.
At the moment my mod-pack I know exactly whats happening in it, but when you add other mods to the mix,
especially those that also alter existing code or use the same tags as i do can and will cause instabilities which will be out of my control.)

ADD in New Spawns for males of the farm animals to replace some of whats used.
I'm thinking of is to make farms for the males just like there are for the females for the animals, but don't really like this idea.


Changes in BS_MP_0-47a_20120527_1445  from previous version of modpack
=====================================
Fixed missing Flour entry in AP food gathering menu
removed bones from ap menu food butchering menu (because bones aren't food) they are in the ap materials menu

no other changes apart from updating it all to work with the new stuff in 0.47a


Changes in BS_MP_0-47_20120526_1422 from previous version of modpack
===================================
Fixed bug in previous version of my mod pack. Making of jailwindow1 (ie: not moving to mason's bench after picking up iron)

Moved traps to its own submenu on the right hand menu as opposed to it being included in utilities

no other changes apart from updating it all to work with the new stuff in 0.47


updated again for 0.46 2012-05-12

Commented out Zones and Stockpile on main menu and moved to end of file as they don't follow the logic of my menu system. Which is
* Left menu for Build/Queue and store
* Right menu for build and place (now also includes stockpiles)
* Bottom menu is now only Actions that don't require resources

Added items to the Left hand menu that can be built and stored  for pre-building them to be placed later thus adding to the things you can set up a stock of.
(This does NOT include cooking fire, mine shafts, animal farms, seeds/seedlings/bushes/trees/animals because they start activated as soon as they are created)
 

added/edited/fixed for 0.46
Added qgatherplantedflowers into ap menu/gathering
Moved qbutcherforbones in ap menu to materials ( because they aren't food )
Re-ordered ap menu/vanity according to take into account the order that the production is needed
Fixed missing missing entry in main chop menu
you can now fill in any hole you dug no matter what terrain
Added Clock into the only rooms/buildings that it can be placed in
Separated the Walls menu a bit more , now has Fences and gates, also bone doors and walls sub menus
Reverted some of my code to the original Towns code after they fixed bugs from 0.45b (yes my coding would have still worked 
but it would have made updating my mod pack even harder every update, I'll always try to leave their existing code alone where possible)
Disabled (commented out) Tree of life in planting seeds menu as apparently it wasn't meant to be in the game yet (read this on another thread on this forum)
(More to come, just wanted to get it updated and out to you all)
could be adding in non Auto Producing items to display their current stock levels on the map (these will include as part of their tooltip "STOCK ONLY" or something similar)
[/spoiler]