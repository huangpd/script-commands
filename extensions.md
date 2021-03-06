# Raycast Script Commands

[Raycast](https://raycast.com) lets you control your tools with a few keystrokes
and Script Commands makes it possible to execute scripts from anywhere on your desktop.
They are a great way to speed up every-day tasks such as converting data, opening bookmarks
or triggering dev workflows.

This repository contains sample commands and documentation to write your own ones.

### Content

- [Bookmarks](#bookmarks)
- [Browsing](#browsing)
- [Communication](#communication)
- [Conversions](#conversions)
- [Dashboard](#dashboard)
- [Developer Utils](#developer-utils)
- [Media](#media)
- [Navigation](#navigation)
- [System](#system)

## Bookmarks

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| 📜 | [Open Script Commands Repository](bookmarks/open-scriptCommandsRepository.sh) | N/A | Raycast |

## Browsing

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| 🧭 | [Copy current page URL](browsing/safari_current_page_url.sh) | This script copies URL of currently opened page in Safari into clipboard. | [Kirill Gorbachyonok](https://github.com/japanese-goblinn) |
| 🧭 | [Copy current window URLs](browsing/safari_current_window_urls.applescript) | This script copies to clipboard all URLs from frontmost Safari window. | [Kirill Gorbachyonok](https://github.com/japanese-goblinn) |
| 🔗 | [Shorten URL From Clipboard](browsing/shorten-url.sh) | Shorten the URL in your Clipboard with Tiny URL. | [Thomas Paul Mann](https://github.com/thomaspaulmann) |

## Communication

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| 🔐 | [2FA from iMessages](communication/imessage-2fa.sh) | Get most recent two-factor authentication code from iMessages. | Caleb Stauffer and Thiago Holanda |

#### Cloudup

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/communication/images/cloudup-logo.png?raw=true" width="20" height="20"> | [Paste](communication/cloudup-paste.sh) | Upload clipboard contents to Cloudup | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/communication/images/cloudup-logo.png?raw=true" width="20" height="20"> | [Pick](communication/cloudup-pick.sh) | Open file dialog and upload to Cloudup | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/communication/images/cloudup-logo.png?raw=true" width="20" height="20"> | [Show](communication/cloudup-show.sh) | Show Cloudup popup | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/communication/images/cloudup-logo.png?raw=true" width="20" height="20"> | [Upload](communication/cloudup-upload.sh) | Upload path or URL in clipboard to Cloudup | [Caleb Stauffer](https://github.com/crstauf) |

## Conversions

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
|  | [Column to Comma](conversions/column-to-comma.sh) | N/A | Raycast |
| 🎨 | [Hex to RGB](conversions/hex-to-rgb.sh) | Convert HEX color values in your Clipboard to RGB values. | [Caleb Stauffer](https://github.com/crstauf) |
| 🎨 | [Hex to RGBA](conversions/hex-to-rgba.sh) | Convert HEX color values in your Clipboard to RGBA values. | [Caleb Stauffer](https://github.com/crstauf) |

## Dashboard

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| 🌦️ | [Current Weather](dashboard/current-weather.sh) | Get current weather report from wttr.in. | [Caleb Stauffer](https://github.com/crstauf) |
| 📈 | [System Activity](dashboard/system-activity.sh) | N/A | Raycast |

#### Internet

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/dashboard/images/speedtest-logo.png?raw=true" width="20" height="20"> | [Speedtest](dashboard/speedtest.sh) | Test download and upload connection speed | [Caleb Stauffer](https://github.com/crstauf) |

## Developer Utils

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| 📝 | [Copy Lorem Ipsum](developer-utils/lorem-ipsum.sh) | N/A | Raycast |
| 💻 | [Decode Base64](developer-utils/decode-base64.sh) | N/A | Raycast |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/developer-utils/images/jwt-logo.png?raw=true" width="20" height="20"> | [Decode JWT](developer-utils/decode-jwt.sh) | N/A | Raycast |
| 💻 | [Encode Base64](developer-utils/encode-base64.sh) | N/A | Raycast |
| 💻 | [Generate UUID](developer-utils/generate-uuid.sh) | N/A | Raycast |
| 💻 | [Prettify JSON](developer-utils/prettify-json.sh) | N/A | Raycast |
| 📱 | [Record Simulator](developer-utils/record-simulator.sh) | Records simulator to Downloads folder with a filename from the clipboard | [Maxim Krouk](https://github.com/maximkrouk) |

#### GitHub

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/developer-utils/images/github-logo.png?raw=true" width="20" height="20"> | [Create GitHub Gist from clipboard](developer-utils/create-github-gist.sh) | Create a GitHub Gist from clipboard contents and copy Gist URL. | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/developer-utils/images/github-logo.png?raw=true" width="20" height="20"> | [Unread Notifications](developer-utils/github-unread-notifications.sh) | Number of unread GitHub notifications. | [Caleb Stauffer](https://github.com/crstauf) |

#### Internet

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| 🌐 | [External IPv4](developer-utils/get-external-ip-v4.sh) | N/A | Raycast |
| 🌐 | [External IPv6](developer-utils/get-external-ip-v6.sh) | N/A | Raycast |
| 🌐 | [Local IPv4](developer-utils/get-local-ip-v4.sh) | N/A | Raycast |
| 🌐 | [Local IPv6](developer-utils/get-local-ip-v6.sh) | N/A | Raycast |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/developer-utils/images/ia-logo.jpg?raw=true" width="20" height="20"> | [Save clipboard URL to Wayback Machine](developer-utils/wayback-machine-save.sh) | Save clipboard URL to Wayback Machine | [Caleb Stauffer](https://github.com/crstauf) |
| 🌐 | [URL IPv4](developer-utils/get-url-ip-v4.sh) | Get IPv4 address of URL | [Caleb Stauffer](https://github.com/crstauf) |
| 🌐 | [URL IPv6](developer-utils/get-url-ip-v6.sh) | Get IPv6 address of URL | [Caleb Stauffer](https://github.com/crstauf) |
| 🌐 | [Whois of clipboard URL](developer-utils/whois.sh) | Whois of clipboard URL. | [Caleb Stauffer](https://github.com/crstauf) |

#### Xcode

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| 🧹 | [Clear Derived Data](developer-utils/clear-derived-data.sh) | N/A | Raycast |

## Media

#### Music

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/media/images/music-logo.png?raw=true" width="20" height="20"> | [Next](media/music-next.applescript) | Next track in Music | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/media/images/music-logo.png?raw=true" width="20" height="20"> | [Pause](media/music-pause.applescript) | Pause Music | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/media/images/music-logo.png?raw=true" width="20" height="20"> | [Play](media/music-play.applescript) | Play Music | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/media/images/music-logo.png?raw=true" width="20" height="20"> | [Previous](media/music-previous.applescript) | Previous track in Music | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/media/images/music-logo.png?raw=true" width="20" height="20"> | [Stop](media/music-stop.applescript) | Stop Music | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/media/images/music-logo.png?raw=true" width="20" height="20"> | [Toggle repeat](media/music-repeat.applescript) | Toggle repeat settling in Music | [Caleb Stauffer](https://github.com/crstauf) |
| <img src="https://raw.githubusercontent.com/raycast/script-commands/master/media/images/music-logo.png?raw=true" width="20" height="20"> | [Toggle shuffle](media/music-shuffle.applescript) | Toggle shuffle setting in Music | [Caleb Stauffer](https://github.com/crstauf) |

#### Spotify

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| ⏭ | [Next Track](media/spotify-next-track.applescript) | N/A | Raycast |
| ⏸ | [Pause](media/spotify-pause.applescript) | N/A | Raycast |
| ▶️ | [Play](media/spotify-play.applescript) | N/A | Raycast |
| ⏯️ | [Toggle Play/Pause](media/spotify-play-pause.applescript) | N/A | Raycast |

## Navigation

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| 📂 | [Open Applications](navigation/open-applications.sh) | N/A | Raycast |
| 🖥 | [Open Clipboard URL on Desktop](navigation/open-desktop-url-from-clipboard.swift) | N/A | Raycast |
| 📂 | [Open Desktop](navigation/open-desktop.sh) | N/A | Raycast |
| 📂 | [Open Documents](navigation/open-documents.sh) | N/A | Raycast |
| 📂 | [Open Downloads](navigation/open-downloads.sh) | N/A | Raycast |
| 📂 | [Open Home](navigation/open-home.sh) | N/A | Raycast |
| 📂 | [Open Library](navigation/open-library.sh) | N/A | Raycast |
| 🌐 | [Open URL From Clipboard](navigation/open-url-from-clipboard.sh) | N/A | Raycast |
| 📂 | [Open Utilities](navigation/open-utilities.sh) | N/A | Raycast |
| 📟 | [Open current Finder directory in Terminal](navigation/open-terminal-from-finder.applescript) | Open curren Finder directory in terminal | [Kirill Gorbachyonok](https://github.com/japanese-goblinn) |
| 📟 | [Open current Terminal directory in Finder](navigation/open-finder-from-terminal.applescript) | Open curren terminal directory in Finder | [Kirill Gorbachyonok](https://github.com/japanese-goblinn) |

## System

| Icon | Title | Description | Author |
| ---- | ----- | ----------- | ------ |
| 📅 | [Copy Availability](system/copy-availability.swift) | N/A | Raycast |
| 💁 | [Copy Last Download](system/copy-last-download.swift) | N/A | Raycast |
| 📸 | [Copy Last Screenshot](system/copy-last-screenshot.swift) | N/A | Raycast |
| 📀 | [Eject All Disks](system/eject-all-disks.applescript) | N/A | Raycast |
| 🗑 | [Empty Trash](system/empty-trash.applescript) | N/A | Raycast |
| 💁‍♂️ | [Open Last Download](system/open-last-download.swift) | N/A | Raycast |
| 💥 | [Quit All Applications](system/quit-all-apps.swift) | N/A | Raycast |
| 🖼️ | [Refresh Wallpaper](system/wallpaper-refresh.applescript) | Refresh the current display's wallpaper | [Caleb Stauffer](https://github.com/crstauf) |
| ♻️ | [Restart](system/restart.applescript) | N/A | Raycast |
| 🌀 | [Screen Saver](system/screensaver.applescript) | A script command to start your current screen saver. | [Valentin Chrétien](https://twitter.com/valentinchrt) |
| 🛌 | [Shut Down](system/shutdown.applescript) | N/A | Raycast |
| 😴 | [Sleep](system/sleep.applescript) | N/A | Raycast |
| 🖥 | [Toggle Desktop Icons](system/toggle-desktop-icons.applescript) | A script command to show and hide icons of Desktop folder | [Raycast](https://raycast.com) |
| 👓 | [Toggle Hidden Files](system/toggle-hidden-files.applescript) | Show and hide hidden files/folders which starts with "." (dot), i.e: .bash_rc, .ssh | [Thiago Holanda](https://twitter.com/tholanda) |
| 🌗 | [Toggle System Appearance](system/toggle-system-appearance.applescript) | Script Command to switch between the system appearance, light and dark mode. | [Thiago Holanda](https://twitter.com/tholanda) |

## Community

This is a shared place and we're always looking for new Script Commands or other ways to improve Raycast.
If you have anything cool to show, please send us a pull request. If we screwed something up,
please report a bug. Join our
[Slack community](https://join.slack.com/t/raycastcommunity/shared_invite/zt-hhzj9i4m-D5~HwnTRsJKrcZmVDJ4mkg)
to brainstorm ideas with like-minded folks.