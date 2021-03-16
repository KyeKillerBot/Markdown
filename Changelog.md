# KyeKillerBot V8.2.2 Patch: (16/03/2021)

### New Features:
- Poll command (Beta).


### Bug fixes: 
- Fixed farewell membercount issue,
- Fixed music issue's,
- Minor bug fixes.


### Improvements:
- Reactionroles command is in beta,
- Disabled some commands for maintenance.


### Removed:
- npm command.

### Known Issue's:
- Check out our trello **[here.](https://trello.com/b/ht61iCHe/kyekillerbot-issues)** To see known issue's on the bot.


# KyeKillerBot V8.2.1 Patch: (12/03/2021)

### Bug fixes: 
- Fixed a bug in verify command,
- Fixed database connections,
- Fixed default spelling mistake,
- Minor bug fixes.

### Known Issue's:
- Check out our trello **[here.](https://trello.com/b/ht61iCHe/kyekillerbot-issues)** To see known issue's on the bot.


# KyeKillerBot V8.2.0 Build: (14/02/2021)
## Warn system will be released in one of the patches of this update!

### New Features:
- Added spotify support to our music commands,
- Added massban command,
- Added togglebeta (Opt-in and out beta mode.).

### Bug fixes: 
- Fixed a bug inside the lyrics command,
- Fixed examples missing command names.

### Improvements:
- Multi bans has been removed from the ban command and moved to the new command "massban",
- Removed the default footer from embed,
- Added "In Beta" on serverinfo command.

### Removed: 
- JavaScript Comamnd,
- Discord.js Comamnd,
- Github Comamnd,
- Alpha Servers System.

### Known Issue's:
- Check out our trello **[here](https://trello.com/b/ht61iCHe/kyekillerbot-issues)** to see known issue's on the bot.

# KyeKillerBot V8.1.1 Patch: (06/01/2021)

### Bug fixes: 
- More permission checks to hopefully fix some errors,
- Fixed the permission errors on reactionroles command,
- Backend fixes.


### Improvements:
- Changed the partner server owner flag,
- Current version is now on the embeds footer,
- Commands that are under maintenance no longer get shown on the help list,
- Changed some errors on our moderation commands,
- Added 2 new tags to the Welcome command and Farewell command ({user.name} and {user.tag}),
- Changed errors on redeem command for premium keys,
- Exmaples now show the full command,
- Added an error to the welcome/farewell test command. 

# KyeKillerBot V8.1.0-1 Patch: (12/12/2020)

### Side note:
We are looking to improve on our auto-mod system. So, you feedback on it, is important to us! 

### New Features:
N/A Bug patches & improvements only.

### Bug fixes: 
- Fixed DMTickets,
- Fixed the invite links.


### Improvements:
- Server Owners and anyone with "Administrator" permission can now bypass the auto-mod,
- voteOnly commands have been enabled,
- Activity has been updated

# KyeKillerBot V8.1.0 Build: (21/11/2020)

### New Features:

- Added alpha servers,
- Added editsnipe command,
- Auto-moderation system is here! (antiSpam, antiInvites, antiSelfBots, antiTokens, antiAttachments & antiCaps),
- Added verifercation system,
- Added 24/7 mode for music. (Bot doesn't leave the voice channel),
- Added dj role system,
- Added hentai nsfw command.,
- Added modOnly commands. (To set this do k!setroles mod <role>, following commands on the role: "say" and "slowmode". More maybe added in the future).

### Bug fixes: 
- Spelling mistakes,
- Starboard issue,
- guildMemberRemove issue.

### Improvements:
- Changed snipe command to util catorgory,
- You can now report bot abusers to us with the report cmd. (k!report abuser mention reason),
- Added meet the team to botinfo command,
- All moderation commands reason's are optional,
- redone the muted logging embed, 
- Ban messages will no longer self delete.

### Removed: 
- Gah command,
- Team command.

# KyeKillerBot V8.0.3-1 Patch: (22/10/2020)

This is a small extra to the V8.0.3 patch!

### Fixes

- Hopefully fix `Cannot read property 'track' of undefined` when you cancel a track selection with the play command
- Hopefully fix `Cannot read property 'guild' of undefined`

### Improvements

- Show a error message when the play command is triggered with no arguments
- Capture process errors

# KyeKillerBot V8.0.3 Patch: (17/10/2020)

### Fixes

- Fixed XP System, should work correctly
- Starboard should be entirely fixed, including the settings command for it.

### New Features

- Added ability to toggle the leveling system
- The `levelUp` event is now disabled by default
- New support team commands. While these are not public, these will be nice to support staff!
- Added `embed` command.
- Added `oldest` command
- Added `hijack` command to steal emojis

### Improvements

- Starboard improvements
- Roles command edits

# KyeKillerBot V8.0.2 patch Release: (16/10/2020)

### Improvements

- Improvements on the queue system
- Added new feature on `remove` command.

### Bug Fixes

- Fixed hackban
- Fixed guildMemberRemove `Cannot read property 'toLocaleDateString' of null` error.
- Fixed starboard `Cannot read property 'partial' of null` error.

### New Commands

- Added emojis command.
- Added slowed and nightcore command for premium users.

# KyeKillerBot V8.0.1 patch Release: (24/09/2020)

### Improvements

- Marry command now has a 1 minute timelimit,
- More permission checking in commands,
- Added empty catches to delete methods,
- Guild check in messageDelete event

### Bug Fixes

- Fixed all gifs on roleplay commands, they should now not send blank embeds,
- Minor bug fixes

# KyeKillerBot V8.0.0 (Rewritten) Release: (22/09/2020)

### New Features

- Music commands return! - They are better and easier to use.
- Economy - Has been redone and is much much better!!
- Snipe - Snipe the last message deleted in the channel.
- Djs - Search the discord.js docs without going to the website!
- Github - find user's and repo's within the bot!
- Enlarge - turn an emoji bigger!
- Progressbar - Shows how long left of the year!
- Nuke - Deletes and clones a channel! (Moderation)
- Sex - Sex command for you to have fun! (NSFW Only)
- Reactionroles - Set reaction roles for your users! (Moderation)
- Settings commands System - Set how you want the bot to do events! (Moderation)
- Tags - Add tags for your members. (E.g FAQ)
- Ticket System - Support tickets for your server!
- Currency - Convert your money currency to another currency!
- You can now edit your messages to correct a misspell command. (e.g k!hekp > k!help)
- Premium has arrived. Please do k!premiuminfo for more details.

### Improvements

- Everything has been reworked and Improved
