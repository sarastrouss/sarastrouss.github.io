---
layout:     post
title:      WREK Atlanta Player
summary:    ___
date:       2016-05-25
categories: UX Design
---

<b>Problem</b>: Due to the inner workings of WREK Atlanta, www.wrek.org is self-hosted through the campus OIT. However, with WREK’s website dependent on the campus’s network and servers, there are often outages. Some of these outages can last for days. In order to provide listeners with a backup to listen online, we are currently working on creating a light wrek.org that will not be self-hosted.

I am leading the feature design of the WREK player. Some key features that we have identified as absolutely necessary are:

- Online playlist
- Song metadata
- Show info
- Pop-out window
- Contact info
- Mobile friendly

<u>Current Implementation</u>

When the user presses the volume button on the player, it opens to a pop-out player. In addition, each link featured on the player takes the user to another page on wrek.org. 

![player](/images/player_old.png)

The current pop-out player's design is not consistent with the player design. It does reuse elements from the main page such as the request widget. Overall, the content of the pop-out player does fit the feature list that we want to complete, however it is not mobile friendly. 

![player_out](/images/Popout Player.png)

<b>Process</b>

To begin, I started by wireframing several different potential layouts for the player that would appear on wrek.org. I started off with a similar layout to the current one and moved from there.

![player_out](/images/player.png)

The final player design puts focus on the what is currently happening on air. The user can change the volume, bring up a short playlist that changes the content in the player widget, and pop out the player into another window. 

<b>Main Proposed Changes</b>

- Player does not automatically pop out, but plays immediately after the user selects the play button.

- User can change between on-air, HD-1, and HD-2 stations through the provided menu. 

- There is a reinforced show identity by highlighting the show’s icon on the web player.

- Including the social media icons and contact at the bottom of the player frees up space on wrek.org.

![player_out](/images/player-final.png)