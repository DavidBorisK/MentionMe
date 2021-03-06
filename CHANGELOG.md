Change Log
===

## v0.4.2 (01/03/2017)
#### Added Features:
* Integration with VentureChat channels.

## v0.4.1 (01/03/2017)
#### Fixes:
1. Fixed integration with DeluxeChat to work with placeholders.

## v0.4.0 (01/03/2017)
#### Added Features:
* Full integration with DeluxeChat.

#### Fixes:
1. Completely recoded the plugin to be more modular, just in case more chat plugin hooks are needed.

## v0.3.4 (12/30/2016)
#### Added Features:
* Auto Tab Completions.

#### Fixes:
1. Fixed a problem where text would be reset to white instead of what the original chat color was.
2. Updated the reload command to `/mentionme` instead of `/mentionmereload`.

## v0.3.3 (12/28/2016)
#### Fixes:
1. Removed the org.bukkit package from the jar.
2. Fixed `selfnotify-tag` bug, it should work properly now.

## v0.3.2 (12/28/2016)
#### Fixes:
1. Fixed bug in which a sound wouldn't play for the target if you had `selfnotify-tag` set to false.

## v0.3.1 (12/28/2016)
#### Added Features:
* Added toggle for self-notification.

## v0.3.0 (12/28/2016)
#### Added Features:
* Primative Hashtag support (colors only, no trending yet).
* Added toggles for the `@everyone` tag.

#### Fixes:
1. Fixed error checking repeating the message to the user.
2. `@everyone` doesn't ping the user who sent it anymore.

## v0.2.0 (12/27/2016)
#### Added Features:
* Title & Subtitle support.
* Made config more readable and added documentation (Please delete and reload the config).
* Sound can now be toggled off.

#### Fixes:
1. Fixed the `onDisable` message.

---

## v0.1.0 (12/27/2016)
*Initial Commit*
