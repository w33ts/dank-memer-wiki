---
title: Fishing
description: 
published: true
date: 2023-11-07T18:03:57.957Z
tags: 
editor: markdown
dateCreated: 2023-10-31T07:09:10.915Z
---

# Dank Memer Fishing
In 2023, the fishing command in Dank Memer was complete redesigned and expanded to add multiple subcommands, new <a href="/Items/Fishing/Creatures" target="_blank">creatures</a>, NPCs, multiple fishing <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishLocations" target="_blank">locations</a>, a <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishSkills" target="_blank">skills system</a>, and more. It was one of the largest updates the bot has had in years, and brought a completely new way of playing Dank Memer.

**Fishing Commands:**
- <a href="/Items/Fishing#Buckets" target="_blank">/fish buckets</a> - Use to manage your buckets, organize what you've caught, sell <a href="/Items/Fishing/Creatures" target="_blank">creatures</a>, and move creatures to your fish tank.
- <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishCatch" target="_blank">/fish catch</a> - Use to equip tools and baits, pick a location, and to fish.
- <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing/Guide" target="_blank">/fish guide</a> - A useful guide that shows all the creatures you've caught, NPCs you've met, locations you've visited, and your fishing stats.
- <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishIdle" target="_blank">/fish idle</a> - With the AFK skill, you can use this command to start an idle fishing machine that will fish for you while you do nothing.
- <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishLeaderboards" target="_blank">/fish leaderboards</a> - Use to heck the daily leaderboards you can compete on for special rewards.
- <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishLog" target="_blank">/fish log</a> - A log for fishing-related items, so you can see what you've caught and sold.
- <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishSeason" target="_blank">/fish season</a> - A leveling system within fishing where you can earn rewards, or upgrade to the premium pass for bonus rewards.
- <a href="/Bot-features/Currency-Commands/Basic-Commands#FishingShop" target="_blank">/fish shop</a> - A shop where you can use the Fish Tokens you've earned to buy fishing-related items.
- <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishSkills" target="_blank">/fish skills</a> - Use to check what skills you can upgrade to make fishing easier and more profitable. 
- <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishTank" target="_blank">/fish tank</a> - A virtual fish tank where you can save a few fish to show off or put decorations.

<br>

Fising Tutorials:
- <a href="https://dankmemer.lol/tutorial/complete-fishing-tutorial" target="_blank">Complete Fishing Tutorial</a> 
- <a href="https://www.youtube.com/watch?v=c3fFkl6IHyI&ab_channel=DankMemerDiscordBot" target="_blank">Video Fishing Tutorial</a> 
- <a href="https://dankmemer.lol/tutorial/legacy-items-fishing" target="_blank">Legacy Fish Items vs New Fishing Items</a> 
- <a href="https://dankmemer.lol/tutorial/managing-buckets-creatures" target="_blank">Managing Buckets and Creatures Tutorial</a> 
- <a href="https://dankmemer.lol/tutorial/fishing-npcs" target="_blank">NPC Tutorial</a> 



## Fishing Basics {: #FishCatch}
The basic command to get started with fishing is /`fish catch`. You can use this command to equip baits and tools, pick a location to fish at, and to start fishing.

<br>
<center>
  <img src="/bot-features/fishing/fishcatch.png" alt="Fish catch." width=500>
</center>

The <a href="/Items/Fishing#Tools" target="_blank">tools</a>, <a href="/Items/Fishing#Baits" target="_blank">baits</a>, <a href="/Items/Fishing#Buckets" target="_blank">buckets</a>, and <a href="/Items/Fishing/Creatures" target="_blank">creatures</a> you'll use and find while fishing are not like other items in Dank Memer. They won't enter your normal Dank `/inventory`, and instead are exclusively used within the fish commands. Visit <a href="/Items/Fishing" target="_blank">the fishing item</a> page to see a complete list of fishing-related items and creatures.

Each tool and bait you use has a limited number of uses, but you can always use your bare hands to fish. Bare hands cannot catch items or bosses, though, unless you upgrade the Zen Hands skill.

Once you begin fishing, you'll see one or more shadows in the water. 

<center>

  ![fishing_shadows.png](/bot-features/fishing/fishing_shadows.png)
  
</center>
  
If there is only one shadow, it is guaranteed to be an item or creature. If you see more than one shadow, however, it can be an item, a creature, or a mine. If you look at the image above, you can see the shadow on the right has spiked points coming out of it and it has a slightly clearer shape. This tells you it is the mine and you want to select the other shadow to catch.

Move your tool to the shadow you want and click catch to pull something from the water. While fishing, you have one minute to fish before the catch will get away.

If you want to shorten the time between fishing, decrease the number of mines, or improve the shape of the shadows so you can see what you are catching, there are skills you can upgrade to help in <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishSkills" target="_blank">/fish skills</a>.

<br>

### Locations {: #FishLocations}
Each location has a different set of possible <a href="/Items/Fishing/Creatures" target="_blank">creatures</a> you can catch there, as well as a different group of <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing#FishNPCs" target="_blank">NPCs</a> who like to visit it. There are also some locations that may be exclusive holiday spots that are only available for a limited time. To complete a location page in `/fish guide`, you must catch one of each creature possible at the location and meet each NPC possible at the location. In order to catch one of the <a href="/Items/Fishing/Creatures#Bosses" target="_blank">boss creatures</a>, you must first catch every other possible creature. 

Traveling to a different location takes 60 minutes by default, but you can speed up the process by using gems to fast travel.

| Location | Creatures |  NPCs |
|:--------:|:------:|:------:|
|Camp Guillermo  <img src="/bot-features/fishing/campguillermo.avif" alt="Camp Guillermo" width="800"> <br> Freshwater {: #CampGuillermo} | Bass, Koi, Crappie, Guppy, Minnow, Bluegill, Goldfish <br> BOSS: Aspidochelone | Margaux, Chet, Zara |
|Crypt Keeper's Pond <br> <img src="/bot-features/fishing/cryptkeeperspond.avif" alt="Crypt Keeper's Pond" width="800"> <br>  Freshwater, <br> Exclusive Halloween Location {: #CryptKeepersPond}  | Ghost Fish, Zombie Fish, Spectral Fish, Electric Eel, Skeleton Fish, Piranha <br> BOSS: Gorgolox | None |
|Mystic Pond  <br> <img src="/bot-features/fishing/mysticpond.avif" alt="Mystic Pond" width="800"> <br> Freshwater, <br> Only available Tuesday and Saturday {: #MysticPond} | Spectral Fish, Guppy, Koi, Flying Fish, Goldfish, Crayfish <br> BOSS: Vodyanoy | ???? ???? (Mysterious Figure)|
|Underwater Sanctuary  <br> <img src="/bot-features/fishing/underwatersanctuary.avif" alt="Underwater Sanctuary" width="800"> <br> Saltwater {: #UnderwaterSanctuary}  | Sardine, Cod, Marlin, Barracuda, Giant Squid, Tuna, Mahi Mahi, Swordfish, Salmon <br> BOSS: Leviathan | Zara, Chet, Samuel |
|Vertigo Beach <br> <img src="/bot-features/fishing/vertigobeach.png" alt="Vertigo Beach" width="800"> <br> Saltwater {: #VertigoBeach} | Shrimp, Butterfly Fish, Pufferfish, Starfish, Hammerhead Shark, Sardine, Cod, Jellyfish, Flounder <br> BOSS: Kraken, Charybdis | Margaux, Chad, Zara |
|Wily River <br> <img src="/bot-features/fishing/wilyriver.avif" alt="Wily River" width="800"> <br> Freshwater {: #WilyRiver} | Rainbow Bass, Electric Eel, Catfish, Crayfish, Red Arowana, Piranha, Golden Dorado, Salmon <br> BOSS: Jormungandr | Chad, Samuel, Zara |

<br>

### NPCs {: #FishNPCs}
J

| NPC | Image | Description |  Location(s) |
|:--------:|:------:|:------:|:------:|
| ???? "Mysterious Figure" ???? | <img src="/bot-features/fishing/npc_mysterious_figure.png" alt="Mysterious Figure" width="200">| Is a bit odd and always wears a hood. Says a lot of ominous things. | Mystic Pond |
| Chad "The Giga" Erningway | <img src="/bot-features/fishing/npc_chad_erningway.png" alt="Chad Erningway" width="200">| Likes working out, fishing, and is surprisingly nice. Doesn't like bullies. | Vertigo Beach, Wily River |
| Chet "Crypto Bro" Sterling | <img src="/bot-features/fishing/npc_chet_sterling.png" alt="Chet Sterling" width="200"> | Likes money, making money, and hearing himself talk. | Camp Guillermo, Underwater Sanctuary |
| Marguax "Robbie" Handler | <img src="/bot-features/fishing/npc_margaux_handler.avif" alt="Margaux Handler" width="200">| Is new to real life, and still learning about the world. Likes making friends and trying new things. | Camp Guillermo, Vertigo Beach |
| Samuel "Tired Father" Booker | <img src="/bot-features/fishing/npc_samuel_booker.png" alt="Samuel Booker" width="200"> | Loves his family, woodworking, and meeting new people. | Underwater Sanctuary, Wily River |
| Zara "Fisherwoman" Grey | <img src="/bot-features/fishing/npc_zara_grey.png" alt="Zara Grey" width="200"> | Loves fishing, being outdoors, and helping people. | Camp Guillermo, Underwater Sanctuary, Vertigo Beach, Wily River |


<br>

## Fishing Guidebook 
The fishing guide book available in `/fish guide` is one of the most useful tools for fishing. The guidebook gives you information about each creature, location, NPC, tool, and bait available. The guide also lists out all of the skill challenges you can complete, and has a summary page that shows your overall fishing progress.

To complete the guidebook and earn the gold fishing badge, you must fill in all the missing information. Find every creature and every variant, unlock the complete time available for each creature, meet every NPC, and meet every NPC at each location. All shadows and question marks must be filled in before your guide will count as being completed.

See more information about what each page of the guidebook shows <a href="
/Bot-features/Currency-Commands/Grind-Commands/Fishing/Guide" target="_blank">here. </a>


## Fish Leaderboard {: #FishLeaderboard}
Every day there is a special competition for all users to compete to be the top of a few leaderboards for fishing. At the start of a new UTC day, one location, one npc, and three fish are chosen for the competition.

The new choices are announced each day in the Dank Memer Community server, or you can see them by doing the `/fish leaderboards` command.
<br>
<center>
  <img src="/bot-features/fishing/fish_leaderboards.png" alt="Fish leaderboard" width="300">
  </center>

The scores on each leaderboard are not just the number of interactions you've had with an NPC or the number of fish you've caught, and involve a complex combination of stats. 

For example, to top the location leaderboard, it takes into account the number of fish you've caught at that location, but the quality of the fish matters too, and the person who catches the largest fish of the day has a big advantage.

For NPC leaderboards, the number of interactions you have with an NPC on that day does help, but also your overall reputation and how the NPC feels about you.


## Fish Skills and Upgrades {: #FishSkills}
The new fishing system comes with a new skill system as well. In the /fish guide there are Skill Challenges you can complete to earn a Skill Point. Skill Points can be used with the /fish skills command. There are a variety of skills you can upgrade to help you fish easier and make money money. For example, several skills in the economy section increase the coins or tokens you can earn when selling fish.

Other skills help improve your tools, shorten cooldowns, and increase NPC interactions. There is even a skill that unlocks an idle fishing machine.

### Idle Fishing {: #FishIdle}
The idle fishing machine is a machine that will fish for you while you are away from the keyboard. You can unlock this machine by upgrading the AFK skill in the science category.

<br>
<center>
  <img src="/bot-features/fishing/fish_idle.png" alt="Fish leaderboard" width="400">
  </center>

Once unlocked, the idle machine will automatically fish for you every 30 minutes and attempt to catch a fish. It is not guaranteed it will catch something, though, and it will continue to operate every 30 minutes until the storage space is full. When it is, you will be notified and have until the next catch to keep it going before it stops.

You can decrease the time between fishing attempts and increase the storage by continuing to upgrade the AFK skill. The machine will fish at all available locations for you, so it can catch a variety of fish, including bosses.

## Fish Tank {: #FishTank}
If you want to save a few of your favorite fish, you can put them in your fish tank. To put a fish in your tank, use the `/fish buckets` command. Select a bucket, then a fish, and click move. To remove a fish from your tank, use the `/fish tank` command. Press the manage button, select a fish, and click remove.

<br>
<center>
  <img src="/bot-features/fishing/fish_tank.webp" alt="Fish Tank" width="400">
  </center>

You can also get decorations to put in your fish tank from the `/fish season` and `/fish shop`. Your tank can hold a limited number of fish and decorations, but if you upgrade the Aquarium Keeper skill, you can increase what the tank can hold.

You can see a full list of the possible decorations so far <a href="
/Items/Fishing#Decorations" target="_blank">here. </a>


---

<body>
  <details closed>
    <summary style="background-color:#196b2f; color:#F5F5F5; font: 14px Roboto; padding: 8px;">Browse Items</summary>
      <div style="text-align: center;">  
      <p style="font: 12px Roboto; padding: 0 8px 3px 8px;">
          <a href="/Items/Collectables" target="_blank">Collectables</a> &#x2022; <a href="/Items/Consumables" target="_blank">Consumables</a> &#x2022; <a href="/Items/Drops" target="_blank">Drops</a> &#x2022; <a href="/Items/Lootboxes" target="_blank">Lootboxes</a> &#x2022; <a href="/Items/Packs" target="_blank">Packs</a> &#x2022; <a href="/Items/Power-ups" target="_blank">Power-ups</a> &#x2022; <a href="/Items/Sellables" target="_blank">Sellables</a> &#x2022; <a href="/Items/Tools" target="_blank">Tools</a>
        </p>
         </div>
    </details>
</body>

<body>
  <details closed>
    <summary style="background-color:#196b2f; color:#F5F5F5; font: 14px Roboto; padding: 8px;">Explore Commands</summary>
    <details>
      <summary style="background-color:#72ad70; color:#000000; font: 12px Roboto; padding: 8px;">Currency Commands</summary>
      <div style="text-align: center;"> 
      <p style="font: 12px Roboto; padding: 0 8px 3px 8px;"> <a href="/Bot-features/Currency-Commands/Achievements" target="_blank">Achievements</a> &#x2022; <a href="/Bot-features/Currency-Commands/Advancements" target="_blank">Advancements - (</a> <a href="/Bot-features/Currency-Commands/Advancements#LevelRewards" target="_blank">Levels</a>, <a href="/Bot-features/Currency-Commands/Advancements#Omega" target="_blank">Omega</a>, <a href="/Bot-features/Currency-Commands/Advancements#Prestige" target="_blank">Prestige</a>,  <a href="/Bot-features/Currency-Commands/Advancements/Upgrades" target="_blank">Upgrades</a>, <a href="/Bot-features/Currency-Commands/Advancements#Vote" target="_blank"> Vote</a>) <br> <a href="/Bot-features/Currency-Commands/Adventure" target="_blank">Adventure</a> &#x2022; <a href="/Bot-features/Currency-Commands/Badges" target="_blank">Badges</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Balance" target="_blank">Balance</a> &#x2022; <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Bankrob" target="_blank">Bankrob</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Beg" target="_blank">Beg</a> &#x2022; <a href="/Bot-features/Currency-Commands/Bundles" target="_blank">Bundles</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Compare" target="_blank">Compare</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands/Crafting" target="_blank">Craft</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Crime" target="_blank">Crime</a> <br><a href="/Bot-features/Currency-Commands/Basic-Commands#Currencylog" target="_blank">Currencylog</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Daily" target="_blank">Daily</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Deposit" target="_blank">Deposit</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Dig" target="_blank">Dig</a> &#x2022; <a href="/Items/Drops" target="_blank">Drops</a> &#x2022; <a href="/Bot-features/Currency-Commands/Farm" target="_blank">Farm</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing" target="_blank">Fish</a> &#x2022; <a href="/Bot-features/Currency-Commands/Friends" target="_blank">Friends</a> &#x2022; <a href="/Bot-features/Currency-Commands/Serverevents-and-Giveaways#Giveaways" target="_blank">Giveaway</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Highlow" target="_blank">Highlow</a> <br> <a href="/Bot-features/Currency-Commands/Grind-Commands#Hunt" target="_blank">Hunt</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Inventory" target="_blank">Inventory</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Item" target="_blank">Item</a> &#x2022; <a href="/Bot-features/Currency-Commands/Leaderboards" target="_blank">Leaderboard</a> &#x2022; <a href="/Bot-features/Currency-Commands/Lotteries" target="_blank">Lottery</a> &#x2022; <a href="/Bot-features/Currency-Commands/Market" target="_blank">Market</a> &#x2022; <a href="/Bot-features/Currency-Commands/Marriage" target="_blank">Marriage</a> &#x2022; <a href="/Bot-features/Currency-Commands/Advancements/Upgrades#Monthly" target="_blank">Monthly</a> <br> <a href="/Bot-features/Currency-Commands/Multipliers" target="_blank">Multipliers</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Notifications" target="_blank">Notifications</a> &#x2022; <a href="/Bot-features/Currency-Commands/Pets" target="_blank">Pets</a>  &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Postmemes" target="_blank">Postmemes</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile" target="_blank">Profile</a> &#x2022; <a href="/Bot-features/Currency-Commands/Quests" target="_blank">Quests</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Remove" target="_blank">Remove</a> &#x2022; <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Rob" target="_blank">Rob</a> <br> <a href="/Bot-features/Currency-Commands/Grind-Commands#Scratch" target="_blank">Scratch</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Search" target="_blank">Search</a> &#x2022; <a href="/Bot-features/Currency-Commands/Serverevents-and-Giveaways#Serverevents" target="_blank">Serverevents</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Shop" target="_blank">Shop</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile#Showcase" target="_blank">Showcase</a> &#x2022; <a href="/Bot-features/Currency-Commands/Skins" target="_blank">Skins</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Stream" target="_blank">Stream</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Taxcalc" target="_blank">Taxcalc</a> <br> <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile#Titles" target="_blank">Title</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Use" target="_blank">Use</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Vacation" target="_blank">Vacation</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Games-and-Wagers#Wagers" target="_blank">Wager</a> &#x2022; <a href="/About-Dank-Memer/Premium-users#Weekly" target="_blank">Weekly</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Withdraw" target="_blank">Withdraw</a> &#x2022; <a href="/Bot-features/Currency-Commands/Work" target="_blank">Work</a> </p>
      </div>
    </details>
    <details>
      <summary style="background-color:#72ad70; color:#000000; font: 12px Roboto; padding: 8px;">Fun, Game, and Image Commands</summary>
      <div style="text-align: center;"> 
      <p style="font: 12px Roboto; padding: 0 8px 3px 8px;"><a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Ball" target="_blank">8ball</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Animals" target="_blank">Animals</a> &#x2022;  <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Clap" target="_blank">Clap</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Games-and-Wagers#Fight" target="_blank">Fight</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Games-and-Wagers#Games" target="_blank">Game</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Image" target="_blank">Image</a> &#x2022;  <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Meme" target="_blank">Meme</a> &#x2022;  <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Rate" target="_blank">Rate</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Trivia" target="_blank">Trivia</a> &#x2022;  <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Xkcd" target="_blank">Xkcd</a> </p>
      </div>
    </details>
    <details>
      <summary style="background-color:#72ad70; color:#000000; font: 12px Roboto,sans-serif; padding: 8px;">Utility and Config Commands</summary>
      <div style="text-align: center;"> 
      <p style="font: 12px Roboto; padding: 0 8px 3px 8px;">
        <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Alert" target="_blank">Alert</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Audit" target="_blank">Audit</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Automeme" target="_blank">Automeme</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Block" target="_blank">Block</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Disableuse" target="_blank">Disableuse</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Flow" target="_blank">Flow</a> &#x2022; <a href="/Resources/help" target="_blank">Help</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Invite" target="_blank">Invite</a> &#x2022; <a href="/About-Dank-Memer/About-the-bot#Partners" target="_blank">Partners</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Ping" target="_blank">Ping</a> <br> <a href="/About-Dank-Memer/Premium-users#PremiumCommands" target="_blank">Premium</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Reminders" target="_blank">Reminder</a> &#x2022; <a href="/Resources/Reports-and-appeals" target="_blank">Report</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#ServerSettings" target="_blank">Serversettings</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Settings" target="_blank">Settings</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Usage" target="_blank">Usage</a> &#x2022; <a href="/About-Dank-Memer/Vote" target="_blank">Vote</a></p>
      </div>
    </details>
  </details>
</body>
    
    


<body>
  <details closed>
    <summary style="background-color:#196b2f; color:#F5F5F5; font: 14px Roboto, sans-serif; padding: 8px;">Resources</summary>
      <div style="text-align: center;">  
      <p style="font: 12px Roboto, sans-serif; padding: 0 8px 3px 8px;"><a href="/Resources/FAQ" target="_blank">Frequently Asked Questions (FAQ) </a> &#x2022;  <a href="/About-Dank-Memer/Bot-rules" target="_blank">Bot Rules</a> &#x2022; <a href="/Resources/Bot-tutorials" target="_blank">Bot Tutorials</a> <br> <a href="/Resources/Changelog" target="_blank">Changelog</a> &#x2022; <a href="/Resources/Community-made-tools" target="_blank">Community Made Tools</a> <br> <a href="/Resources/Dank-Blog" target="_blank">Dank Blog</a> &#x2022; <a href="/Resources/help" target="_blank">Help Commands</a> &#x2022; <a href="/Resources/Reports-and-appeals" target="_blank">Reports and Appeals</a>
        </p>
         </div>
    </details>
</body>
