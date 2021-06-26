# ripper
Checks YouTube, Bitchute, and Peertube channels for new videos and downloads them quickly.

This is considerably faster than giving `youtube-dl` the channel URIs directly.
## YouTube
This script can use the YouTube Data API v3 if available, but has a fallback if either:

- no API Key is given
- the Data quota for the day has been exceeded

## Bitchute
Bitchute can also be used with this script.
This part of the script is quite generic and could easily be adjusted for other websites.

## Peertube
Peertube instances require the channel RSS feed URL to work.


See the documentation inside the `ripper` file for more information.

## Install
After `git clone`ing this repo, run the helper `installer`

```sh
./installer install
```

## Features to come

- Odysee support
