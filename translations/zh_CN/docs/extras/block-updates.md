# 阻止更新
---
目前所有已知的 Wii U 漏洞（例如 Nintendo Switch RCM 漏洞）都可以被通过更新系统失效。 虽然 Wii U 不再会得到任天堂官方的技术支持，但任天堂仍然可以为其发布新的系统更新。 Namely, the updates 5.5.3 up to 5.5.6 were all released after the Wii U was discontinued, so blocking updates is still a recommended action.

While Tiramisu's PayloadLoader already has built-in update blocking functionality, it is recommended to delete the update folder to effectively block system updates. If you get a red warning screen while booting into Tiramisu, the update folder still exists and it is recommended to delete it using the guide below.

### 简介 {docsify-ignore}

Currently, one way exists to effectively block updates on the Wii U system:

1. 将 SD 卡插入电脑。
1. Download and extract the contents of [UFDiine](https://github.com/GaryOderNichts/UFDiine/releases/tag/v1.1) to the root of your SD Card.
1. Plug the SD Card into your Wii U console and boot Tiramisu.
1. 启动 Homebrew Launcher。
1. 移动 Homebrew Launcher 并启动 UFDiine app。
1. 按下 A 键删除更新文件夹。
1. Confirm that it says `Update folder is deleted`.
1. Power off the console. You are now blocking updates.
