---
icon: /static/twitch-icon.svg
order: 1000
---
# Stream Alerts

## Overview

Stream Alerts is a feature that enables you to set up notifications for when a streamer goes live on Twitch. This feature is advantageous for streamers who wish to alert their community when they commence streaming.

## Commands

+++ Slash

| Name                              | Example                        | Usage                                                                 |
|-----------------------------------|--------------------------------|-----------------------------------------------------------------------|
| twitch add<br>`Manage Guild`      | `/twitch add`                  | Allows you to add streamers to the notification list.                 |
| twitch list                       | `/twitch list`                 | Allows you to view the list of streamers on the notification list.    |
| twitch remove<br>`Manage Guild`   | `/twitch remove <twitch_name>` | Allows you to remove streamers from the notification list.            | 


+++ Prefix

| Name                              | Example                        | Usage                                                                 |
|-----------------------------------|--------------------------------|-----------------------------------------------------------------------|
| twitch add<br>`Manage Guild`      | `!twitch add`                  | Allows you to add streamers to the notification list.                 |
| twitch list                       | `!twitch list`                 | Allows you to view the list of streamers on the notification list.    |
| twitch remove<br>`Manage Guild`   | `!twitch remove <twitch_name>` | Allows you to remove streamers from the notification list.            |
+++

### Setup Stream Alerts

+++ twitch add

| Description                                                                                                                                                                                                                 |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| This command adds a Twitch user to the list. You will need to provide the `twitch name`, `channel id` (where notifications are sent), and `live message`. Buttons are available to explain the Live Message placeholders.   |

+++ twitch list

| Description                                                                                  |
|----------------------------------------------------------------------------------------------|
| This command displays all members who are part of the Twitch notifications in that server.   |

+++ twitch remove

| Description                                                                                                                                                                |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| This command removes any user from the Twitch list in that server. You will need to provide the `twitch_name` argument, which is displayed in the `twitch list` command.   |
+++