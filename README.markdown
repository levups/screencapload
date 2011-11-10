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