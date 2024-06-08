---
icon: /static/antialt-icon.png
order: 800
---
# Birthdays

## Overview

The Birthdays feature enables you to set up birthday notifications for yourself. This feature is advantageous for members who wish to receive reminders on their birthday.

## Commands

+++ Slash

| Name              | Example                        | Usage                                                                                         |
|-------------------|--------------------------------|-----------------------------------------------------------------------------------------------|
| birthday set      | `/birthday set`                | Allows you to set your birthday in the bot and receive a notification on your birthday.       |
| birthday delete   | `/birthday delete`             | Allows you to delete all your stored birthday data.                                           |
| birthday check    | `/birthday check [member]`     | Allows you to check your own birthday or that of others.                                      |
| birthday common   | `/birthday common`             | Finds users who share the same birthday as you.                                               |
| birthday stats    | `/birthday stats`              | Provides the most common, least common, and average birthdays.                                |
| birthday ages     | `/birthday ages`               | Provides the average age, youngest, and oldest user.                                          |
| birthday upcoming | `/birthday upcoming [days=10]` | Provides upcoming birthdays within a specified number of days.                                |


+++ Prefix

| Name              | Example                        | Usage                                                                                         |
|-------------------|--------------------------------|-----------------------------------------------------------------------------------------------|
| birthday set      | `!birthday set`                | Allows you to set your birthday in the bot and receive a notification on your birthday.       |
| birthday delete   | `!birthday delete`             | Allows you to delete all your stored birthday data.                                           |
| birthday check    | `!birthday check [member]`     | Allows you to check your own birthday or that of others.                                      |
| birthday common   | `!birthday common`             | Finds users who share the same birthday as you.                                               |
| birthday stats    | `!birthday stats`              | Provides the most common, least common, and average birthdays.                                |
| birthday ages     | `!birthday ages`               | Provides the average age, youngest, and oldest user.                                          |
| birthday upcoming | `!birthday upcoming [days=10]` | Provides upcoming birthdays within a specified number of days.                                |
+++

### Set Your Birthday

+++ birthday set

| Description                                                                                                                                                                         |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| This will set your birthday based on DOB, Timezone and that's all!<br/><br/>Example being `07/12/1990` then `America/Chicago`, there are no arguments, you set it up with messages! |

+++ birthday delete

| Description                                                                                                                                     |
|-------------------------------------------------------------------------------------------------------------------------------------------------|
| This will delete all your data in birthdays, meaning you won't receive anymore notifications after you do it unless you re-setup your birthday! |

+++ birthday check

| Description                                                                        |
|------------------------------------------------------------------------------------|
| This will show members birthdays, you can get your friends birthday if you wanted! |

+++ birthday common

| Description                                                                                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| This will get users who share the same birthday as you! You can now see if you are special and see if you are the only one with that birthday so far in the bot! |

+++ birthday stats

| Description                                                                                                                                               |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| This will get the most common, least common and average birthdays, showing all stats about birthdays so you can see whats the most popular if you wanted! |

+++ birthday ages

| Description                                                                                                           |
|-----------------------------------------------------------------------------------------------------------------------|
| This will get the average, youngest and oldest user stored in the database, maybe someone is 80 years old? Who knows! |

+++ birthday upcoming

| Description                                                                                                 |
|-------------------------------------------------------------------------------------------------------------|
| This will get all upcoming birthdays based on the argument `days` which default is `10`, but the max is 30! |
+++

