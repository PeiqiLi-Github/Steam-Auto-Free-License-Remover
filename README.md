# Steam Free License Auto Remover  
（Steam One-Click Licence Cleaner）

_This version is an implementation to add checkboxes to each title so you can check which ones you want to remove_

---

## Description

This script helps you clean up your Steam inventory by removing all free licenses with one click. It will not affect games you have purchased.  
To avoid triggering Steam rate limits, the deletion interval defaults to 5 minutes and is not recommended to shorten.  
Deleted licenses can usually be re-added through the store page, but some removed games may no longer be available in store.  
Please confirm before deleting. Use at your own risk; the author is not responsible for any loss caused by this script.

---

## Features

- Automatically scans and lists all removable free licenses  
- One-click automatic removal with interval to prevent rate limiting
- Check to remove either all free titles or demo/prologue titles only
- Displays current progress and estimated remaining time  
- Easy to use, runs directly on Steam license inventory page

---

## Usage

1. Install this script using a userscript manager like Tampermonkey or Violentmonkey.  
2. Navigate to: https://store.steampowered.com/account/licenses/  
3. After the page loads, check the box for all free titles or demo titles only, click the "🧹Start cleaning" button to start automatic removal.  
4. Keep the page open and wait until the script finishes all operations.

---

## FAQ

**Q1: Why is the deletion slow?**  
A1: Steam rate limits removal operations. The default 3-minute interval prevents request rejections.

**Q2: Can I restore deleted games?**  
A2: Most free licenses can be re-added via the store. Some removed or delisted games may be unrecoverable.

**Q3: What if I get error code 84?**  
A3: It usually means you're acting too fast and triggered rate limiting. Wait and try again later.

**Q4: Script does nothing or cannot find buttons?**  
A4: Make sure you are on the correct page and it has fully loaded. Steam layout changes might break the script temporarily.

**Q5: Will purchased games be deleted?**  
A5: No, only free licenses are removed, purchased games remain unaffected.

---

## Disclaimer

This script is developed by [PeiqiLi](https://github.com/PeiqiLi-Github) for personal use only. Use at your own risk. PeiqiLi is not responsible for any damage or loss caused. Please operate carefully.

---

## Feedback

You are welcome to submit issues or suggestions on GitHub:
- [PeiqiLi's Github](https://github.com/PeiqiLi-Github/Steam-Auto-Free-License-Remover/issues)
- [JoeX92's Github](https://github.com/joex92/Steam-Auto-Demo-License-Remover/issues)
