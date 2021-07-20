---
title: Home
weight: -1
---

# Welcome!

Thanks for checking out the documentation. LowResNickel was made by Ari Taylor, who can be found in a variety of locations:

 - [AriCodes.net](https://aricodes.net)
 - [Twitter (@realwillowtw)](https://twitter.com/realwillowtw)
 - [Twitch (@WillowTheWhisperSR)](https://twitch.tv/willowthewhispersr)
 - [Patreon](https://www.patreon.com/aricodes)

If you want your own custom bot, feel free to reach out to them!

# Core concepts

Using LowResNickel is fairly straightforward. There's two classifications of commands: system commands, and user commands.

## System Commands

System commands are defined in LRN's code and cannot be modified by other commands. These are typically restricted to VIPs, moderators, or just Nickel. They also do not show up in the [commands list](https://commands.exotichorse.com/lowresnickel). Because of their static nature, they'll be listed here in the documentation.

## User Commands

User commands are stored in LRN's database and can be modified by chatters with sufficient privileges. Permissions are broken as follows:

 - User (0)
 - VIP (1)
 - Moderator (2)
 - Nickel themselves (3)

...with each one of those levels having more power than the last. Moderators and above can add and delete commands, change the permissions level and cooldown time of existing commands, and typically are not subject to command cooldowns. Nickel has absolute authority over all commands, system or user, and is never subject to cooldowns.
