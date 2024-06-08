---
icon: rocket
order: 1000
---
# Getting Started
!!!warning
Do not actually type out `<` `>` `[` `]`, etc.
!!!

!!!info
The user permissions required to execute certain commands will be listed under the command name.
Example:

/ban

`Ban Members`

Each category of commands has its own page, so you won't miss anything!


| Syntax                        | Definition                                                                                                |
|-------------------------------|-----------------------------------------------------------------------------------------------------------|
| `<example>`                   | This argument is required.                                                                                |
| `[example]`                   | This argument is optional.                                                                                |
| `[example='No reason given']` | This argument is optional, but has a default value. In this case, the default value is 'No reason given'. |
!!!


## Basic Setup

In the future, UniBot will feature a dashboard, allowing you to customize it without the need for commands!

Let's delve into how UniBot operates and its various features!

This documentation primarily uses `/` as the command prefix, but remember, UniBot supports custom prefixes, so don't get confused!

### Prefix
By default, UniBot's command prefix is `!`, and it also supports `/` slash commands.
To change UniBot's prefix, execute the `!config` or `/config` command. The bot will then send an embed message that you can read and use to configure various settings!

### Configurations

UniBot offers multiple commands for configuring different aspects, but the primary command for most configurations is `/config`.

To access these setup features, you must either be an admin or the server owner!

### Modlogs

Modlogs only track actions performed by UniBot, not those performed by other bots. To set up modlogs with UniBot, run the `/config` command, click on `Setup Configurations`, and then click on `Mod Channel`. After that, it will prompt you to specify a channel. Simply mention the desired channel, and UniBot will set it as the modlog channel!

### Logs

UniBot features a logging system that records all activities within your Discord server! By default, this feature is disabled. To enable it, run the `/config` command, click on `Setup Logging`, and follow the instructions. Just like with the config command, you can click a button, read its function, and then click the button to set it. It will ask for a channel, and once you mention the channel, it will set that channel for that specific logging category! To reset the config, repeat the previous steps but this time click on `Config`, and you'll find a reset button there!

### Join Role

UniBot offers a join role feature, which assigns a role to members when they join! You can set this up by using the `/config` command, clicking on `Setup Configurations`, and then clicking on `Join Role`. Then, mention the role you want to assign to new members!

!!!danger Reminder
The bot cannot assign a role to a member if it doesn't have the `Manage Roles` permission. Furthermore, it cannot assign a role that is higher in the hierarchy than its own highest role. Ensure that UniBot's role is higher than the role you want to assign to others, and that UniBot has the `Manage Roles` permission.
!!!