# GDPS antiraid
Anti-raid for pre-1.9 GDPSes
(currently only supports [MegaSa1nt's GMDprivateServer fork](https://github.com/MegaSa1nt/GMDprivateServer)
In its current state, it's pretty barebones. Here's what it does:
- Adds rate limits (configurable)
- Blocks invalid UDIDs
- Blocks users with impossibly high star counts
- Blocks level names that are valid base64
- Blocks levels with "realcq" or "furrycq" in the name

if you want to make changes, feel free to submit a pull request. for feature requests or bug reports, open an issue.

## Setup
Simply copy the entire incl/ folder and config/ folder to your gdps.
configure everything in config/raidfix.php

## Planned features
- removal of like bots
- removal of comment spam bots
- removal of account spam bots
- discord webhook for logs
- removal of level reupload raids
 <small> (if those still exist)</small>
