**Bot Ideas List by T_nology**

Suggestions:

**Part A - XP System**

**1.** Add `>setxp`<br>
**2.** Add `>givexp`<br>
**3.** Add `>takexp`<br>
**4.** Add `>setlevel`<br>
**5.** Add `>givelevel`<br>
**6.** Add `>takelevel`<br>
**7.** Add a channel blacklist feature (per-server) for earning XP<br>
**8.** Allow for a customizable amount of XP to be given per-channel<br>
**9.** Allow for a customizable multiplier of XP to be given per-role<br>
**10.** Add a user blacklist feature for earning XP<br>
**11.** Add reward roles, so users can get certain roles for earning enough XP/hitting a certain level.<br>
**12.** Add the ability to award a disposable role with XP (the user might have to claim it) (refer to Part D - Utilities @ D7)<br>
**12.** Add an XP leaderboard with pages.<br>
**13.** Add the ability to set a user's XP/level when the user is not in the server.<br>
**14.** A per-user command to toggle mentions in the level-up message.<br>
**15.** Add an option for users to gain between X and Y XP by being in a specific voice chat. Make it possible to configure the bot so XP is only given if there are 2 or more users in voice chat and 2 or more people are unmuted. Additionally, streaming in voice chat with at least X users can earn between A and B XP if the user configures it.<br>
**16.** The ability for each user to toggle mentions in the level up message, per-user. This would be beneficial because some users enjoy being pinged over the level up message, while others hate it.<br>


**Part B - Moderation**

**1.** Add basic moderation features, such as `>ban`, `>tempban`, `>kick`, `>mute`, `>tempmute`, `>timeout`, `>purge`, and other basic moderation commands.<br>
**2.** Add the ability to restrict each moderation command to a specific role (per-server).<br>
**3.** Add a `>purgeuntil` command to purge messages until a specific point in time.<br>
**4.** Add a `>purgeuser` command to only purge a specific user's messages.<br>
**5.** Add an optional parameter in `>ban` and `>tempban` to clear the user's messages (clearing no messages by default).<br>
**6.** Add a "blacklist" system. The blacklist system would be used as a system as an in-between for muting and banning. Blacklisted users will not have access to any channel, neither being able to view them in the channel list nor send messages in them. This feature would be useful if the owner or a staff member wants to ban a user from sending and reading messages in a server, but does not wish to use Discord's ban feature. One good reason to not use Discord's ban feature is because Discord IP bans users who are banned from joining the server. This is especially problematic because most people have a dynamic IP, which can change either over time or by leaving the router unplugged for a while and plugging it back in. Not only does this mean that an IP banned user can evade the ban with an alt without the usage of a VPN or another network, but it also means that an innocent person can have their IP switched to a banned IP and be banned from a server for no reason. This is even more problematic if the server is intended for a specific area (e.g. a community in a city) or the server is a large server, as many people in the same area may be joining and thus increasing the chance of an innocent person being banned. Additionally, Discord's ban system does not give the user a reason for being banned, so if the user's DMs are off for the server upon being banned (assuming the user is even banned by a bot), the user will not get a reason as to why they were banned. This system would work through a custom "Blacklisted" role that the user recieves when blacklisted. The user would not have access to any other channels, other than a "#blacklisted" channel. In this channel, the owner can set up a message that has a reaction or button on it, and upon clicking it, the bot would tell the user the reason provided for the blacklist (either through an ephemeral message or DM), along with the time remaining if it's not permanent.<br>
**7.** Add a filtering feature.<br>
**8.** Add a `>post` feature. This will bring up the last thing deleted by the bot in the channel (e.g. a deleted invite). You can use this without arguments or you can ping a user as an argument to bring up their last deleted thing. The last deleted thing must be within the last 48 hours. Example: User A posted an invite and User B posted a different invite, both of which were deleted by the bot. A staff member with the proper permission wants to get back User A's invite, so they type: `>post @User A`. This will then make the bot say: `@User A posted: [invite link]`. This can also work with things the bot auto-deletes other than invites, such as spam.<br>


**Part C - Tickets**

**1.** Add a read/unread ticket system (which is toggleable per-server). If the system is enabled, here's how it will work:
When a ticket is opened, the ticket will go into the "Awaiting Response" category. Then, when any Staff Member responds in that ticket, the bot will put that channel in the "Responded" category. You can set what you want the "Awaiting Response" and "Responded" categories could be. A Support Representative/Staff Member can also type >r (or whatever the prefix is set to in that server) to mark a ticket as "Responded" without the staff member sending an actual message, and then that message is deleted.<br>
**2.** Priority Tickets, which allow users with a specific role to be able to prioritize tickets by adding them to a prioritized (configurable) category.<br>
**3.** Ticket categories, using the same system as ZeoBot's ticket category system, with every same exact feature (plus more), ask T_nology for more information once you begin working on this.<br>
**4.** Add the ability to open a ticket of a different category with different commands. (Example: Allow a user to set up `>tnew` for a regular ticket and `>mnew` for a management ticket).<br>
**5.** Add a ticket panel that appears when a user runs the command to open a ticket (such as `>new`). Look at how ZeoBot (T_Bot) is configured this way for an example in T_Cord.<br>
**6.** Add an `openable` option for ticket categories, which would be mainly used for categories where tickets could only be transferred to them and not opened in them.<br>
**7.** Add ticket transcripts that are saved in a customizable ticket logs channel when a ticket is closed.<br>
**8.** Allow the server owner to set different channels for each ticket category.<br>
**9.** Add a `>lock` command to lock a channel, with the ability to optionally specify how long to lock it for.<br>
**10.** Add a `>hidechannel` command to not only lock a channel, but also hide it from members.<br>
**11.** Add a `>lockdown` command to lockdown the entire server, not allowing any new messages to be sent in any of the channels. A time can optionally be provided for how long the server should be locked for.<br>
**12.** Add the purge commands that ZeoBot has, including `>purge` and `>purgeuntil`, but also a `>purgeuser` command that will purge X messages from a user __OR__ purge messages from a user for __X__ amount of time __either in one channel, every channel, or a few specified channels.__<br>
**13.** Add the automod features ZeoBot has, including being able to take X action (e.g. verbal warning or warning or tempban or whatever) when a certain amount of violation points have been reached. Also add the ability for an action to happen (e.g. a mute or tempban) when X amount of warnings has been reached.<br>
**14.** Add a `>history` command to view a user's punishment history.<br>
**15.** Add a `>modhistory` command to view a user's moderation history.<br>
**16.** Add `>timeout` and `>untimeout` commands.<br>
**17.** Add a `>slowmode` command.<br>
**18.** Add a ticket limit for users, with different roles being able to have different limits (and having no limit if it's set to `-1`).<br>


**Part D - Utilities**

**1.** Add an `>emojisteal` command.<br>
**2.** Add a `>stickersteal` command.<br>
**3.** Add an `>exportmessages` command, which would allow the person running the command to get a transcript of the X most recent messages of any channel (just like ticket transcripts, making an HTML file). (Number of messages is passed as a parameter)<br>
**4.** Add a `>serverinfo` command that displays server information, such as when the server was created, the owner of the server, the member count (total, users, and bots), the channels in the server, etc.<br>
**5.** Have the `>serverinfo` command only display the channels that the user has access to.<br>
**6.** Add a `>userinfo` command that display user information, such as when the user's account was created, the user ID, the user's roles in the server, etc.<br>
**7.** Add a disposable role feature for specific use cases. __For example, a role can be used to allow the user to change their nickname X time(s) before it is taken away__, with the bot tracking the nickname changes, __or a role that allows a user to send X message(s) in a certain channel before the role is taken away, optionally with X amount of time as a cooldown between messages__ (where messages that have not waited the cooldown will be deleted as if they weren't sent).<br>
**8.** Add a text-to-speech feature, which generates an MP3 file with text-to-speech of the text the user provides.<br>
**9.** Add a reminder system.<br>
**10.** In the reminder system, allow the command to cancel a reminder to cancel either just one reminder or a group of reminders at a time.<br>
[i forgot to send parts 11-25 to blocks and i am on windows right now to prepare for school. i'm tired and i don't feel like explaining anything so idk]<br>


**Part E - Suggestions**

**1.** Add the ability for users to have current suggestions, accepted suggestions, and denied suggestions to be in separate channels.<br>
**2.** Add the ability for suggestions that have already been accepted or denied to have their status changed.<br>
**3.** Add an optional "community deny" feature to suggestions that will automatically deny a suggestion if it has X% (configurable) amount of downvotes compared to upvotes.<br>
**4.** Allow the server owner to choose the reactions for upvoting and downvoting a suggestion.<br>
**5.** Add an `>amendsuggestion` command that allows a user to amend a suggestion. This way, suggestions cannot be abused by being edited entirely, but users who may have made a mistake in their suggestion can still clarify something in the suggestion. This comes with an `amendment_limit` configuration value that can be set by the bot owner.<br>
**6.** Custom statuses for suggestions. (Example: The server owner adds an "Implemented" status). Each status can have a custom channel (so the owner can add #implemented-suggestions), or use an existing channel (such as #accepted-suggestions). If the status is in the same channel the suggestion is already in, the bot will edit the message. Additionally, there is a custom color option for each suggestion status.<br>
**7.** Add suggestion IDs for suggestions. Suggestion IDs make sense because using message links to refer to suggestions is just plain stupid. Think about it, the message gets accepted/denied, and now the original suggestion message link doesn't work anymore because the original message was deleted.<br>
**8.** Add an optional "community deny" feature that will deny your suggestion if it has X% more downvotes than upvotes and/or reaches X amount of downvotes.<br>



**Part F - Economy**

**1.** Add different levels of jobs/education in the economy module. The default educations are `High School Dipoloma`, `Associate's Degree`, `Bachelor's Degree`, `Master's Degree`, and `Doctorate Degree` The user must use the `>school` command to level up education, which will give the user a challenge such as a matching game or a math game. The jobs are customizable, as well as the challenges (e.g. how hard the math questions are per education level and how much time is given), the currency, and more.<br>
**2.** Add a shop that users can buy from with currency. In the shop, allow users to buy roles either permanently or temporarily. This can go well with Suggestion D7.<br>
**3.** Allow the economy to work similar to XP, with users gaining money by being active, if the owner wants to configure it this way (such as if the owner prefers an economy over an XP system), allowing a user to gain between X and Y coins in a certain channel with possible multipliers and a blacklist system. (Refer to suggestions A7, A8, A9, and A10)<br>
**4.** Add an option for users to gain between X and Y coins by being in a specific voice chat. Make it possible to configure the bot so coins are only given if there are 2 or more users in voice chat and 2 or more people are unmuted. Additionally, streaming in voice chat with at least X users can earn between A and B coins if the user configures it.<br>
**5.** Add an economy leaderboard.<br>


**Part G - Games**

**1.** Add a tic-tac-toe game for two users to play tic tac toe game between each other.<br>
**2.** Add a singleplayer mode for tic-tac-toe, with the bot's AI not being too good so it doesn't just win or tie every game.<br>
**3.** Add a connect four game.<br>
**4.** Add a minesweeper game that uses buttons.<br>
**5.** Add a `>typeracer` command that generates an image of a phrase, and the phrase must be typed in X (configurable) seconds. You can use the default typeracer phrases for the bot, able to be toggled in the config/a file, as well as have your own phrases (that you can provide your own image for or use an automatically generated one for it) with a custom amount of time.<br>


**Part H - Music**

**1.** Add all of the obvious stuff - looping, shuffling playlists, pausing, stopping music, playing.<br>
**2.** Add support for playing YouTube playlists and individual YouTube videos. You can optionally add support for Soundcloud and whatnot, but you don't have to.<br>
**3.** Add te ability to play `.mp4` and `.mp3` files.<br>


**Part I - Other**

**1.** __Add an extensive addon system, which allows people to easily make addons for the bot that are extraordinarily and extremely customizable to a highly extreme extent, while being stupid easy for the user to make and use while also having fantastic documentation on it.__<br>
**2.** Add the ability to play YouTube livestreams and MP3 file livestreams.<br>
**3.** Add a party feature, which works like this:<br>
`Note:` In commands, arguments with triangle brackets (`<this>`) are required and arguments with square brackets (`[this]` are optional. The triangle/square brackets are not included in the actual command.<br>
**Party Feature**<br>
This feature would allow for users to create "parties." A party would have a host, which would be the user who created the party, and could do the following: Invite users, transfer host to another user, remove users, and make them co-hosts. There are a few things that could be done with parties. Below are some basic party commands:<br>
`>party create <name>`<br>
`>party invite @User#1234` (the user must accept)<br>

**Party Voice Chats**<br>
With parties, a private voice chat could be created in a category defined in the configuration (e.g. Parties). Only those who are in the party would have access to the voice chat. Here are the party voice chat commands:<br>
`>party voicechat create "<name>" [user limit] [bitrate]`<br>
`>party voicechat edit <name|bitrate|userlimit> <new name|new bitrate|new user limit>`<br>
`>party voicechat delete`<br>

**Party Private Channels)**<br>
Parties will allow for the ability for the users to communicate with each other within the server while also not worrying about those not in the party interfering with their conversations. You can define roles that will always have access to party channels in the configuration (useful for adding staff to the party channels to ensure moderation is happening). Here are the private channel commands:<br>
`>party channel create <name>`\*<br>
`>party channel edit name <new name>`<br>
* There could be a specific configuration option that would just make the channel name be something that you choose, such as `{PARTY_NAME}-chat`<br>

**User-Specific Permissions & Ranks**<br>
A really useful feature of parties would be user-specific permissions and ranks within the parties. This could be very customization for the hosts of parties to choose what permissions could be given to specific users and ranks. An example would be the `MANAGE_PARTY_MESSAGES` party permission. If the user has this permission, they get the Manage Messages permission in the party channel. Below are some permissions:<br>
`MANAGE_PARTY_MESSAGES` - Allows for the user to manage messages in the party chat.<br>
`PARTY_PRIORITY_SPEAKER` - Allows for the user to use Push to Talk (Priority) in the party voice chat.<br>
`EDIT_PARTY_CHANNEL_NAME` - Allows for the user to change the party channel's name. Does not work if there is a forced name in the configuration.<br>
`SEND_TTS_PARTY_MESSAGES` - Allows for the user to send TTS Messages in the party chat.<br>
`SET_PARTY_VOICE_CHAT_BITRATE` - Allows for the user to set the bitrate in the party voice chat.<br>
`INVITE_MEMBERS` - Allows for the user to invite other members to the party.<br>
`CREATE_PARTY_CHAT` - Allows for the user to create the party channel.<br>
`SET_PARTY_VOICE_CHAT_USERLIMIT` - Allows for the user to set the user limit in voice chat.<br>
`MANAGE_RANKS` - Allows for the user to manage the party's ranks.<br>
`MANAGE_USERS` - Allows for the user to manage other users below them in rank.<br>
`HOST` - The HOST permission is essentially the equivalent to the "Administrator" permission on Discord. Users with this permission can do everything the host can except for doing anything to the host himself/herself or deleting the party.<br>
These wouldn't necessarily be all of the permissions, and these are just examples as to what some of them would be. Now, how this would work is that there would be ranks that could have permissions kind of like how Discord roles work, but there wouldn't be actual roles given/involved. Permissions could be given to individual users as well. By default, there are 3 ranks, called `HOST`, `COHOST`, and `MEMBER`. `HOST` would only be for the host of the party, while `COHOST` has the `HOST` permission by default, and `MEMBER` is an automatic rank given to members upon joining the party. New ranks could be made and managed and everything would be customizable.

**Party Saving/Loading**<br>
This is something that wouldn't have to be a part of the parties feature, but would be very useful. It would allow for a file to be generated that somehow can load the current party. It would have the ranks, the permissions, and everything of that party stored in that key so even in another server with this same parties feature, the host could use this key and have their old party from another server back.<br>


List is to be updated, I'm super tired and hopefully I can get at least 6 hours of sleep tonight (trying to aim for 6.5 if possible). If you don't know what ZeoBot is, that's fine, I made this list for Bloxs (aka Blocks_n_more) for his bot, called Bidome. I just copied and pasted the ideas here so you guys can see it.
