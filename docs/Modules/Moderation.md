title: Moderation 
description: All commands of the moderation module

# Moderation commands

* `ban {@User/UserID} {reason}` - Bans a user from the Discord server with a certain reason (Needed permissions: BAN_MEMBERS)
* `clear {amount of messages between 2 and 100}` - Deletes for you the last X messages that were sent in the current channel (Needed permissions: MANAGE_MESSAGES)
* `currentlybanned [@USER/UserID]` -  (Needed permissions: KICK_MEMBERS)
* `currentlymuted [@USER/UserID]` -  (Needed permissions: KICK_MEMBERS)
* `kick {@User} {reason}` - Kick a user from the Discord server with a certain reason (Needed permissions: KICK_MEMBERS)
* `mute {@User} {time (d, h, m, s)} {reason}` - Mutes a user for a certain time (Needed permissions: KICK_MEMBERS)
* `softban @User {days} {reason}` - Bans a user and deletes his messages of the last X days (max 14 days). After that, he will be unbaned immediately! (Needed permissions: BAN_MEMBERS)
* `temporaryban {@User/UserID} {time (d, h, m, s)} {reason}` - Bans an user temporary (Needed permissions: BAN_MEMBERS)
* `unban {userID} {reason}` - Unban a user from the Discord server with a certain reason (Needed permissions: BAN_MEMBERS)
* `unmute {@User} {reason}` - Unmutes a user (Needed permissions: KICK_MEMBERS)
* `warn {@User/UserID} {reason}` - Warn a user on the Discord server with a certain reason (Needed permissions: KICK_MEMBERS)
* `warnlog [@User]` - Shows you the warnlog from you or another user (Needed permissions: KICK_MEMBERS)