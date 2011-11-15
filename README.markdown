# ScreenCapLoad

This command line utility launches Mac OSX screen capture in interactive
mode (select a region or press space to toggle window capture), captures
a portion of your screen, trims and re-compresses the captured image,
uploads it to imgur service and copies the full size image URL to your
clipboard.


## API key

You need an API key from imgur. This is required to use the
[imgur API](http://api.imgur.com/resources_auth).

You can get [register your application](http://imgur.com/register/api_anon)
and get your own API key. It allows you to upload up to 100 images per hour.


## Config file

For easier use, you can store your key in a config file named ~/.imgur
The script will use command line attribute first and fallback to the config
file otherwise.

Config file syntax is pretty simple :

    7d8ca1d32ca3daca123

## OSX Integration

You can use this script via a keyboard shortcut in many ways :

- Create a system-wide service with Automator, that launches screencapload
- Create a keyboard shortcut in Alfred App that triggers an Alfred Action that launches screencapload