## ISgood Docs

https://acatiadroid.github.io/docs/

⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼

**Want to advertise your bot & add it to a public server?**

Join https://discord.gg/p5bURjs and run `!addbot {invite} {reason}`. Change {invite} to your bots invite link and it will get reviewed by moderators.

⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼


This site is for help with the Discord bot ISgood.

This documentation uses certain formatting to represent certain information, as shown below:
```
[ ] means the arguemnt IS NOT required. I.E [reason]
```
or
```
< > means the argument IS required. I.E <member>
```
and
```
| means a command alias. I.E [command|subcommand]
```
**Do not literally type out the \[ ] or < > or | when running the command.**

### Useful links

[Support server](https://discord.gg/p5bURjs)

[Invite the bot](https://discord.com/oauth2/authorize?client_id=720785136425369652&permissions=8&scope=bot)

[Documentation (this page)](https://acatiadroid.github.io/docs/)

[Top.gg page](https://top.gg/bot/720785136425369652) (recommended)

To find a specific command, hit `Ctrl + F` and search your keyword.

```
This version of the documentation is only temporary and will be completely updated soon in HTML.
```

### Moderation commands

**All commands require a certain permission or a modrole to use.**

```
ban
Bans a member.
Requires BAN_MEMBERS permission.
Commands: "ban", "b"
Usage: ".ban <user> [delete_days] [reason]
Example: ".ban @Dyno Bye"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
massban
Bans multiple members out of the server.
Requires BAN_MEMBERS permission.
Commands: "massban", "mb"
Usage: ".massban|mb <@user> <@user>... [delete_days] [reason]
Example: ".massban @Dyno @MEE6 Bad"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
masskick
Kicks multiple members out of the server.
Requires KICK_MEMBERS permission.
Commands: "masskick", "mk"
Usage: ".masskick|mk <@user> <@user>... [reason]
Example: ".massban @Dyno @MEE6 Bad"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
kick
Kicks a member.
Requires KICK_MEMBERS permission.
Commands: "kick", "k"
Usage: ".kick <user> [reason]"
Example: ".kick @MEE6 Bye"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
nick
Changes the nickname of a user.
Requires MANAGE_NICKNAMES permission.
Commands: "nick"
Usage: ".nick <user> <new-nick>"
Example: ".nick @acatia Developer"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
slowmode
Changes the slowmode of whichever channel it's used in.
Requires MANAGE_MESSAGES permission, for that channel, where it's used.
Commands: "slowmode", "sm"
Usage: ".slowmode <amount>"
Example: ".slowmode 5"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
purge
Purges messages in whichever channel it's used in.
Requires MANAGE_MESSAGES permission, for that channel, where it's used.
Commands: "purge"
Usage: ".purge <amount>"
Example: ".purge 10"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
unban
Unbans a user
Requires BAN_MEMBERS permission.
Commands: "unban", "ub"
Usage: ".unban <username#0000>"
Example: ".unban Cosmic#0022"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
mute
Perm-mutes a member.
Requires KICK_MEMBERS permission.
Commands: "mute", "m"
Usage: ".mute <member> [reason]"
Example: ".mute @Toby Spam."
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
tempmute
Changes the nickname of a user.
Requires KICK_MEMBERS permission.
Commands: "tempmute", "tm", "timemute"
Usage: ".mute <member> [length] [reason]"
Example: ".mute @Toby 3h Read the rules."
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
unmute
Unmutes a Member.
Requires KICK_MEMBERS permission.
Commands: "unmute", "um"
Usage: ".unmute <member>"
Example: ".unmute @Toby"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
lock
Locks down a channel.
Requires MANAGE_CHANNELS permissions
Commands: "lock"
Usage: ".lock [channel]
Example ".lock #general Raid", ".lock Spam"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
lockdown
Locks down the server
Requires MANAGE_SERVER permissions
Commands: "lockdown"
Usage: ".lockdown [reason]"
Example ".lockdown Mass raid"
```

### Configuration

**All commands here require "MANAGE_SERVER" permission. Modroles won't work.**
```
setprefix
Sets the prefix
Commands: "setprefix"
Usage: ".setprefix <new-prefix>"
Example: ".setprefix !"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
lockannounce
Sets a channel that a message will get sent to when the "lockdown" command is used.
Commands: "lockannounce"
Usage: ".lockannounce <chnl>"
Example: ".lockannounce #general"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
suggestionchannel
Sets the suggestion Channel (also enables suggestions)
Commands: "suggestchannel", "suggestionchannel"
Usage: ".suggestionchannel <channel>"
Example: ".suggestionchannel #suggestions"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
disablesuggest
Disables suggestions
Commands: "disablesuggest"
Usage: ".disablesuggest"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
enablereddit
Enables the reddit command
Commands: "enablereddit"
Usage: ".enablereddit"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
disablereddit
Disables the reddit command
Commands: "disablereddit"
Usage: ".disablereddit"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
modrole
Shows the current- or sets a- modrole.
Commands: "modrole"
Usage: ".modrole [role]"
Example: ".modrole @Moderators"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
modrole_delete
Deletes the current modrole
Commands: "modrole_delete", "modrole_disable"
Usage: ".modrole_delete"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
muterole
Shows the current mute role, creates a mute role or sets a mute role.
Commands: "muterole", "muterole set", "muterole create"
Usage: ".muterole", "muterole set <role>", "muterole create"
Example: ".muterole set @Muted"
```

### Miscellaneous

**Commands that are able to be run by *almost* everyone**
```
coinflip
Coin flip, what did ya expect? (returns heads or tails)
Commands: "coinflip"
Usage: ".coinflip"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
invite
Gives you the bot's invite!
Commands: "invite"
Usage: ".invite"
Example: ".invite"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
poll
Creates a poll with thumbs up and down reactions.
Commands: "poll"
Usage: ".poll <content>"
Example: ".poll Pizza is good, right?!"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
emojify
Creates an emoji out of your attachment.
Requires MANAGE_EMOJI permission
Commands: "emojify", "addemote"
Usage: ".emojify <name> <attachment>"
Example: ".emojify name <attachment>" replace <attachment> with an attachment to the message.
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
patreon
Links ISgood's patreon
Commands: "patreon", "patron"
Usage: ".patreon"
```

### Custom Embeds

**Creates custom embeds that can have anything you want in.**
```
embed
Creates a custom embed. (interactive guide)
Requires MANAGE_MESSAGS permission, in that channel of whichever it's used in.
Commands: "embed"
Usage: ".embed"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
editembed
Edits a pre-existing embed sent by the bot. (interactive guide)
Requires MANAGE_MESSAGS permission.
Commands: "editembed"
Usage: ".editembed"
```

### Role Management

**These commands require a modrole or "manage_roles" permission.**
```
addrole
Adds a role to the user specified.
Commands: "addrole", "role"
Usage: ".addrole <member> <role>"
Example: ".addrole @acatia#0001 @Moderator"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
removerole
Removes a role for the user specified.
Commands: "removerole", "rrole"
Usage: ".removerole <member> <role>"
Example: ".remove role @acatia#0001 @Moderator"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
autorole
Gives specified role(s) upon joining.
Commands: "autorole", "ar"
Usage: ".autorole"
Example: ".autorole"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
autorole add 
Adds a role to the autorole.
> Note: non-premium servers can have 6 autoroles, whereas premium servers can have 15.
Commands: "autorole remove"
Usage: ".autorole set <role>"
Example: ".autorole add @Unverified"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
autorole remove 
Removes a role from the autorole.
Commands: "autorole remove"
Usage: ".autorole remove <role>"
Example: ".autorole remove @Unverified"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
autorole ignorebots/unignorebots 
Ignores/unignores bots from being affected by autorole.
Commands: "autorole ignorebots", "autorole unignorebots"
Usage: ".autorole ignorebots", ".autorole unignorebots"
Example: ".autorole ignorebots", ".autorole unignorebots"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
autorole disable 
Disables autorole, this will delete ALL data with autorole.
Commands: "autorole ignorebots", "autorole unignorebots"
Usage: ".autorole ignorebots", ".autorole unignorebots"
Example: ".autorole ignorebots", ".autorole unignorebots"
```

### Information commands
```
avatar
Gets the avatar of the user specified or yourself
Commands: "avatar", "av"
Usage: ".avatar [member]"
Example: ".av @acatia"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
whois
Gets some informaton about the specified user or you
Commands: "whois"
Usage: ".whois [member]"
Example: ".whois"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
serverinfo
Shows some server information
Commands: "serverinfo", "si"
Usage: ".serverinfo"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
ping
Shows some the bots ping, for the websocket and rest latency.
Commands: "ping"
Usage: ".ping"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
covid
Shows some statistics for covid-19. If [country] is not given, it will show global stats.
Commands: "covid", "cv", "coronavirus", "corona"
Usage: ".covid", ".covid uk"
```

### Suggestions

These commands will only work if suggestions are enabled. (`suggestchannel` / `disablesuggest`)

```
suggest
Commands: "suggest"
Usage: ".suggest <content>"
Example: ".suggest Make us able to follow #announcements!"
```

### Reddit

**Retrieves a random post from a subreddit**
```
reddit
Gets a random post from the specified sub-reddit.
REQUIRES ".enabledreddit" TO BE RAN, without ".disablereddit" have been ran after, AND NEEDS TO BE IN A NSFW CHANNEL!
Commands: "reddit"
Usage: ".reddit <sub-reddit>"
Example: ".reddit ihadastroke"
```

### Starboard

**Commands for configuring the starboard**

WARNING: Starboard is currently slightly buggy. Please do the following:
- set the starboard channel
- set the emoji
- set the threshold
- toggle the starboard
- set the channel again
```
starboard channel
Sets a starboard channel
Requires MANAGE_SERVER permission.
Commands: "starboard channel", "sb channel"
Usage: ".starboard channel #starboard"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
starboard toggle
Enables or disables the starboard
Requires MANAGE_SERVER permission.
Commands: "starboard toggle", "sb toggle"
Usage: ".starboard toggle"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
starboard emoji
Sets the starboard emoji
Requires MANAGE_SERVER permission.
Commands: "starboard emoji", "sb emoji"
Usage: ".starboard emoji ⭐"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
starboard threshold
Sets the amount of reactions required to get posted to the starboard. (note that self starring doesn't work)
Requires MANAGE_SERVER permission.
Commands: "starboard threshold", "sb threshold", "starboard thresh", "starboard limit"
Usage: ".starboard thresh 3"
```
 
### Music

```
join
Joins a voice channel.

leave
Clears the queue and leaves the voice channel.

loop
Loops the currently playing song.

now
Displays the currently playing song.

pause
Pauses the currently playing song.

play <search>
Plays a song.

queue [page=1]
Shows the player's queue.

remove <index>
Removes a song from the queue at a given index.

shuffle
Shuffles the queue.
skip
Vote to skip a song. The requester can automatically skip.

summon [channel]
Summons the bot to a voice channel.
```

### Reaction roles

**Let members assign their own roles by clicking reactions!**

Commands below have the name `reactionroles`, but for the sake of readability, they will use the subcommand `rr`.

NOTE: You must set the reaction roles channel before anything else or it WILL NOT work.

⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
rr channel
Sets the reaction roles channel.
Requires MANAGE_SERVER permission.
Commands: "rr channel <channel>"
Usage: ".rr channel #get-roles"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
rr toggle
Toggles reaction roles on/off.
Requires MANAGE_SERVER permission.
Commands: "rr toggle"
Usage: ".rr toggle"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
rr remove
Removes a reaction role by selecting the emoji.
Requires MANAGE_SERVER permission.
Commands: "rr remove <emoji>"
Usage: ".rr remove 🟢"
```

### Tickets

Allow members to have private interactions with support team.

⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
ticket
Creates a ticket channel with an optional reason
Commands: "ticket [reason]"
Usage: ".ticket I need help"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
ticket addaccess
Adds a role that are allowed to interact with tickets.
Requires MANAGE_SERVER permission.
Commands: "ticket addaccess <role>"
Usage: ".ticket addaccess @Support"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
ticket close
Closes a ticket channel. Will not work on non-ticket channels.
Requires you to be the ticket creator, or have an access role, or a modrole.
Commands: "ticket close"
Usage: ".ticket close"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
ticket removeaccess
Removes an access role.
Requires MANAGE_SERVER permission.
Commands: "ticket removeaccess <role>"
Usage: ".ticket removeaccess @Helper"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
ticket setup
Sets up the ticket channel. This command must be done beforehand.
Requires MANAGE_SERVER permission.
Commands: "ticket setup"
Usage: ".ticket setup"
```
⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼⎼
```
ticket disable
Disables tickets. To re-enable, you must do the "ticket setup" command.
Requires MANAGE_SERVER permission.
Commands: "ticket disable"
Usage: ".ticket disable"
```

### Purge

```
purge all [search=100]
Removes all messages.

purge bots [search=100] [prefix]
Removes a bot user's messages and messages with their optional prefix.

purge embeds [search=100]
Removes messages that have embeds in them.

purge emojis [search=100]
Removes all messages containing custom emoji.

purge files [search=100]
Removes messages that have attachments in them.

purge images [search=100]
Removes messages that have embeds or attachments.

purge mentions [search=100]
Removes messages that have mentions in them.

purge reactions [search=100]
Removes all reactions from messages that have them.

purge user <member> [search=100]
Removes all messages by the member.

purge users [prefix] [search=100]
Removes only user messages.
```

### Credits

acatia#0001 - Project Lead & bot developer
Cosmic#0022 - Bot artwork & more
tobiO0310#0001 - Documentation & more
All moderators
All supporters

Docs last updated: 25th feb, 2021 
