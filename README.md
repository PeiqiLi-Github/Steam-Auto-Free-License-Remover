# Steam Free License Auto Remover  
（Steam One-Click Licence Cleaner）    
[English](#steam-free-license-auto-remover) | [中文](#中文说明)       

_This version is an implementation to add checkboxes to each title so you can check which ones you want to remove_     
Thanks [joex92](https://github.com/joex92) 

若账号有数千款以上游戏，推荐下载运行更快的旧版本脚本：OLDSteam Free License Auto Remover.js
> **文件名称**：OLDSteam Free License Auto Remover.js 
> **链接**：[OLDSteam Free License Auto Remover.js](https://github.com/PeiqiLi-Github/Steam-Auto-Free-License-Remover/blob/b358c1b98e4700830f1285187973b317218b5fcc/OLDSteam%20Free%20License%20Auto%20Remover.js)   

If your account has thousands of games or more, download the older version script OLDSteam Free License Auto Remover.js for faster operation.
> **File Name**: OLDSteam Free License Auto Remover.js
> **Link**: [OLDSteam Free License Auto Remover.js](https://github.com/PeiqiLi-Github/Steam-Auto-Free-License-Remover/blob/b358c1b98e4700830f1285187973b317218b5fcc/OLDSteam%20Free%20License%20Auto%20Remover.js)


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

---

# 中文说明

## 简介

此脚本可以帮助你一键清理 Steam 账户中的免费许可证，不会影响你购买的游戏。  
为了避免触发 Steam 的请求限制，删除间隔默认设置为 5 分钟，不建议缩短。  

被删除的许可证通常可以在商店页面重新添加，但某些已下架的游戏可能无法恢复。  
删除前请确认，使用风险自负。

---

## 功能

- 自动扫描并列出所有可移除的免费许可证  
- 一键自动删除，并带有间隔防止触发限制  
- 可以选择删除所有免费游戏或仅删除 Demo / Prologue  
- 显示当前进度和预计剩余时间  
- 直接在 Steam 许可证页面运行，操作简单

---

## 使用方法

1. 使用 Tampermonkey 或 Violentmonkey 安装此脚本。  
2. 打开页面：  
   https://store.steampowered.com/account/licenses/  
3. 页面加载完成后，选择 **删除所有免费游戏** 或 **仅删除 Demo**，然后点击 **🧹Start cleaning**。  
4. 保持页面打开，等待脚本完成所有操作。

---

## 常见问题

**Q1：为什么删除速度很慢？**  
A1：Steam 对删除操作有限速。默认 3 分钟间隔可以避免请求被拒绝。

**Q2：删除的游戏可以恢复吗？**  
A2：大多数免费许可证可以在商店页面重新添加，但某些已下架的游戏可能无法恢复。

**Q3：出现错误代码 84 怎么办？**  
A3：通常是操作过快触发了限制，等待一段时间再尝试即可。

**Q4：脚本没有反应或找不到按钮？**  
A4：请确认在正确页面，并且页面已经完全加载。Steam 页面结构变化可能导致脚本暂时失效。

**Q5：会删除我购买的游戏吗？**  
A5：不会，脚本只会删除免费许可证。

---

## 免责声明

此脚本由 [PeiqiLi](https://github.com/PeiqiLi-Github) 开发，仅供个人使用。  
使用风险自负，作者不对任何损失负责，请谨慎操作。

---

## 反馈

欢迎在 GitHub 提交问题或建议：

- https://github.com/PeiqiLi-Github/Steam-Auto-Free-License-Remover/issues  
- https://github.com/joex92/Steam-Auto-Demo-License-Remover/issues     

## Acknowledgements / 致谢

Thanks to the following people and projects for their ideas and improvements:

* [joex92](https://github.com/joex92) – inspiration and related project
* Community users who reported bugs and suggested improvements

感谢以下人员和项目提供的灵感与改进建议：

* [joex92](https://github.com/joex92) – 提供相关项目与思路
* 提交问题和建议的社区用户
