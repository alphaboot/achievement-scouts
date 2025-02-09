`App` can be an app name, alias, or an appid.

| Command | Description |
| -------------------------------------------- | - |
| `.c <app>` | Returns curation for `app`. |
| `.newalias <app> >> <alias>` | Adds `alias` to `app`. |
| `.remalias <alias>` | Removes `alias` stored on bot. |
| `.dc <app> [>> <curator_id>]` | Removes curation from curators, hides it on the bot database, and archives it on Discord.<br>`curator_id` is optional unless the same app is curated on multiple curators. |
| `.author <curator_id> <app> >> <new_author>` | Changes the author of a curation to `new_author`. `new_author` is a SteamID64 or custom url. |
| `.uc <app> [>> <curator_id>]` | Updates a curation.<br>`curator_id` is optional unless the same app is curated on multiple curators. |
| `.link <steam_id>` | Link your Steam account to your Discord account on the bot. `steam_id` is a SteamID64 or custom url. |
| `.linked [<user>]` | Shows details on accounts linked to `<user>`. `<user>` is a Discord username or Discord user ID. |
