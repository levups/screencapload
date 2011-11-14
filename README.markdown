# ScreenCapLoad

This command line utility launches Mac OSX screen capture in interactive
mode (select a region or press space to toggle window capture), captures
the image as an temporary PNG file, uploads it to imgur service and copies
the original image URL to your pasteboard.

The temporary image is deleted after successfull upload.

## API key

You need an API key from imgur. This is required to use the
[imgur API](http://api.imgur.com/resources_auth).

You can get [register your application](http://imgur.com/register/api_anon)
and get your own API key. It allows you to upload up to 100 images per hour.

## Config file

For easier use, you can store your key in a config file named ".screencapload.yml"
located in your home directory. The script will search for the file /Users/your_user_name/.screencapload.yml and fallback to command line attribute
otherwise.

Syntax is pretty simple :

```yaml
imgur_api_key: "12345..."
```

## OSX Integration

You can use this script via a keyboard shortcut in many ways :

- Create a system-wide service with Automator, than launches screencapload
- Create a keyboard shortcut in Alfred App that triggers an Alfred Action