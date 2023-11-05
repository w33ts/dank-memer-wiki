---
title: Basic Commands
description: Learn about basic Dank Memer commands, including balance, craft, currencylog, daily, deposit, inventory, item, notifications, profile, shop (gem shop), use, vacation, and withdraw.
published: true
date: 2023-11-05T02:29:19.722Z
tags: profile, basic commands, balance, craft, currencylog, daily, deposit, inventory, item, shop, use, withdraw, vacation, notifications, notification search, notification view, notification list, gem shop, dank memer wiki, dankmemer wiki, coin shop
editor: markdown
dateCreated: 2023-05-29T20:20:06.427Z
---

# Basic Commands
Here you can find all the basic commands you will need to get the best out of the bot. These commands are the ones that are the most used, and they are important for your progression in the bot and allow you to get further.
- [Balance](/Bot-features/Currency-Commands/Basic-Commands#Balance)
- <a href="/Bot-features/Currency-Commands/Basic-Commands/Crafting" target="_blank">Craft</a>
- [Currencylog](/Bot-features/Currency-Commands/Basic-Commands#Currencylog)
- [Daily](/Bot-features/Currency-Commands/Basic-Commands#Daily)
- [Deposit](/Bot-features/Currency-Commands/Basic-Commands#Deposit)
- [Inventory](/Bot-features/Currency-Commands/Basic-Commands#Inventory)
- [Item](/Bot-features/Currency-Commands/Basic-Commands#Item)
- [Notifications](/Bot-features/Currency-Commands/Basic-Commands#Notifications)
- [Profile](/Bot-features/Currency-Commands/Basic-Commands#Profile)
- [Remove](/Bot-features/Currency-Commands/Basic-Commands#Remove)
- [Shop](/Bot-features/Currency-Commands/Basic-Commands#Shop)
- [Use](/Bot-features/Currency-Commands/Basic-Commands#Use)
- [Vacation](/Bot-features/Currency-Commands/Basic-Commands#Vacation)
- [Withdraw](/Bot-features/Currency-Commands/Basic-Commands#Withdraw)

## Balance {: #Balance}
The `/balance` command can be used to check not only your wallet & bank value, but also your inventory net, market net & total net.
This command also shows you your global rank on the bot.

<br>
<center>
<img src="/bot-features/basic-commands/balance2.png" alt="balance.">
</center>

There buttons at the bottom of the balance embed message can be used to withdraw and deposit money. When using one of these buttons, the max value possible is automatically entered for you by default.

## Craft {: #Craft}

With the `/craft` command, you can craft new items from existing items that you have collected throughout the bot. Some items have multiple <a href="/Bot-features/Currency-Commands/Basic-Commands/Crafting#Recipes" target="_blank">crafting recipes</a> you can use, and there are also <a href="/Bot-features/Currency-Commands/Basic-Commands/Crafting#HolidayRecipes" target="_blank">holiday recipes</a> that are only available at limited times throughout the year. Recipes can change at any time and sometimes are removed completely.

<br>
<center>
<img src="/craft_example.png" alt="craft example." width=400>
</center>

To craft, choose the item you want to craft from the dropdown menu, then pick which recipe you want to use with the left and right arrows. Each craft takes a specific amount of time per craft to complete, and some crafts produce (or yield) more than one. The more items you craft, the longer your crafting time will be, but there are <a href="/Bot-features/Currency-Commands/Basic-Commands/Crafting#Boosts" target="_blank">boosts</a> you can activate to make things craft faster.

You can only do one craft order at a time and there is a max of 25 crafts at once. If you are already crafting something, you will see a message letting you know how long it is before it is completed when you try to craft something new. 

If you choose to cancel an ongoing craft, you will only receive the portion of the craft that has been completed, and you will lose the extra materials and any uncrafted items. 

To see all possible crafts and boosts, check out the <a href="/Bot-features/Currency-Commands/Basic-Commands/Crafting" target="_blank">crafting page.</a>



## Currencylog {: #Currencylog}

The `/Currencylog` will show basically everything going in and out of your inventory, bank, and wallet, as well as things like skin fragments, titles, and other rewards. If a command ever errors or you're not sure where something went, browsing your currencylog can be a great way to figure it out.

The currencylog can be sorted by various types of transactions using the drop-down box at the bottom, including pocket, bank, items, skin fragments, skins, multipliers, titles, etc.

<br>
<center>
<img src="/bot-features/basic-commands/currencylog.png" alt="currencylog.">
</center>


## Daily {: #Daily}

The `/Daily` command can be run every day to earn extra coins or possibly items. This is something that can be great to do each day if you are aiming to get more money, as the amount you receive increases every day and comes with extra rewards the longer you maintain your daily streak.

If you forget to do your daily, there is a small grace period where you will not lose your streak completely. If you miss 1, 2, or 3 days, you will lose 1, 2, or 3 days from your streak. If you miss four days, you will lose half of your total streak, and on the fifth missed day or beyond, your entire streak is reset to zero.

<br>
<center>
<img src="/daily_example.png" alt="daily example." width=500>
</center>

If you haven't done your `/daily` yet, around 1-2 hours before the daily reset you will get a reminder to run the command and continue your streak.

<br>
<center>
<img src="/bot-features/basic-commands/daily_reminder.png" alt="daily reminder.">
</center>

You can also enable "Recurring Income Reminders" in `/settings` to get a DM when you are able to do `/daily` or `/weekly`.

## Deposit {: #Deposit}

With the `/Deposit` command, you can move coins from your wallet to your bank where they are more secure. Coins in your wallet can be lost by <a href="https://dankmemer.lol/community/blog/death" target="_blank">death</a> or during <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Bankrob" target="_blank">bankrobs</a> you enter, can be used to make purchases, or can be stolen when <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Rob" target="_blank">robbed</a>. Coins in your bank are not affected by these things, though they can be bankrobbed.

The deposit command allows quite a few numeral wordings, shown below.

<center>
<p><img src="/bot-features/basic-commands/deposit_1k.png" alt="deposit_1k."> <img src="/bot-features/basic-commands/deposit_1m.png" alt="deposit_1m."></p> 
<p><img src="/bot-features/basic-commands/deposit_1b.png" alt="deposit_1b.">  <img src="/bot-features/basic-commands/deposit_2000.png" alt="deposit_2000."></p>
<p><img src="/bot-features/basic-commands/deposit_2000000.png" alt="deposit_20000.">  <img src="/bot-features/basic-commands/deposit_2000000000.png" alt="deposit_2000000000."></p>
<p><img src="/bot-features/basic-commands/deposit_50_percent.png" alt="deposit_50%.">  <img src="/bot-features/basic-commands/deposit_max.png" alt="deposit_max."></p>
</center>


## Inventory {: #Inventory}

This `/inventory` command shows all of the items that you own and how many of each item you own. It is sorted alphabetically by default, but you can also buy an <a href="/Bot-features/Currency-Commands/Advancements/Upgrades" target="_blank">upgrade</a> called <a href="/Bot-features/Currency-Commands/Advancements/Upgrades#NetWorthSort" target="_blank">net worth sort</a> you can buy to organize your inventory based on what makes up the most of your net worth.

Checking your inventory can be useful if you wish to trade, fight, or collect items.
<br>

<center>
<img src="/bot-features/basic-commands/inventory.png" alt="inventory.">
</center>
  
## Item {: #Item}

This `/item` command can be used to view information about an <a href="/Items/All-items" target="_blank">item</a> and to see how many of a specific item you own. On each item page, there is a description, information about any possible uses, market information, current average value, as well as the selling price if the item is sellable to the bot.

At the bottom of each item embed, there are two or more buttons that can be used as well. The "Market View" button will open the <a href="/Bot-features/Currency-Commands/Market" target="_blank">market offers</a> for that item, and the "Market Inspect" button can be used by <a href="/About-Dank-Memer/Premium-users" target="_blank">premium users</a> to view the current trend of sales for that item. On <a href="/Items/Lootboxes" target="_blank">lootboxes</a> and <a href="/Items/Packs" target="_blank">packs</a>, there is also a button to show the possible items you can find within them.

<br>
<center>
<img src="/bot-features/basic-commands/item.png" alt="item.">
</center>

## Notifications {: #Notifications}

When playing the bot, you can receive DM notifications from the bot with updates on important events. These can include things like your pets bringing you an item or losing a level, a friend sharing something with you, a market ad being accepted, you level up, etc. Usually, anytime you receive something that you didn't run the command yourself to get, you can get a DM notification about it. 

Most Dank Memer notifications are usually enabled by default, but you have to have at least one Discord server where you also allow people to DM you to receive them. Many users create a private server with Dank Memer to do this if they don't want to enable messaging in a public one.

You can customize which notifications you receive or disable them completely in <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Settings" target="_blank">/settings</a>. 

You can also use `/notifications list` to check your 200 most recent notifications or `/notifications search` to search for something specific. For example, in the image below, the query is "coins".

<br>
<center>
<img src="/bot-features/settings/notifications_search.png" alt="notifications search."  width=403>
</center>

The `/notifications list` gives you an abbreviated view of the notification, but you can see the full notif by doing `/notifications view` with the number of the notif you want to see more of. 

<br>
<center>
<img src="/bot-features/settings/notification_view.png" alt="notifications view." width=485>
</center>


## Profile {: #Profile}

You can use the `/profile` command to see your profile or other people's profiles. You can customize your profile in <a href="/Bot-features/Utility-and-Config-Commands/Config-Commands#Settings" target="_blank">/settings</a> by adding a bio or a location to it, displaying <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile/Title" target="_blank">titles</a>, and purchasing a <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile#Showcase" target="_blank">showcase</a>. If you buy the <a href="/Bot-features/Currency-Commands/Advancements/Upgrades#Profile" target="_blank">advanced profile customization upgrade</a> with <a href="/Bot-features/Currency-Commands/Advancements/Upgrades" target="_blank">/advancements upgrades</a>, you can completely customize your own profile so it only shows the information you want. 

<br>
<center>
<img src="/bot-features/basic-commands/profile.png" alt="profile." width=420>
</center>

## Remove {: #Remove}

The `/remove` command can be used to remove any effect that an item may have on you. You cannot remove items that others have used on you, like a <a href="/Items/Consumables#FartinaBottle" target="_blank">Fart in a Bottle</a> or <a href="/Items/Tools#BoxofSand" target="_blank">Box of Sand</a>, but you can remove items you've used on yourself such as <a href="/Items/Power-ups#Alcohol" target="_blank">Alcohol</a>. Removing the item does not return it to your inventory and simply removes it from your active items.
<br>
<center>
<img src="/bot-features/basic-commands/remove.png" alt="remove.">
</center>

## Shop {: #Shop}

The `/shop` command is important in the progression of new starters and professional players. The command has 3 subcommands:
- `/shop sell all` - Which allows you allows you to sell all of your <a href="/Items/Sellables" target="_blank">sellable-type items</a> at once based on your <a href="/Bot-features/Currency-Commands/Multipliers" target="_blank">coin multiplier</a>. When doing the command, you can choose to exclude 1-3 items that you don't want to sell.
- `/shop sell item` - Which allows you to sell a single item to the bot for coins.
- `/shop view` - Which opens the in-game shop where you can buy things for coins, Gems, Fish Tokens, and Skin Fragments.


The amount of money you'll get for selling an item is available on the <a href="/Bot-features/Currency-Commands/Basic-Commands#Item" target="_blank">/item</a> embed. Only some items are sellable to the bot unless you have the <a href="/Bot-features/Currency-Commands/Badges#Collector" target="_blank">collector's badge</a>, which allows you to sell <a href="/Items/Collectables" target="_blank">collectable-type items</a>.

The shop has basic items that many players use every day. What is in the shop can sometimes rotate every few hours throughout the day, and may change completely every few months, but you can see what is currently available in any of the in-game shops with `/shop view`. Use the drop-down menu to switch between the different shops.


### <font color =b32d2d> Coin Shop</font> {: #CoinShop}
The basic coin shop is the regular shop where you can spend your Dank Memer Coins. The coin shop is usually stocked with basic tools needed to play Dank Memer, like <a href="/Bot-features/Currency-Commands/Badges#Collector" target="_blank">Life Savers</a> and <a href="/Bot-features/Currency-Commands/Badges#Collector" target="_blank">Shovels</a>, as well as a few classic collectable items.

Items with a circular icon in the top left corner of their shop picture rotate with something else every few hours when the shop changes.

<br>
<center>
<img src="/bot-features/basic-commands/coin_shop2.png" alt="coin shop example."width=400>
</center>
<br>



### <font color =b32d2d>Gem Shop</font> {: #GemShop}

The gem shop is where you can spend gems that you can purchase from the <a href="https://dankmemer.lol/store" target="_blank">web store</a>. Usually, gems shop items are a bit rarer, and you can buy things like multipliers and boosts.

Yuo can even buy global <a href="/Bot-features/Currency-Commands/Multipliers" target="_blank">multiplier</a> boosts which affect **every** player. There are also sometimes exclusive pets, skins, titles and much more.

<br>
<center>
<img src="/bot-features/basic-commands/gem_shop2.png" alt="gem shop example." width=400>
</center>
<br>


### <font color =b32d2d>Fishing Shop</font> {: #FishingShop}
You can find the fishing shop with the `/shop view` or `/fish shop` commands. The <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing" target="_blank">fishing</a> shop is where you can spend the Fish Tokens you earn from selling your fish. Throughout the fishing shop you'll find fishing-related items like tools, buckets, and baits, as well as fish tank decorations and some foods that can be consumed to give you boosts outside of fishing.

Some items in the Fish Shop are restricted, though, and you'll notice they are grayed out. These items need to be unlocked by either leveling up a special skill in /fish skills, or by being friends with one of the fishing NPCs.

<br>
<center>
<img src="/bot-features/basic-commands/fishing_shop.png" alt="gem shop example."width=400>
</center>
<br>

### <font color =b32d2d>Skin Shop</font> {: #SkinShop}
The last shop you can access is the Skin Shop. This is where you can use Skin Fragments you've earned from duplicate skins to buy new <a href="/Bot-features/Currency-Commands/Skins" target="_blank">skins</a>. What is availabe in the shop is the same for everyone and it rotates every few hours.

<br>
<center>
<img src="/bot-features/basic-commands/skin_shop2.png" alt="gem shop example."width=400>
</center>
<br>


## Use {: #Use}

The `/use` command allows you to use <a href="/Items/Lootboxes" target="_blank">lootboxes</a>, <a href="/Items/Packs" target="_blank">packs</a>, and various items. If an item is usable, it will say on the <a href="/Bot-features/Currency-Commands/Basic-Commands#Item" target="_blank">item description page</a>. For most of the items, you can enter the quantity you want to use, but some items can only be used one at a time. 

**Example: `/use item:God Box quantity:2`**
<br>
<center>
<img src="/use_example.png" alt="use example.">
</center>

If you are opening lootboxes, <a href="/About-Dank-Memer/Premium-users" target="_blank">premium supporters</a> can reroll the loot from boxes for a chance to change what they received!

A `Use Again` button will pop up after you used an item (besides lootboxes) under the embed or when an item expires through the DM Notifications.

<br>
<center>
<img src="/bot-features/basic-commands/useagain.png" alt="use example.">
</center>

## Vacation {: #Vacation}

If you are not able to be online for a little while, but you'd still like to upkeep your streaks, pets, etc., you can use the `/vacation` command.

Using this command will upkeep your:
- <a href="/Bot-features/Currency-Commands/Basic-Commands#Daily" target="_blank">Daily</a> streak (You won't lose your streak)
- <a href="/Bot-features/Currency-Commands/Grind-Commands#Stream" target="_blank">Stream</a> streak (You won't lose your streak)
- <a href="/Bot-features/Currency-Commands/Marriage" target="_blank">Marriage</a>  (Your marriage stays at 100% & you can't get divorced)
- <a href="/Bot-features/Currency-Commands/Pets" target="_blank">Pets</a> (You can't lose your pets)
- <a href="/Bot-features/Currency-Commands/Work" target="_blank">Work</a> (You can't get fired)

Upkeeping these things means they stay protected, but they do not increase during the vacation either. Each stat you need to protect will cost you some money to upkeep, depending on the duration of your vacation.

<a href="/About-Dank-Memer/Premium-users" target="_blank">Premium users</a> receive a certain amount of free vacation days based on their tier.

- As a 2$ subscriber, you get 4 days of free vacation.
- As a 5$ subscriber, you get 10 days of free vacation.
- As a 10$ subscriber, you get 20 days of free vacation.
- As a 20$ subscriber, you get 30 days of free vacation.

<br>
<center>
  <img src="/bot-features/basic-commands/vacation.png" alt="Vacation.">
</center>

## Withdraw {: #Withdraw}

The `/withdraw` command is used to take coins out of your bank and move them to your wallet. Whenever you want to buy something or spend coins, they have to be in your wallet to be used. There is a danger to having coins in your wallet, though, as coins in your wallet can be lost in <a href="https://dankmemer.lol/community/blog/death" target="_blank">death</a>.
<br>

<center>
<img src="/bot-features/basic-commands/withdraw.png" alt="withdraw.">
</center>

Withdrawing money follows the same numeral wordings as the <a href="/Bot-features/Currency-Commands/Basic-Commands#Deposit" target="_blank">deposit</a> command.

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
      <p style="font: 12px Roboto; padding: 0 8px 3px 8px;"> <a href="/Bot-features/Currency-Commands/Achievements" target="_blank">Achievements</a> &#x2022; <a href="/Bot-features/Currency-Commands/Advancements" target="_blank">Advancements - (</a> <a href="/Bot-features/Currency-Commands/Advancements#LevelRewards" target="_blank">Levels</a>, <a href="/Bot-features/Currency-Commands/Advancements#Omega" target="_blank">Omega</a>, <a href="/Bot-features/Currency-Commands/Advancements#Prestige" target="_blank">Prestige</a>, <a href="/Bot-features/Currency-Commands/Advancements/Upgrades" target="_blank">Upgrades</a>, <a href="/Bot-features/Currency-Commands/Advancements#Vote" target="_blank"> Vote</a>) <br> <a href="/Bot-features/Currency-Commands/Adventure" target="_blank">Adventure</a> &#x2022; <a href="/Bot-features/Currency-Commands/Badges" target="_blank">Badges</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Balance" target="_blank">Balance</a> &#x2022; <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Bankrob" target="_blank">Bankrob</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Beg" target="_blank">Beg</a> &#x2022; <a href="/Bot-features/Currency-Commands/Bundles" target="_blank">Bundles</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Fun-and-Images#Compare" target="_blank">Compare</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Craft" target="_blank">Craft</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Crime" target="_blank">Crime</a> <br><a href="/Bot-features/Currency-Commands/Basic-Commands#Currencylog" target="_blank">Currencylog</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Daily" target="_blank">Daily</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Deposit" target="_blank">Deposit</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Dig" target="_blank">Dig</a> &#x2022; <a href="/Items/Drops" target="_blank">Drops</a> &#x2022; <a href="/Bot-features/Currency-Commands/Farm" target="_blank">Farm</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands/Fishing" target="_blank">Fish</a> &#x2022; <a href="/Bot-features/Currency-Commands/Friends" target="_blank">Friends</a> &#x2022; <a href="/Bot-features/Currency-Commands/Serverevents-and-Giveaways#Giveaways" target="_blank">Giveaway</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Highlow" target="_blank">Highlow</a> <br> <a href="/Bot-features/Currency-Commands/Grind-Commands#Hunt" target="_blank">Hunt</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Inventory" target="_blank">Inventory</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Item" target="_blank">Item</a> &#x2022; <a href="/Bot-features/Currency-Commands/Leaderboards" target="_blank">Leaderboard</a> &#x2022; <a href="/Bot-features/Currency-Commands/Lotteries" target="_blank">Lottery</a> &#x2022; <a href="/Bot-features/Currency-Commands/Market" target="_blank">Market</a> &#x2022; <a href="/Bot-features/Currency-Commands/Marriage" target="_blank">Marriage</a> &#x2022; <a href="/Bot-features/Currency-Commands/Advancements/Upgrades#Monthly" target="_blank">Monthly</a> <br> <a href="/Bot-features/Currency-Commands/Multipliers" target="_blank">Multipliers</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Notifications" target="_blank">Notifications</a> &#x2022; <a href="/Bot-features/Currency-Commands/Pets" target="_blank">Pets</a>  &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Postmemes" target="_blank">Postmemes</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile" target="_blank">Profile</a> &#x2022; <a href="/Bot-features/Currency-Commands/Quests" target="_blank">Quests</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Remove" target="_blank">Remove</a> &#x2022; <a href="/Bot-features/Currency-Commands/Rob-and-Heist#Rob" target="_blank">Rob</a> <br> <a href="/Bot-features/Currency-Commands/Grind-Commands#Scratch" target="_blank">Scratch</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Search" target="_blank">Search</a> &#x2022; <a href="/Bot-features/Currency-Commands/Serverevents-and-Giveaways#Serverevents" target="_blank">Serverevents</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Shop" target="_blank">Shop</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile#Showcase" target="_blank">Showcase</a> &#x2022; <a href="/Bot-features/Currency-Commands/Skins" target="_blank">Skins</a> &#x2022; <a href="/Bot-features/Currency-Commands/Grind-Commands#Stream" target="_blank">Stream</a> &#x2022; <a href="/Bot-features/Utility-and-Config-Commands/Utility-Commands#Taxcalc" target="_blank">Taxcalc</a> <br> <a href="/Bot-features/Currency-Commands/Basic-Commands/Profile#Titles" target="_blank">Title</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Use" target="_blank">Use</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Vacation" target="_blank">Vacation</a> &#x2022; <a href="/Bot-features/Fun-Games-Image/Games-and-Wagers#Wagers" target="_blank">Wager</a> &#x2022; <a href="/About-Dank-Memer/Premium-users#Weekly" target="_blank">Weekly</a> &#x2022; <a href="/Bot-features/Currency-Commands/Basic-Commands#Withdraw" target="_blank">Withdraw</a> &#x2022; <a href="/Bot-features/Currency-Commands/Work" target="_blank">Work</a> </p>
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

