## 透口气 v0.6.8

### Windows 和 Mac 修订版

- 主窗口关闭后重新打开时恢复默认大小并居中，小屏幕按可用空间适配。
- 主窗口和当天记录的滚动条随明亮、暗黑主题切换，内容超出可见区域时显示。

### v0.6.8 的其他改进

- 改善后台计时调度，关窗后仍会提醒并保存工作记录。
- 减少近七天汇总的重复读取和计算，切换日期时按需读取明细。
- 读取旧记录时跳过损坏条目，保留有效记录并显示提示。
- 改善 Windows 系统助手的返回值校验和主题卡片的鼠标跟随更新。

## 选择下载

| 文件 | 适用设备 |
| --- | --- |
| [`RestReminder-0.6.8-Windows-x64-Rev2.zip`](https://github.com/pink-mimi/rest-reminder-releases/releases/download/v0.6.8/RestReminder-0.6.8-Windows-x64-Rev2.zip) | 64 位 Intel / AMD Windows 电脑。完整解压后启动 `透口气.exe`。 |
| [`RestReminder-0.6.8-macOS-arm64-Rev2.zip`](https://github.com/pink-mimi/rest-reminder-releases/releases/download/v0.6.8/RestReminder-0.6.8-macOS-arm64-Rev2.zip) | Apple 芯片 Mac 修订预览包。在 Mac 上解压后打开 `透口气.app`。 |

Windows 试用包尚未正式签名。Mac 预览包通过了 AppKit 设置、计时测试和临时签名校验，尚未经过 Apple 公证，macOS 可能拦截首次打开。锁屏唤醒、登录时打开和多屏提醒仍需实际使用验证。

升级前请从 Windows 托盘或 Mac 菜单栏退出正在运行的旧版，再解压修订包。请保留完整的解压目录。

附件 `SHA256SUMS-Windows-Rev2.txt` 和 `SHA256SUMS-macOS-Rev2.txt` 用于校验两端修订包。所有包的校验值见[校验文件](https://github.com/pink-mimi/rest-reminder-releases/blob/main/SHA256SUMS.txt)。

[使用说明](https://github.com/pink-mimi/rest-reminder-releases/blob/main/INSTALL.md) · [问题反馈](https://github.com/pink-mimi/rest-reminder-releases/issues/new/choose)
