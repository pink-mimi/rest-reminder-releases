## 透口气 v0.6.7 · Windows x64 原生试用版

- **托盘快捷面板**失焦后会收起，暂停状态的「现在恢复」按钮完整显示。
- **自定义暂停**可以从主窗口、托盘菜单和快捷面板打开。
- **主窗口位置**首次打开居中，之后恢复上次关闭的位置。角落休息卡片出现时，主窗口的设置和记录继续按自身宽度排版。
- **输入和设置**暂停时长数字聚焦前后保持居中，设置开关的操作范围限于右侧按钮本体。

## 下载和使用

下载附件 **RestReminder-0.6.7-Native-x64.zip**，约 **27.6 MB**，适用于 64 位 Intel / AMD Windows 电脑。先从托盘退出旧版，完整解压后打开 `RestReminderNativeLauncher.exe`，点击「开始提醒」。

原生版使用独立的本机设置和记录。附件 `SHA256SUMS.txt` 可用于校验 ZIP。

技术栈采用 NSH 0.7.1、TypeScript / TSX 和 QuickJS。Windows 后端通过 Win32 绘制，C# / .NET Framework 助手处理开机启动与系统事件。

[使用说明](https://github.com/pink-mimi/rest-reminder-releases/blob/v0.6.7/INSTALL.md) · [问题反馈](https://github.com/pink-mimi/rest-reminder-releases/issues/new/choose)
