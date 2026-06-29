# Emerald

## Introduction
Emerald is a bot which keep track of server member roles for persistence should they decide to leave and rejoin servers.
This bot is fully configurable via /slash commands:
- `/config role` Configure an action to be taken for specific roles.
- `/config default_action` Configures a default action for all the server roles.
- `/config log` Allows configuring the log channel to be used for logging (optional).
- `/config log_restored` and `/configure log_saved` allows enabling and disabled the logging events.
- `/config log_dangerous_roles` Selects what to do for dangerous roles, which are roles containing dangerous permissions such as kick, ban, timeout, manage and admin permissions.
- `/config reset_roles` Resets configured roles to default.
- `/config show` Shows the current configuration.

Bot's source code can be found at: https://github.com/rreminy/RolesWarden


## Privacy Policy
### Data Collection and Retention
Server member roles tracked for persistence should they decide to leave and rejoin the servers this bot is installed at.
This data is retained until the bot is removed from the respective server.


### Logging
Basic logging is performed into a private discord channel for record purposes.


## Intents
### Why do you need the Guild Members intent?
The bot relies on the following events for its functionality:
- Guild Member Updated: Used to update the roles data for each user in the installed servers.
- Guild Member Added: Used to restore roles configured to be persisted when they rejoin servers the bot is installed at.
- Guild Member Removed: Used for logging providing feedback for moderators whenever a server member leave.
