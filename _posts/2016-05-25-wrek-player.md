---
layout:     post
title:      WREK: Live Player Redesign
summary:    ___
date:       2016-05-25
categories: UX Design
---

<b>Problem</b>: WREK Atlanta's Wordpress site, ([WREK.org](https://wrek.org)), has come a long way from what it looked like [back in 2001](http://web.archive.org/web/20011127061215/http://www.wrek.org/). Even so, the most recent redesign took place in 2013, and the Live Player was an Adobe Flash widget with no phone-friendly fallback until 2015. I'm leading a redesign of the player to address listener feedback and improve the overall experience. Key elements of the new player: 

- Easier access to show descriptions and playlist history
- Mobile friendly while maintaining features such as live-updating "Now Playing" text
- Optional, rather than mandatory pop-out player

<u>Current Implementation</u>

When the user presses the volume icon on the WREK homepage, a pop-up player window opens. In addition, each link featured on the player takes the user to another page on wrek.org. 

![player](/images/player_old.png)

While the current player's design does reuse some elements from the homepage such as the Song Request widget, it still feels inconsistent across desktop and mobile, and there are a few strange CSS quirks on tablets. 

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
