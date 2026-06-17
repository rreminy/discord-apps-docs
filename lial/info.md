# Lial
## Introduction
Lial is a bot allowing for relays to be managed by holding, releasing, cancelling or deleting relay messages.

It works by adding reaction to our FIlo relay bot messages, which can then be used for relay controls. The controls allow the bot to:
- Release the relay immediately.
- Hold or cancel the relay.
- Deleting the relay should it be deemed inaccurate.
Should none of the reaction be clicked Lial will release the relay after a set time have passed.

Use cases for this bot include crowd and congestion control, and to give time to organize.

## Privacy Policy
### Data Collection and Retention
No data is collected nor retained by this app.

### Logging
Logging is performed into a private discord channel for moderation purposes, which are to ensure its functionality are not abused in unintended ways.

## Intents
### Why do you need the Message Content intent?
The relay message contents from Filo are parsed, which once released are then copied into a new post at a public relay channel for our discord members.

No user messages are processed.
