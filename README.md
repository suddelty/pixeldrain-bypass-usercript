# Pixeldrain Download Limit Bypass

### Install
You can install the extension using this [link](https://github.com/suddelty/pixeldrain-bypass-usercript/raw/refs/heads/main/bypass_script.user.js)

### Usage
Once the script is installed, you'll see two additional buttons in the left sidebar on Pixeldrain pages:

- **"Download Bypass"** - Instantly downloads files using bypass links, circumventing Pixeldrain's download limits
- **"Show Bypass Links"** - Opens a popup displaying bypass URLs for the current file or all files in a gallery

**For single files:** Both buttons work with the currently viewed file.
**For galleries:** The download button only appears when viewing a specific file. Use "Show Bypass Links" to see all files in the gallery.

### Important Notes
- **File Downloads:** Some file types (videos, images, PDFs) may open in your browser instead of downloading. If this happens, right-click the bypass link and select "Save link as..." or "Save target as..." to download the file.
- **External Download Managers:** The "Show Bypass Links" popup is particularly useful if you prefer using external download managers like IDM, JDownloader, or similar tools.
- **VPN Compatibility:** Some VPN providers may block access to the bypass website. If the script doesn't work, try temporarily disabling your VPN or switching servers.

### Features (v1.7.0)
- **Dynamic Button Insertion**: Automatically detects when you navigate between gallery files and updates bypass buttons accordingly
- **Enhanced File Detection**: Works with gallery URLs containing hash fragments (e.g., `#item=0`)
- **Link Caching**: Stores bypass links on page load for faster access and better performance
- **Improved File Names**: Shows actual file names next to bypass URLs in the popup
- **Multiple Copy Options**: Copy URLs only or copy with filenames included for easier sharing
- **Robust Button Placement**: Multiple fallback strategies ensure buttons appear regardless of page structure changes
- **Real-time Updates**: Automatically adapts to dynamic page content changes
- **Intuitive Popup**: Click outside the popup to close it for better user experience

### Gallery Navigation
The script seamlessly handles Pixeldrain's gallery system. When you click on gallery files or navigate between items, the bypass buttons automatically update to work with the currently viewed file. The popup will always show the specific file you're viewing with its actual filename, making it easy to identify and download the content you want.

### TODO
- [x] Fix show bypass links on single files
- [x] Store all the links on page load
- [x] Add event listeners to gallery files so that when clicked they add the bypass buttons to the changed website structure. same needs to be done when the gallery button (top left) is clicked
- [x] Show file names next to url's in popup box
- [x] Update the main page for the userscript

### Changelog

#### v1.7.0
- ✅ Implemented link caching system for improved performance
- ✅ Added smart gallery navigation with automatic button updates
- ✅ Enhanced file name extraction from multiple page sources
- ✅ Added support for gallery URLs with hash fragments (#item=)
- ✅ Improved popup display with file names next to URLs
- ✅ Added "Copy with Names" functionality
- ✅ Implemented robust button insertion with multiple fallback strategies
- ✅ Added comprehensive error handling and debugging
- ✅ Enhanced MutationObserver for dynamic content detection
- ✅ Added click-outside-to-close functionality for popup

### Credits
Written by [MegaLime0](https://github.com/MegaLime0), [honey](https://github.com/hhoneeyy) and [Nurarihyon](https://greasyfork.org/en/users/723993-nurarihyonmaou)

Thanks to [Bypass site](https://pixeldrain-bypass.cybar.xyz/) by GameDrive