---
title: Config Commands
description: Learn more about commands to help configure settings, serversettings, audit servers, block users, manage flows, access premium, and more.
published: true
date: 2023-07-29T12:08:40.317Z
tags: premium, server settings, audit, automeme, config commands, alert, block, disableuse, flow, serversettings, settings, config, dank memer wiki, dankmemer wiki
editor: markdown
dateCreated: 2023-05-31T09:02:15.887Z
---

# Config Commands
These commands help you configure Dank Memer to your preferences, and can help you manage differnet parts of the bot. Config Commands include:

- [Alert](/Bot-features/Utility-and-Config-Commands/Config-Commands#Alert)
- [Audit](/Bot-features/Utility-and-Config-Commands/Config-Commands#Audit)
- [Automeme](/Bot-features/Utility-and-Config-Commands/Config-Commands#Automeme)
- [Block](/Bot-features/Utility-and-Config-Commands/Config-Commands#Block)
- [Disableuse](/Bot-features/Utility-and-Config-Commands/Config-Commands#Disableuse)
- [Flow](/Bot-features/Utility-and-Config-Commands/Config-Commands#Flow)
- [Premium](/Bot-features/Utility-and-Config-Commands/Config-Commands#Premium)
- [Serversettings](/Bot-features/Utility-and-Config-Commands/Config-Commands#ServerSettings)
- [Settings](/Bot-features/Utility-and-Config-Commands/Config-Commands#Settings)

## Alert {: #Alert}
When a significant change is released by the bot developers, or there is an important announcement, Dank Memer sends out an alert. You can use the `/alert` command to show new alerts from the developers about updates or announcements. Another way to stay updated on the latest changes is with the <a href="/Resources/Changelog" target="_blank">Changelog</a>.

<br>
<center>
<img src="/alerts_example.png" alt="alerts example.">
</center>
<br>


## Audit {: #Audit}
You can check the `/audit` logs in any server to who has made changes to the [/serversettings](/Bot-features/Utility-and-Config-Commands/Config-Commands#ServerSettings) recently, as well as who has made the server <a href="/About-Dank-Memer/Premium-users" target="_blank">premium</a> recently. This can be useful to see if a server has <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Rob" target="_blank">rob</a> enabled or disabled, as well as to see if anyone is changing settings that shouldn't be changed.

**Example:**
<center>
<img src="/bot-features/settings/dmc_audit.png" alt="dmc audit.">
</center>

## Automeme {: #Automeme}
<a href="/About-Dank-Memer/Premium-users" target="_blank">Premium users who are $5 subscribers or above </a> can <a href="/About-Dank-Memer/Premium-users#PremiumServers" target="_blank">make a server premium</a> to give users access to the <a href="/About-Dank-Memer/Premium-users#Weekly" target="_blank">/weekly</a> command and the server the ability to use automemes. The `/automeme` feature can be used to automatically post memes in a designated channel every X minutes or hours, depending on the time chosen.

<center>
  
![automeme.png](/bot-features/config/automeme.png)  
  
</center>


Once the server has been made premium, ask a server admin to go to the server settings and click integrations. Under integrations, there is an option to view & create webhooks.
<br>
<center>
<img src="/bot-features/premium/webhook_integrations.png" alt="webhook integrations." width=777>
</center>

Create a new webhook for your server, then click the down arrow next to the webhook’s name so it shows the options for the webhook. Here you can choose the channel it is supposed to be for, change its name, and grab the webhook URL. The webhook URL is required for the `/automeme set` command. Once everything is set the way you want, copy the webhook URL and exit out of the server settings.

Finish setting up automeme by going to the channel you want the memes to be automatically posted in and do the `/automeme set` command.

<center>
  
![automeme_set.png](/bot-features/premium/automeme_set.png)
  
</center>
  
Put the webhook in the command where asked, and set the interval to how often you want memes to be posted in minutes. Once you’ve filled out the info and submitted the command, memes will begin to post automatically every X minutes, based on the interval you chose.

You can change the interval in between memes by running the `/automeme set` command again and entering a new interval time. To stop the automemes from posting, use the `/automeme remove` command in the channel where automeme is active.

A more detailed guide on setting up automemes can be found in <a href="https://dankmemer.lol/tutorial/premium-redemption" target="_blank">this blog post</a>.

You can read more about other premium benefits <a href="/About-Dank-Memer/Premium-users" target="_blank">here</a>.

## Block {: #Block}
You can block people on the bot by using the `/block` command. This stops others from interacting with you in various ways. 
If you blocked a user, they can no longer:
- Send you messages via the <a href="/Items/Tools#CellPhone" target="_blank">Cell Phone</a> or a <a href="/Items/Consumables#Postcard" target="_blank">Postcard</a>;
- Try to use an engagement ring on you to start a <a href="/Bot-features/Currency-Commands/Marriage" target="_blank">marriage</a>;
- Add you as a <a href="/Bot-features/Currency-Commands/Friends" target="_blank">friend</a> on the bot;
- Try to start <a href="/Bot-features/Fun-Games-Image/Games-and-Wagers#Games" target="_blank">games</a> or <a href="/Bot-features/Fun-Games-Image/Games-and-Wagers#Wagers" target="_blank">wagers</a> with you.

Users will still be able to use items on you if you are blocked, so it cannot be used by <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Rob" target="_blank">robbers</a> as a way to stop victims from using <a href="/Items/Tools#UsedDiaper" target="_blank">Used Diapers</a> or a <a href="/Items/Tools#BoxofSand" target="_blank">Box of Sand</a> on them.

<center>
  
![block.png](/bot-features/config/block.png)  
  
</center>

## Disableuse {: #Disableuse}
The `/disableuse` command gives server owners and admins a way to disable the use of certain commands for certain channels, roles, the entire server, or a specific user. 

Some servers do this to create custom channels, like a channel for opening <a href="/Items/Lootboxes" target="_blank">lootboxes</a>, or to stop people from ruining <a href="/Bot-features/Currency-Commands/Serverevents-and-Giveaways#Serverevents" target="_blank">server heists</a> with items like the <a href="/Items/Tools#UsedDiaper" target="_blank">Used Diapers</a>.
<br>

| Command | Does what? |
|:------:|:----:|
| `/disableuse channel` | Disable use for a channel |
| `/disableuse role` | Disable use for a role |
| `/disableuse server` | Disable use for a server | 
| `/disableuse user` | Disable use for a user |
| `/disableuse list` | List of all disable use rules |
| `/disableuse remove` | Remove a disabled use rule from the `/disableuse list` | 

<br>

## Flow {: #Flow}
The `/flow` command can be used to manage and activate your flows. You can use flows to make your grinding experience a lot easier! You don't even have to type the commands yourself anymore, you can just create/import/edit a flow and once you start it with `/flow start`, you can run commands with the push of a button.

Read the in-depth guide to flows <a href="https://dankmemer.lol/tutorial/flows" target="_blank">here</a> to learn how to record a flow, import a flow, and more.

<center>
<img src="/bot-features/grinding/flows2.png" alt="Flow list.">
</center>

### Editing Flows
It is possible to edit **your own created** flows with te "Edit this Flow" button after using `/flow list`. 

- If someone shared a flow with you, then you can **not** edit that flow, only the original creator can.
- If the owner of a flow edits it, the flow gets changed for **everyone** who it has been shared to.

#### Flow Conditions
While editing flows, you can add certain conditions for each command in that flow.
The conditions for these commands **only** work if you click the "Run" button while grinding, not if you skip a flow command.

The command you're putting conditions for will have a little arrow next to it like shown below.

<center>

![flows_editing_conditions.png](/bot-features/grinding/flows_editing_conditions.png)

</center>

You can use the arrows next to the remove button to change which command in your flow you'd add a condition to.

A condition is built out of 3 types of attributes and will always look like `(if Requirement + Operator + Number)`, for example: `(if pocket < 1,000,000)`.

<center> 
  
| Option | Type | What is it? |
|:----:|:----:|:----:|
| Pocket | Requirement | Coins in your pocket |
| Cooldown (seconds) | Requirement | Command cooldown left |
| < | Operator | Smaller than |
| > | Operator | Greater than |
| = | Operator | Equals |
| 0 | Number | 0 |
| 10 | Number | 10 |
| 30 | Number | 30 |
| 60 | Number | 60 |
| 120 | Number | 120 |
| 100 | Number | 100 |
| 1000 | Number | 1000 |
| 10,000 | Number | 10,000 |
| 100,000 | Number | 100,000 |
| 1000,000 | Number | 1000,000 |

  </center>

## Premium (Formerly /Donor) {: #Premium}
The `/premium` commands are used by <a href="/About-Dank-Memer/Premium-users" target="_blank">premium users</a> to check on their premium status, to add or remove a server as premium, and to look at information about premium rewards. 

You can read more about how to become premium, the perks, and the commands, <a href="/About-Dank-Memer/Premium-users" target="_blank">here</a>.

<center>
  
![premium_status.png](/bot-features/config/premium_status.png)  
  
</center>

## Serversettings {: #ServerSettings}
The `/serversettings` command is used by server owners and admins to help control Dank Memer's settings within the server on top of Discord's integration settings. If you need help understanding how to set up Dank Memer, there are two guides that are useful:
- <a href="https://dankmemer.lol/tutorial/set-up-dank-memer" target="_blank">Dank Memer Setup Tutorial</a>
- <a href="https://support.discord.com/hc/en-us/articles/4644915651095-Command-Permissions" target="_blank">Discord's Guide to Command Permissions</a> 

When using the `/serversettings` command, there are several options you can manage.

| Setting option | Does what? |
|:------:|:----:|
| Bank Robbing | Enable or disable bankrobbing in your server. <br> NOTE: **Only** the owner of the server can change this setting. |
| Events Manager | Add/edit a role through a role select menu that will be in charge of managing <a href="/Bot-features/Currency-Commands/Serverevents-and-Giveaways#Serverevents" target="_blank">/serverevents</a>  in your server. <br> NOTE: **Only** the owner of the server can change this setting. |
| Random Events | Enable or disable random events in your server. |
| Rob Protection | Enable or disable the rob protection in your server, which makes it that members who joined within the last day can not rob anyone for 24 hours. |
| Robbing | Enable or disable robbing in your server. <br> NOTE: **Only** the owner of the server can change this setting. |

If the information above does not answer your questions, you can also ask for help in the <a href="https://discord.com/invite/dankmemerbot" target="_blank">Dank Memer Support Server</a>.

## Settings (for Users) {: #Settings}
The `/settings` command gives users the ability to change their personal settings for the bot, such as what <a href="/Bot-features/Currency-Commands/Basic-Commands#Notifications" target="_blank">notifications</a> they receive, passive mode, their <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile" target="_blank">profile</a>, and more.

The following are the settings that can be changed:
| Setting option | Does what? |
|:------:|:----:|
| Compact Mode | Enable or disable compact mode. Compact mode makes your <a href="/Bot-features/Currency-Commands/Basic-Commands#Inventory" target="_blank">inventory</a> and the <a href="/Bot-features/Currency-Commands/Basic-Commands#Shop" target="_blank">/shop view</a> page smaller, so they fit more info in less space.|
| Confirmation Number | If you have <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Warning" target="_blank">warning confirmations</a> enabled, the number you put here will be the value for when you'll get a confirmation message before selling and buying items or sharing things with friends. The value can be set between 1 and 2,000,000,000. | 
| <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile#Customization" target="_blank">Customize Your Profile</a> | Edit your profile and personalize it to your own liking! You can buy advanced profile customization in <a href="/Bot-features/Currency-Commands/Advancements/Upgrades" target="_blank">/advancements upgrades</a>. | 
| DM <a href="/Bot-features/Fun-Games-Image/Games-and-Wagers#Fight" target="_blank">Fight</a> Logs {: #DMLogs} | Enable or disable whether you receive a DM of fight logs after a fight. |
| Ephemeral Notifications | Ephemeral messages are pop-up notifications only you can see that you can receive when running commands. Use this setting to customize which type of ephemeral messages you'd like to receive. |
| Expose IDs | When you enable this you'll be able to see User ID's in leaderboards, fighting ranking, global/server giveaways and market accept notifications. |
| Hide Public | Enable or disable yourself being shown on <a href="/Bot-features/Currency-Commands/Leaderboards" target="_blank">leaderboards</a>. Having this set to true hides your username from the leaderboards, so it shows you only as "Hidden User." |
| <a href="/Bot-features/Currency-Commands/Advancements#LevelRewards" target="_blank">Level Up</a> Notifications | Enable, disable, or change your level-up notifications. Notifications are sent to DMs, and you can customize what type of notifications you want to see, such as only one every minute, every level, or only for rewards.| 
| <a href="/Bot-features/Currency-Commands/Advancements/Upgrades#NetWorthSort" target="_blank">Net Worth Sort</a> | Once you purchase the <a href="/Bot-features/Currency-Commands/Advancements/Upgrades#NetWorthSort" target="_blank">Net Worth Sort</a> upgrade in <a href="/Bot-features/Currency-Commands/Advancements/Upgrades" target="_blank">/advancements upgrades</a>, you can use this to disable it and put your inventory back into alphabetical order. | 
| Passive | Enable or disable passive mode. When passive mode is enabled, you cannot be <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Rob" target="_blank">robbed</a> or <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Bankrob" target="_blank">bankrobbed</a> or do them on others, use items on others or have them used on you, and play <a href="/Bot-features/Fun-Games-Image/Games-and-Wagers#Wagers" target="_blank">/wager</a> games. Passive expires if you don't run commands for 5 days. |  
| Recurring Income Reminders | Enable or disable whether or not you'll get a notification about being able to run <a href="/Bot-features/Currency-Commands/Basic-Commands#Daily" target="_blank">/daily</a>, <a href="/About-Dank-Memer/Premium-users#Weekly" target="_blank">/weekly</a>, or <a href="/Bot-features/Currency-Commands/Advancements/Upgrades#Monthly" target="_blank">/monthly</a> again. Notifications come based on when you last used the commands. |
| Warning Confirmations {: #Warning} | Enable or disable whether or not you'll get a confirmation warning before sending a large number of coins or items or making an expensive purchase. |

<br>
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