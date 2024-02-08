Database for Pazer's BotDetector. Download the original build [here](https://github.com/PazerOP/tf2_bot_detector/releases/tag/1.2.1.934).
Usage instructions below:

## Correcting Steam API
Once you have BotDetector open, click **Settings** and then **Service Integrations**. Change Steam API mode to `direct`, and then paste your Steam API key into the box. You can get your Steam API key [here](https://steamcommunity.com/dev/apikey)

## Using This Database
After that, close BotDetector and nagivate to your BotDetector installation folder, then the `/cfg/` subfolder (should look something like this: `tf2-bot-detector_x86-windows_1.2.1.934_Release\cfg`).

Once you're there, open `rules.official.json` and replace the URL after `update_url` with https://raw.githubusercontent.com/SisterHailey/tf2bd2/main/rules.official.json so that it looks like this:
`"update_url": "https://raw.githubusercontent.com/SisterHailey/tf2bd2/main/rules.official.json"`

Do the same for `playerlist.official.json` and replace its `update_url` with this: https://raw.githubusercontent.com/SisterHailey/tf2bd2/main/playerlist.official.json

## Almost Done!
Now whenever you want to play TF2, just open BotDetector, launch TF2 from there, and then click **File > Reload Playerlists/Rules**. You *must* do this, otherwise your client will not sync to the latest version of the database.
