---
icon: rocket
---
# Getting Started
!!!warning
Do not actually type out `<` `>` `[` `]` ect.
!!!

!!!info
The user permissions required to run certain commands will be under the command name.
Example:

/ban 

`Ban Members`

Each category of commands has their own page, so don't worry about skipping anything!


| Syntax                        | Definition                                                                                               |
|-------------------------------|----------------------------------------------------------------------------------------------------------|
| `<example>`                   | This argument is required.                                                                               |
| `[example]`                   | This argument is optional.                                                                               |
| `[example='No reason given']` | This argument is optional, but has a default value. In this case the default value is 'No reason given'. |
!!!


## Basic Setup

UniBot in the future will have a dashboard so you can customize it without using commands!

Now lets get started on how UniBot works and everything in it!

Most of this documentation will be using / as the prefix, but remember it does support prefix so don't get confused!

### Prefix
By default, UniBot's prefix is `!` as well as `/` slash commands. 
To change UniBot's prefix you need to run the command `!config` or `/config` in then you can read the embed it sends and you can configure multiple things inside of that one command!

### Configurations

Inside of UniBot, there are multiple commands to configure multiple things, but the main command to configure almost everything is `/config`.

For all of these setup features, you will need admin or be the owner of the server!


### Modlogs

Modlogs will only log things UniBot does, this will NOT log what other bots do. To setup modlogs inside of UniBot, just run `/config`, then click `Setup Configurations`, then click `Mod Channel`, after you have done that, it will ask for what channel, just mention the channel you are wanting then UniBot will set it to be that channel!

### Logs

UniBot has a logging system to log everything that happens inside of your discord server! By default UniBot will have this disabled. To enable it you can do `/config`, then click `Setup Logging`, it explains what each thing is. Just like config, you can just click a button read what it does, then click the button to set it, it will ask for which channel, you just mention the channel and it sets it to be that channel for that logging category only! To reset the config, just do the previous steps but this time click `Config` and it will have a reset button in there!

### Join Role

UniBot has a join role feature, when a member joins they are given a role! You can set this up with using `/config`, then click `Setup Configurations` and then click `Join Role` then mention the role you want to be the join role!

!!!danger Reminder
The bot cannot assign a role to a member if it lacks the `Manage Roles` permission. Additionally, the bot cannot assign a role that is higher in the hierarchy than its own highest role. Ensure that UniBot's role is higher than the role you wish to assign to others, and that UniBot has the `Manage Roles` permission.
!!!
