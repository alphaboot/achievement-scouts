`app` can be an app name, alias, or an appid.  
`user` can be a SteamID64 or custom url.

| Command | Description |
| -------------------------------------------- | - |
| `.c <app>` | Returns curation for `app`. |
| `.newalias <app> >> <alias>` | Adds `alias` to `app`. |
| `.remalias <alias>` | Removes `alias` stored on bot. |
| `.dc <app> [>> <curator_id>]` | Removes curation from curators, hides it on the bot database, and archives it on Discord.<br>`curator_id` is optional unless the same app is curated on multiple curators. |
| `.author <curator_id> <app> >> <user>` | Changes the author of a curation to `user`. |
| `.uc <app> [>> <curator_id>]` | Updates a curation.<br>`curator_id` is optional unless the same app is curated on multiple curators. |
| `.link <steam_id>` | Links a Steam account to your Discord username on the bot.<br>`steam_id` can be a SteamID64 or custom url. |
| `.linked [<discord_id>]` | Returns accounts linked to `discord_id`.<br>`discord_id` can be a Discord username or ID. Omitting `discord_id` displays details about yourself. |
| `.me <app>` | Returns your achievement progress for `app`.<br>Query multiple `apps` by separating them with semicolon. |
| `.ach <user> >> <app> ` | Returns `user's` achievement progress for `app`.<br>`user` can also be a Discord username or ID if linked. Query multiple `apps` by separating them with semicolon. |
