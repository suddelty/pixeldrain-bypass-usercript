# Pixeldrain Download Limit Bypass

[![Install with Tampermonkey](https://img.shields.io/badge/Install%20with-Tampermonkey-00485B.svg)](https://github.com/suddelty/pixeldrain-bypass-usercript/raw/refs/heads/main/bypass_script.user.js)

A userscript that enhances Pixeldrain with bypass download functionality and additional features to improve your downloading experience.

## Features

- **Instant Downloads**: Bypass Pixeldrain's download limits with direct download links
- **Gallery Support**: Full support for both single files and gallery downloads
- **Link Management**: View and copy bypass URLs for single files or entire galleries
- **Smart Navigation**: Automatic button updates when navigating through galleries
- **Filename Display**: Shows actual file names next to bypass URLs
- **Link Caching**: Stores bypass links on page load for faster access
- **Multiple Copy Options**: Copy URLs with or without filenames

## Installation

1. Install a userscript manager (like Tampermonkey) for your browser
2. Click [here](https://github.com/suddelty/pixeldrain-bypass-usercript/raw/refs/heads/main/bypass_script.user.js) to install the script

## Usage

After installation, you'll see two new buttons in the left sidebar on Pixeldrain pages:

- **"Download Bypass"** - Direct download using bypass links
- **"Show Bypass Links"** - View bypass URLs in a popup

## Important Notes

- Some file types (videos, images, PDFs) may open in your browser instead of downloading
  - Right-click the bypass link and select "Save link as..."
- The "Show Bypass Links" popup works great with external download managers (IDM, JDownloader, etc.)
- If using a VPN and the script doesn't work, try temporarily disabling it or switching servers

## Changelog

### v1.7.0
- Implemented link caching system
- Added smart gallery navigation
- Enhanced file name extraction
- Added support for gallery URLs with hash fragments
- Improved popup display with file names
- Added "Copy with Names" functionality
- Implemented robust button insertion
- Added comprehensive error handling
- Enhanced dynamic content detection
- Added click-outside-to-close for popup

## Todo List

- [x] Fix show bypass links on single files
- [x] Store all the links on page load
- [x] Add event listeners to gallery files
- [x] Show file names next to URLs in popup box
- [x] Update the main page for the userscript

## Credits

- Written by [MegaLime0](https://github.com/MegaLime0), [honey](https://github.com/hhoneeyy), and [Nurarihyon](https://greasyfork.org/en/users/723993-nurarihyonmaou)
- [Pixeldrain Bypass](https://pixeldrain-bypass.cybar.xyz/) provided by GameDrive