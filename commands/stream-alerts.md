---
icon: /static/twitch-icon.svg
order: 1000
---
# Stream Alerts

## Overview

Stream Alerts is a feature that allows you to set up alerts for when a streamer goes live on Twitch. This feature is beneficial for streamers who want to notify their community when they start streaming.

## Commands

+++ Slash

| Name                              | Example                        | Usage                                                               |
|-----------------------------------|--------------------------------|---------------------------------------------------------------------|
| twitch add<br>`Manage Guild`      | `/twtich add`                  | Allows you to add streamers to the notifications list!              |
| twitch list                       | `/twitch list`                 | Allows you to view the list of streamers in the notifications list! |
| twitch remove<br>`Manage Guild`   | `/twitch remove <twitch_name>` | Allows you to remove streamers from the notifications list!         | 


+++ Prefix

| Name                              | Example                        | Usage                                                               |
|-----------------------------------|--------------------------------|---------------------------------------------------------------------|
| twitch add<br>`Manage Guild`      | `!twtich add`                  | Allows you to add streamers to the notifications list!              |
| twitch list                       | `!twitch list`                 | Allows you to view the list of streamers in the notifications list! |
| twitch remove<br>`Manage Guild`   | `/twitch remove <twitch_name>` | Allows you to remove streamers from the notifications list!         |
+++

### Setup Stream Alerts

+++ Twitch Add

| Description                                                                                                                                                                                                |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| This adds a twitch user to the list, you will have to provide `twitch name`, `channel id` (where notifications go), and `live message`. There are buttons that will explain the Live Message placeholders! |

+++ Twitch List

| Description                                                                     |
|---------------------------------------------------------------------------------|
| This shows all members who are part of the twitch notifications in that server! |

+++ Twitch Remove

| Description                                                                                                                                                  |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| This will remove anyone in the twitch list in that server! You will need to provide the `twitch_name` argument, which is shown in the `twitch list` command! |
+++
