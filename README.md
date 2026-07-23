# GDPS antiraid
Anti-raid for pre-1.9 and 2.0+ GDPSs
(currently only supports [MegaSa1nt's GMDprivateServer fork](https://github.com/MegaSa1nt/GMDprivateServer)
> [!IMPORTANT]  
> I highly recommend you activate hcaptcha and turn off the reactivation of accounts (E-mail verification)

this is what this modification does:
- Adds rate limits (configurable)
- Blocks invalid UDIDs
- Blocks users with impossibly high star counts
- Blocks level names that are valid base64
- Blocks levels with "realcq" or "furrycq" in the name
- Logs raid attempts
- Removes like bots
- Removes comment bots
- Removes account spam

if you want to make changes, feel free to submit a pull request. for feature requests or bug reports, open an issue.

## Setup
download the latest [release](https://github.com/Wubba-jpeg/gdps-antiraid/releases) and paste everything in your GDPS folder
configure everything in config/raidfix.php

## Planned features
- none at this time.
