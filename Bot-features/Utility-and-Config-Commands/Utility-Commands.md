---
title: Utility Commands
description: Learn about basic utility commands available in Dank Memer, including invite, ping, reminder, resetmydata, and usage.
published: true
date: 2023-06-05T07:56:49.372Z
tags: invite, ping, reminder, resetmydata, usage, reminders, reminder every, reset my data, reset data
editor: markdown
dateCreated: 2023-05-31T06:41:51.720Z
---

# Utility Commands
Utility commands are useful tools for users. Some of the basic utility commands are things like the ability to set reminders for yourself, an invite command that gives you access to important Dank Memer links, and even a command to see your complete command usage stats. 

- <a href="/Resources/help" target="_blank">Help</a>
- [Invite](/Bot-features/Utility-and-Config-Commands/Utility-Commands#Invite)
- <a href="/About-Dank-Memer/About-the-bot#Partners" target="_blank">Partners</a>
- [Ping](/Bot-features/Utility-and-Config-Commands/Utility-Commands#Ping)
- [Reminder](/Bot-features/Utility-and-Config-Commands/Utility-Commands#Reminders)
- <a href="/Resources/Reports-and-appeals" target="_blank">Report</a>
- [Resetmydata](/Bot-features/Utility-and-Config-Commands/Utility-Commands#Reset)
- [Taxcalc](/Bot-features/Utility-and-Config-Commands/Utility-Commands#Taxcalc)
- [Usage](/Bot-features/Utility-and-Config-Commands/Utility-Commands#Usage)
- <a href="/About-Dank-Memer/Vote" target="_blank">Vote</a>


## Invite {: #Invite} 
The `/invite` command gives you easy access to all the important links you might need related to Dank Memer. There is a link for the <a href="https://discord.gg/memers" target="_blank">Dank Memer Community Server</a>, the <a href="https://discord.gg/dankmemerbot" target="_blank">Dank Memer Official Support Server</a>, and even <a href="/About-Dank-Memer/About-the-bot#Social" target="_blank">Dank Memer social media</a> links. There are also links to buy a <a href="/About-Dank-Memer/Premium-users" target="_blank">premium subscription</a> or to <a href="/About-Dank-Memer/Invite-the-bot" target="_blank">invite the bot</a> to a server.

<center>
  
![invite.png](/bot-features/utility/invite.png)  
  
</center>

## Ping {: #Ping}
The `/ping` command is used as a quick and easy way to see the bot's response time and how well data is transmitting. 

<center>
  
![ping.png](/bot-features/utility/ping.png)
  
</center>

## Reminders {: #Reminders}
You can create reminders by using the `/reminder` command. There are two types of reminders you can create, a one-time reminder with `/reminder add` or a recurring reminder with `/reminder every`. When it is time for the reminder to be delivered, you will receive a DM from the bot about it.

Reminders are set by default in the bot's time zone, which is UTC. However, you can alter the time zone to your own by entering that information when you set the reminder, such as entering 4pm EST. You can also use phrases like the following for time:
- "2pm"
- "hour"
- "tomorrow"
- "in 3 hours and 15 minutes"
- "4h5m"

To check your current active reminders, you can use the `/reminder list` command. If you wish to remove a reminder, you can use the `/reminder remove` command. 

<center>
  
![reminders.png](/bot-features/utility/reminders.png)  
  
</center>

Once a reminder is delivered in DMs, you will be prompted with 3 buttons:
-  Snooze: Snoozes the reminder and reminds you again in 5 minutes about it.
- Remind again: Add the same reminder to your `/reminder list` again for the **exact** same duration.
- A Link: This brings you back to your original post when you created the reminder.
<br>

### <font color =b32d2d>Recurring Reminders</font> 
You can use the `/reminder every` command to be reminded every x amount of time of something. For example: `/reminder every time:1h about:work`

There is also a limit to how many active reminders a user can have, depending on whether they are a <a href="/About-Dank-Memer/Premium-users" target="_blank">premium user</a> or not.

<br>

| Reminder Type | For Who? | Limit |
|:------:|:----:|:------:|
| Regular reminders | Non premium users | 100 |
| Regular reminders | Premium users | Unlimited |
| Recurring reminders | Non premium users | 5 (out of 100) |
| Recurring reminders | Premium users | Unlimited |
<br>

## Resetmydata {: #Reset}
The `/resetmydata` command is a way you can reset **all** of your progress on the bot so far. Using this command will reset all of your information, including <a href="/Bot-features/Currency-Commands/Badges" target="_blank">badges</a>, <a href="/Bot-features/Currency-Commands/Achievements" target="_blank">achievements</a>, <a href="/Bot-features/Currency-Commands/Advancements#LevelRewards" target="_blank">levels</a>, <a href="/Bot-features/Currency-Commands/Basic-Commands#Inventory" target="_blank">inventory</a>, bank, wallet, etc. The only information that will not be removed is some of your <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Usage" target="_blank">usage</a> data, which is saved for the bot staff to use as needed.  

Players can use this command when they want to quit the bot and wipe their data or if they want to have a fresh start. To reset your data, run the command and then press the button 3 times and enter RESET MY DATA in all capital letters in the text box given.

This action cannot be undone, so only reset your data if you are sure you're ready to lose everything.

<center>
  
![resetmydata.png](/bot-features/utility/resetmydata.png)  
  
</center>

## Taxcalc {: #Taxcalc}
The `/taxcalc` command is used for players to be able to calculate the tax they would have to pay for fighting with others.
The command automatically calculates your tax based on your ***own*** tax. The more wealth you have, the higher your tax will be, capping at a maximum tax rate of 13%.
<br>
<center>
  <img src="/bot-features/settings/taxcalc.png" alt="Taxcalc.">
</center>

<a href="/About-Dank-Memer/Premium-users" target="_blank">Premium users</a> bypass this and don't have to pay any tax when fighting.

## Usage {: #Usage}
The `/usage` command shows your complete command usage. Each command in the usage stats is listed by the top-level command name, so some information is grouped together. For example, instead of having two entries for `/pets view` and `/pets care`, the usage will combine them under <a href="/Bot-features/Currency-Commands/Pets" target="_blank">pets</a> .

<center>
  
![usage.png](/bot-features/utility/usage.png)  
  
</center>

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