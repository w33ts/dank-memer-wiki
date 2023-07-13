---
title: Serverevents and Giveaways
description: Learn about global giveaways you can do on your own and serverevents and giveaway features.
published: true
date: 2023-07-13T23:00:36.246Z
tags: serverevents, raffles, giveaways, split or steal, events
editor: markdown
dateCreated: 2023-06-02T18:52:08.435Z
---

# Serverevents and Giveaways


## Global giveaways {: #Giveaways}
The `/giveaway` command lets you create a **global** giveaway that anyone can join until the timer for it times out.

You can create a coins giveaway with the `/giveaway create coins` command.
You can create an item giveaway with the `/giveaway create items` command.

<center>

![giveaway_create_coins.png](/bot-features/events/giveaway_create_coins.png)
  
</center>

Keep in mind, the value of your giveaway has to be **at least** 2,000,000. 
For items this means the **average market value** of your item is being taken.

<center> 
  
![giveaway_requirement.png](/bot-features/events/giveaway_requirement.png)
  
</center>

You can use the `/giveaway view` command to view current global giveaways. This shows you 1 random global giveaway, where you get the option to either the giveaway, show the next giveaway or do both.

## Serverevents {: #Serverevents}
In order to run an event in your server, you need to have a server with **at least** 50 players in it. 
Going back below 50 members after donating items to your server pool does not make the items/coins from the pool vanish! They stay in the `/serverevents pool`, but will be unaccesable until your server reaches 50+ members again.

Keep in mind, using alts to influence the server count is **NOT** allowed and can get you punished.

**Only** the owner of a server can change the role for managing server events under `/serversettings`.

Each server has a `/serverevents pool` which will contain all the items donated to that particular server.

<center>

![serverevents_pool.png](/bot-features/events/serverevents_pool.png)
  
</center>

To donate to a serverpool, you can use the `/serverevents donate` command, this lets you donate either items or coins.
You can check the recent server donations with the `/servervents donations` command.

If items were to be missing from your server pool, you can check the logs by using the `/serverevents logs` command.

There are 4 different types of events:
- Giveaways (`/serverevents run giveaway`)
- Rafles (`/serverevents run raffle`)
- Server bankrobs (`/serverevents run serverbankrob`)
- Split or Steal (`/serverevents run splitorsteal`)

After an event has been hosted, you can pay the winner(s) out with the `/serverevents payout` command.

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
      <p style="font: 12px Roboto; padding: 0 8px 3px 8px;"> <a href="/Bot-features/Currency-Commands/Achievements" target="_blank">Achievements</a> &#x2022; <a href="/Bot-features/Currency-Commands/Advancements" target="_blank">Advancements - (</a> <a href="/Bot-features/Currency-Commands/Advancements#LevelRewards" target="_blank">Levels</a>, <a href="/Bot-features/Currency-Commands/Advancements#Omega" target="_blank">Omega</a>, <a href="/Bot-features/Currency-Commands/Advancements#Prestige" target="_blank">Prestige</a>, <a href="/Bot-features/Currency-Commands/Advancements/Upgrades" target="_blank">Upgrades</a>, <a href="/Bot-features/Currency-Commands/Advancements#Vote" target="_blank"> Vote</a>) <br> <a href="/Bot-features/Currency-Commands/Adventure" target="_blank">Adventure</a> &#x2022; <a href="/Bot-features/Currency-Commands/Badges" target="_blank">Badges</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Balance" target="_blank">Balance</a> &#x2022; <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Bankrob" target="_blank">Bankrob</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Beg" target="_blank">Beg</a> &#x2022; <a href="/Bot-features/Currency-Commands/Bundles" target="_blank">Bundles</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Compare" target="_blank">Compare</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Craft" target="_blank">Craft</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Crime" target="_blank">Crime</a> <br><a href="/Bot-features/Currency-Commands/Basic-Commands#Currencylog" target="_blank">Currencylog</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Daily" target="_blank">Daily</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Deposit" target="_blank">Deposit</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Dig" target="_blank">Dig</a> &#x2022; <a href="/Items/Drops" target="_blank">Drops</a> &#x2022; <a href="/Bot-features/Currency-Commands/Farm" target="_blank">Farm</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Fish" target="_blank">Fish</a> &#x2022; <a href="/Bot-features/Currency-Commands/Friends" target="_blank">Friends</a> &#x2022; <a href="/Bot-features/Currency-Commands/Serverevents-and-Giveaways#Giveaways" target="_blank">Giveaway</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Highlow" target="_blank">Highlow</a> <br> <a href="/Bot-features/Currency-Commands/Grind-Commands#Hunt" target="_blank">Hunt</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Inventory" target="_blank">Inventory</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Item" target="_blank">Item</a> &#x2022; <a href="/Bot-features/Currency-Commands/Leaderboards" target="_blank">Leaderboard</a> &#x2022; <a href="/Bot-features/Currency-Commands/Lotteries" target="_blank">Lottery</a> &#x2022; <a href="/Bot-features/Currency-Commands/Market" target="_blank">Market</a> &#x2022; <a href="/Bot-features/Currency-Commands/Marriage" target="_blank">Marriage</a> &#x2022; <a href="/Bot-features/Currency-Commands/Advancements/Upgrades#Monthly" target="_blank">Monthly</a> <br> <a href="/Bot-features/Currency-Commands/Multipliers" target="_blank">Multipliers</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Notifications" target="_blank">Notifications</a> &#x2022; <a href="/Bot-features/Currency-Commands/Pets" target="_blank">Pets</a>  &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Postmemes" target="_blank">Postmemes</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile" target="_blank">Profile</a> &#x2022; <a href="/Bot-features/Currency-Commands/Quests" target="_blank">Quests</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Remove" target="_blank">Remove</a> &#x2022; <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Rob" target="_blank">Rob</a> <br> <a href="/Bot-features/Currency-Commands/Grind-Commands#Scratch" target="_blank">Scratch</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Search" target="_blank">Search</a> &#x2022; <a href="/Bot-features/Currency-Commands/Serverevents-and-Giveaways#Serverevents" target="_blank">Serverevents</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Shop" target="_blank">Shop</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile#Showcase" target="_blank">Showcase</a> &#x2022; <a href="/Bot-features/Currency-Commands/Skins" target="_blank">Skins</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Stream" target="_blank">Stream</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Taxcalc" target="_blank">Taxcalc</a> <br> <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile#Titles" target="_blank">Title</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Use" target="_blank">Use</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Vacation" target="_blank">Vacation</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Games-and-Wagers#Wagers" target="_blank">Wager</a> &#x2022; <a href="/About-Dank-Memer/Premium-users#Weekly" target="_blank">Weekly</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Withdraw" target="_blank">Withdraw</a> &#x2022; <a href="/Bot-features/Currency-Commands/Work" target="_blank">Work</a> </p>
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
        <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Alert" target="_blank">Alert</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Audit" target="_blank">Audit</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Automeme" target="_blank">Automeme</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Block" target="_blank">Block</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Disableuse" target="_blank">Disableuse</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Flow" target="_blank">Flow</a> &#x2022; <a href="/Resources/help" target="_blank">Help</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Invite" target="_blank">Invite</a> &#x2022; <a href="/About-Dank-Memer/About-the-bot#Partners" target="_blank">Partners</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Ping" target="_blank">Ping</a> <br> <a href="/About-Dank-Memer/Premium-users#PremiumCommands" target="_blank">Premium</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Reminders" target="_blank">Reminder</a> &#x2022; <a href="/Resources/Reports-and-appeals" target="_blank">Report</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Reset" target="_blank">Resetmydata</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#ServerSettings" target="_blank">Serversettings</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Settings" target="_blank">Settings</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Usage" target="_blank">Usage</a> &#x2022; <a href="/About-Dank-Memer/Vote" target="_blank">Vote</a></p>
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