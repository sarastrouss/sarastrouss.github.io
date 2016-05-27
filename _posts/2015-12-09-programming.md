---
layout:     post
title:      Programming Dashboard 2.0
summary:    ___
date:       2015-12-09
categories: Development
---

<b>Problem</b>: The current music director system at WREK Atlanta is not user friendly. After working with the system myself, and discussing some of the usability issues with other music directors, I decided to take on the project as my senior design project. I worked with two other people and I was responsible for the <b>front-end development</b>. I used <b> Ruby on Rails</b>, <b>d3.js</b>, and <b>Bootstrap</b>.

Some of the key issues users noted:


- Unable to delete an album/track
- Adding a track is confusing
- Finding the correct record label isn't easy
- Can't share albums with other users
- Can't mark a track obscene

<b>Previous System</b>

![program_menu](/images/program_menu.png)

Very messy menu system that with confusing wording. Add albums vs add incoming album, for example, can often lead a user to add an album directly to the database to be programmed whereas adding an incoming album sends it to the audition phase.

![program_case](/images/programming_case.png)

Example of what users do in order to mark a track as obscene. However, due to the track still eventually showing up to the on-air DJ, it is possible for them to both play this track and announce it on air as if "Obscene Do Not Play" is the track title.

![addAlbum](/images/add_album_old.png)

The most difficult issue we saw users encounter with adding an album was dealing with the record label input. A lot of the albums sent to WREK Atlanta are self-released and do not belong to a label.

![addTracks](/images/add_tracks_old.png)

Programming an album for airplay can take a lot of time. Adding the track metadata individually just adds to the time. We felt that it was possible to make this process a little easier.

<b>Process</b>

Features:


- Tracks can be marked obscene
- Automation and online listener data is displayed in order to allow users to make more informed programming decisions
- Menu follows user
- FAQ Page for new users
- Clear feedback to user when an action is taken

The initial design worked off of a grid system and would display all album artwork for incoming albums instead of a list. However, we found that due to the nature of some of the albums sent to WREK Atlanta, finding the album artwork through existing databases impossible.
![wireframe-pd](/images/Wireframe-PD.png)



<b>Proposed Solution</b>

<u>Home Page</u>

<b>What we updated:</b> Instead of seeing a list of albums to be programmed, the user sees real-time data related to the number of online listeners and automation usage. Hovering over each cell in the heatmap shows the user the number of online listeners and the show for a given hour.

![home_page](/images/home_page_PD.png)

<u>Add An Album</u>

<b>What we updated:</b> The biggest change for adding an album was changing the input type for the record label. Instead of creating and maintaining a list of record labels, the user inputs one into a text field and if that record label already exists, it will auto-fill. We also added a field for the user to add a Spotify URL if one exists. This feature would become available in a later version of the WREK online playlist.

<u>Add New Track</u>

<b>What we updated:</b> The biggest change for adding a new track was the addition of an explicit field. If a track is marked explicit, that particular track will be blocked out in red indicating to the on-air DJ not to play that track. In addition, a frequency field was added to each track for automation purposes.

<u>Feedback, Search, and Help</u>

<b>What we updated:</b> We added feedback for the user whenever an action was taken. We also included filtering search for programmed albums and incoming albums. We also included a simple FAQ page for new users.

![new_album](/images/Feedback-PD.png)

![wireframe-pd](/images/Help-PD.png)





