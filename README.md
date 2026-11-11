# sin Download Manager

A Windows download manager built for Iranian internet. It tells you which downloads are half-price, grabs every part of a game in one go, extracts archives on its own, and downloads torrents without a VPN.

**[Download the latest version](https://github.com/siinsiw/sin-download-manager/releases/latest)**: get `sinDL_…_windows_x64.exe` and run it.

## What it does

- **Half-price detection:** shows whether the server that actually sends a file is inside Iran, following redirects all the way to the final CDN.
- **Every part at once:** paste a download page and it finds all the parts, the archive password and the mirror links. When the page offers several releases (ElAmigos, RUNE, FitGirl…), each is listed with its size and you pick the ones you want, down to single parts. It also takes a text file of links, links you copied, or every picture on a page.
- **Auto extract and repair:** when the last part arrives, the archive is opened with the right password. If one part is broken, only that part is downloaded again.
- **Video:** YouTube and other sites at the quality you pick; audio and video are merged automatically. Whole playlists, and subtitles saved next to the video. The sinDL extension adds a download button over videos.
- **Torrents:** on libtorrent. Works without a VPN, stops uploading once a torrent finishes (or at the ratio you set), and RSS feeds add new episodes on their own.
- **Security:** finished files go to Windows antivirus, websites can not send download commands to the app behind your back, and files over a size you choose wait for your permission.
- **And more:** night queue that wakes the computer and shuts it down after, a speed limit only while you use the computer, the country of each server, disk space check, duplicate finder, resuming downloads after a power cut.

## Installing

The installer is not digitally signed, so Windows may show "Windows protected your PC". Click **More info**, then **Run anyway**.

To catch downloads from the browser, install the AB Download Manager extension ([Chrome and Edge](https://chromewebstore.google.com/detail/bbobopahenonfdgjgaleledndnnfhooj), [Firefox](https://addons.mozilla.org/firefox/addon/ab-download-manager/)). sinDL works with the same extension.

For the button over videos, download `sinDL-video-button-extension-….zip` from the release, unzip it, open `chrome://extensions`, turn on **Developer mode**, click **Load unpacked** and choose the unzipped folder.

## License

sinDL is built on [AB Download Manager](https://github.com/amir1376/ab-download-manager) by AmirHossein Abdolmotallebi and is distributed under the Apache License 2.0. See [NOTICE](NOTICE) for the third-party components it includes.
