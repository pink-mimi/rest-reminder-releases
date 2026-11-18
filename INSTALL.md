# Windows 安装与使用

当前版本：**v0.5.2 试用版**

适用设备：Windows x64，即使用 64 位 Intel / AMD 处理器的 Windows 电脑

## 安装

1. 从[版本页面](https://github.com/pink-mimi/rest-reminder-releases/releases/tag/v0.5.2)下载 `RestReminder-0.5.2-x64-Setup.exe`
2. 运行安装包。安装后的首次打开会等待安装器收尾，稍候即可
3. 在开始菜单搜索 **Rest Reminder**，打开「透口气」
4. 点击「开始提醒」，开始第一轮工作计时

GitHub 的 `Source code (zip)`、`Source code (tar.gz)` 是下载仓库的文件快照，不是软件安装包

当前试用包尚未正式签名，Windows 可能显示未知发布者或拦截。如果不确定来源，请停止安装，不建议关闭系统保护。下载页提供 SHA-256 校验值用于确认文件是否一致

## 调整提醒

打开「详细设置」后，可以调整工作间隔、休息时长和忙时处理

这三项修改后需要点击「保存休息规则」，再选择「立即生效」或「下一轮生效」。未保存内容会保留为草稿，不会影响正在运行的规则

主题、外观、减少动态效果和启动开关修改后自动保存

## 关闭窗口与退出

关闭设置窗口后，软件继续在托盘运行。Windows 托盘图标可能位于任务栏的隐藏图标区域

- 点击托盘图标：打开快捷面板
- 右键托盘图标：打开菜单
- 选择「退出透口气」：完全退出软件

## 休息与暂停

- 「开始休息」或「立即休息」：打开角落倒计时
- 「全屏休息」：主动进入全屏，按 Esc 返回角落，剩余时间继续
- 「提前结束」：结束本次休息并开始下一轮工作计时
- 「暂停提醒」：可选 30 分钟、1 小时或到当天 18:00；恢复后继续此前的剩余时间

锁屏或睡眠时不弹提醒。恢复后工作计时开始新一轮，未结束的休息按原截止时间继续

## 启动选项

「开机启动」默认关闭，开启后登录电脑时在托盘运行

「启动时自动开始」控制打开软件后是否自动开始倒计时，与开机启动分别设置

## 升级与卸载

升级前先从托盘退出旧版，再运行新版安装包。请保留现有配置，并在升级后检查设置；遇到异常可提交[问题反馈](https://github.com/pink-mimi/rest-reminder-releases/issues/new/choose)

当前没有应用内自动更新，可从[版本列表](https://github.com/pink-mimi/rest-reminder-releases/releases)查看新版

卸载时先退出软件，再在 Windows 设置的应用列表中卸载 **Rest Reminder**

## 校验文件

本版本的校验值位于 [SHA256SUMS.txt](SHA256SUMS.txt)，也会随 Release 附件提供

可在 PowerShell 中执行：

```powershell
Get-FileHash -LiteralPath '.\RestReminder-0.5.2-x64-Setup.exe' -Algorithm SHA256
```

将输出的 Hash 与校验文件比较。校验一致只说明文件内容相同，不代表安装包已经获得发布者签名
