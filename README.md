# ripper
Checks YT Channels and Bitchute channels for new videos and downloads them quickly

This is considerably faster than giving `youtube-dl` the channel URIs directly.
This script can use the YouTube Data API v3 if available, but has a fallback if either:

- no API Key is given
- the Data quota for the day has been exceeded

Bitchute can also be used with this script.
This part of the script is quite generic and could easily be adjusted for other websites.

See the documentation inside the `ripper` file for more information.

## Install
After `git clone`ing this repo, run the helper `installer`

```sh
./installer install
```

## Features to come

- Odysee support
- Peertube support -> could just be done via RSS feeds
