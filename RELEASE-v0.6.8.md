## 透口气 v0.6.8

- 改善后台计时调度，关窗后仍会提醒并保存工作记录。
- 减少近七天汇总的重复读取和计算，切换日期时按需读取明细。
- 读取旧记录时跳过损坏条目，保留有效记录并显示提示。
- 改善 Windows 系统助手的返回值校验和主题卡片的鼠标跟随更新。

## 选择下载

| 文件 | 适用设备 |
| --- | --- |
| `RestReminder-0.6.8-Windows-x64.zip` | 64 位 Intel / AMD Windows 电脑。完整解压后启动 `透口气.exe`。 |
| `RestReminder-0.6.8-macOS-arm64.zip` | Apple 芯片 Mac 预览版。在 Mac 上解压后打开 `透口气.app`。 |

Windows 试用包尚未正式签名。Mac 预览包通过了 AppKit 设置、计时测试和临时签名校验，尚未经过 Apple 公证，macOS 可能拦截首次打开。锁屏唤醒、登录时打开和多屏提醒仍需实际使用验证。

请保留完整的解压目录。附件 `SHA256SUMS.txt` 可用来校验两个 ZIP 的文件内容。

[使用说明](https://github.com/pink-mimi/rest-reminder-releases/blob/main/INSTALL.md) · [问题反馈](https://github.com/pink-mimi/rest-reminder-releases/issues/new/choose)
