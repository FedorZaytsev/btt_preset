# Better Touch Tool preset with Yandex.Music
Just another preset for Better touch tool, but this time with support for Yandex.Music. This preset aim is to make touch bar close to old F1-F12 bar on old macbooks, but with some new features.


## Installation
If you want to have only triggers (only buttons on touchbar, but not the better touch tool settings) import `lobster_triggers.bttpreset`. If you just want everything to work then import `lobster_trigger_settings.bttpreset`.


## The preset contain
* Finder quick button
* Buttons for brightness up/down
* Yandex.Music support
* Current temperature
* Lock button (coffee button)
* Volume mute, lower, higher
* Battery status
* Time

![Preset](touchshot.png)

## Weather widget support
To run a weather widget you would probably need to register on [openweathermap.org](https://openweathermap.org/appid) and change `appid` from `dae3a235f3b0b168acec4955c801ca47` to you new API key (APPID).

Also you would likely need to download the following packages:
* https:\\itunes.apple.com\ru\app\json-helper-for-applescript\id453114608?l=en&mt=12
* https:\\itunes.apple.com\ru\pp\location-helper-for-applescript\id488536386?mt=12

## Yandex.Music support and limitations
This preset has a basic support for Y.Music. It can:
* Play/Pause
* Show current track
* Swipe 2 fingers left/right to next/previous track


However, there are some limitations:
* Works with Chrome browser only. It should work in Safari also, but you will need to change `Google Chrome` to `Safari` in the `Play/Pause` Button.
* If there are more than one tab of Y.Music is present only first one (from browser perspective) will interact.
* If no track is running, "play" will be shown as a name of a track.

## Acknowledge
This preset was made on base of vas3k's and toxblh's presets from [here](https://github.com/vas3k/btt-touchbar-presets). Also thanks vas3k for a great blog post [here](https://vas3k.com/blog/touchbar/).
