# 余火 · AI Roaster

**让每份额度都有数。**

个人 AI 订阅额度看板：集中查看 Codex、Claude 桌面 App 与 Claude Code 的账号、剩余额度和使用历史，在本机管理账号切换。

[下载安装包与更新日志](https://github.com/winrey/ai-roaster-releases/releases) · [macOS 安装说明](INSTALL.md) · [反馈问题](https://github.com/winrey/ai-roaster-releases/issues)

## 下载与更新

在 Releases 中选择版本，下载 `YuHuo-AI-Roaster_<版本>_macOS_universal.dmg`。通用安装包同时包含 Apple 芯片和 Intel 架构；每个版本附带安装说明、构建信息和 SHA-256 校验文件。

当前提供预览版。请查看对应 Release 的签名与公证状态；已签名、未公证的预览包首次打开可能被 macOS 阻止，处理步骤见安装说明。Intel Mac 尚未实机验收。

从 0.2.1 起，应用右上角菜单提供“检查软件更新”，通过本仓库公开的 GitHub Releases 检测新版。默认仅检查正式版本；试用预览版需勾选“包含预发布版本”。更新检测只提供下载入口，安装由用户操作。

## 功能

- Codex、Claude 桌面 App 与 Claude Code 的本地登录识别、额度读取和账号切换。
- 多账号、多个额度周期、手动校正与历史图表。
- 日间、夜间与跟随系统主题，可调节毛玻璃透明度。
- macOS 菜单栏、开机启动、本地 JSON 导入和导出。

切换桌面客户端账号会关闭并重新打开对应客户端，运行中的任务会中断。Claude 的完整登录、真实额度及双向切换仍需更多实机验证。

## 数据与反馈

账号、额度历史和授权保存在使用者本机。安装包不包含开发者的账号数据。更新检查无需 GitHub Token，不上传邮箱、授权或额度记录。

反馈时请注明系统、芯片类型、应用版本和复现步骤；截图请遮盖私人信息，不要上传授权文件或完整数据目录。

本仓库用于公开安装包、更新日志和问题反馈，应用源码仓库保持私有。暂未指定项目开源许可证。
