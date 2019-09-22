# Changelog

## 1.15.0 - 2019-09-22

Many updated strings for website and the bot

{% tabs %}
{% tab title="Bot" %}
* Ban a user with its id: `?ban {userid} {reason`
* Ban or tempban reasons can now be seen in the Discord application when you click on a ban 
* If you type `?clear 2`, this will delete the last 2 messages which were sent before executing the command. This means that the command doesn't count as one message which should be deleted 
* Fixed music module \(`?cmds Music`\)
* Fixed double response messages when direct messaging the bot
* If you're LenoxBot staff member, it can now be seen if you use the command `?userinfo` 
* Many updated strings for the bot 
* To pay some credits to somebody, you can use the comman `?paycredits` now also with a userid 
* Sometimes the custom emojis of a Discord server weren't shown when using `?serverinfo`
* `?hentaihaven` commands has been fixed
* If modlog is activated and a moderator executes `?clear`, it gets logged in the modlog channel 
* To execute `?clear`, the moderator must give a reason for this use of `?clear` 
* Fixed the `?channelblacklistremove` command 
* New commands for LenoxBot staff members \(?senditem & ?setstreak & ?guildinformation\). Deleted the commands `?prefixfinder` and `?languagefinder` 
* If you execute `?inventory upgrade` it uses one inventoryslotticket
* Fixed a bug that you couldn't play a playlist with the command `?playplaylist`
{% endtab %}

{% tab title="Website" %}
* The browser tabs of **lenoxbot.com** are now translated too 

![translated browser tabs](.gitbook/assets/stkwidw%20%281%29.png)

* Your session on the website is now persistent. This means that you stay logged in also if the bot restarts
* New section on our first page - "What our customers say?" 
* If you click on "Vote" in the navigation bar, you get an explanation of how the voting system works LenoxBot Staff members see staff-only commands now on the /commands page 
* In the logs on the dashboard you can now see where a setting has been changed. Either via the dashboard or a command 
* All dashboard logs should be translated now 
* If you have a LenoxBot Premium Discord server, it gets a new design in the /servers list 
* Some design changes for the /servers page \(for example transparent background\) 
* Servers get sorted now if you visit the /servers page. All Discord servers that have LenoxBot, are listed first in the server list 
* Fixed the profile page and the feature cards on the main page
{% endtab %}
{% endtabs %}



## 1.13.0 - 2019-06-30

{% tabs %}
{% tab title="Changed" %}
* Many language strings updated
* Performance updates
* Request credits using a userID \(`?c <USERID>`\)
* Added Icons in the job list
{% endtab %}

{% tab title="Added" %}
* The webuser is now able to see the used inventoryslots on a profile user page
* New command `?remind` : Sets a reminder
* New NSFW command `?hentaihaven` : Random HentaiHaven videos
* New HELP command `?lenoxbotteam` : All LenoxBot staff members
{% endtab %}

{% tab title="Fixed" %}
* ?hangman bug fixed
* Unmute reason was 1 after a user got automatically unmuted by LenoxBot
* Error pages on the website after requesting the servers page
{% endtab %}
{% endtabs %}

## 1.11.0 - 2019-06-01

{% tabs %}
{% tab title="Added" %}
* Website is now available in more languages
{% endtab %}
{% endtabs %}

## 1.9.0 - 2019-05-13

{% tabs %}
{% tab title="Changed" %}
* Command changed: **?calculator --&gt; ?calculate/?calc**
* Instant forwarding to discord login page for pages where a login is required
{% endtab %}

{% tab title="Added" %}
* Guildupdate log is now in the dashboard
* The name of the Discord server is now written in the browser tab if you are currently in the dashboard of a Discord server
* New command **?punishments** : Shows you the punishments of a user \(bans, mutes, kicks, warns, ...\)
* The socialmedia of every staffmember are now on the team page of lenoxbot.com
{% endtab %}

{% tab title="Fixed" %}
* NSFW commands work again
* Temporary ban didn't work with an UserID
{% endtab %}
{% endtabs %}

## 1.8.1 - 2019-04-28

{% tabs %}
{% tab title="Fixed" %}
* Many bugfixes
* Dashboard has been fixed
{% endtab %}
{% endtabs %}

## 1.7.2 - 2018-12-22

{% tabs %}
{% tab title="Changed" %}
* Many strings have been changed
* All logs have now different colors
* Changed the description of the website
* All answers of the `?shop` command are now in Richembeds
* You can now have the welcome and bye messages in embeds using `$embed$` in your welcome/bye message
* People who do the job "Harvest fields" get now more credits
* Added new links in the website footer
{% endtab %}

{% tab title="Added" %}
* Create new custom commands via the dashboard \([https://i.imgur.com/aJCoth8.png](https://i.imgur.com/aJCoth8.png)\)
* You can now buy and sell items using the words of the items \(in the server language\)
* Our new statuspage is now in the help command
* You can now give your friends your inventory items with the new command `?giveitem`
* New minigame `?hangman` to play solo or with your Discord friends
* Added new socialmedia: GitHub, Facebook, Pinterest and Reddit
* All current premium users have a badge on their website profile
* New badges have been added \(XP badges, buy/sell badges\)
* New command `?joinrole` to define which roles new users will get when they join your Discord server
{% endtab %}

{% tab title="Fixed" %}
* Some translation mistakes
* You couldn't get the stats of a fortnite account with a space in the name
* "Harvest fields" was undefined in the `?job` command
* The months were written in German on the website. We changed it to English
* Ticket system
{% endtab %}
{% endtabs %}

## 1.7.1 - 2018-11-12

{% tabs %}
{% tab title="Changed" %}
* Prices of the crate and the cratekey have been updated
{% endtab %}

{% tab title="Added" %}
* New items have been added in the `?opencrate` command
{% endtab %}

{% tab title="Fixed" %}
* Userkeys weren't saved for the user
{% endtab %}
{% endtabs %}

