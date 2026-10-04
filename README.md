# NeoShell 下载与更新

<img src="./branding/neoshell-icon.png" width="72" height="72" alt="NeoShell Shell/SFTP 标识" />

NeoShell 是跨平台 SSH 终端和 SFTP 文件管理工具。本仓库只存放公开安装包、校验值和版本说明。

**[获取最新版本](https://github.com/niujt/NeoSHELL-Releases/releases/latest)**

v0.3.1 更新为更简洁的黑白界面，采用全新 Shell/SFTP 标识。左下角可切换浅色与深色主题，应用会记住选择。

- Windows：下载 x64 NSIS 安装版 `.exe`。
- macOS Apple Silicon（M 系列）：下载 arm64 DMG，将 NeoShell 拖入 Applications。
- 退出旧版再覆盖安装，原有连接、凭据和工作区保留。无需删除应用数据。

v0.3.0 起，可通过 **设置 → 应用更新** 或 **帮助 → 检查更新** 获取对应系统的下载链接。默认启动时检查一次，也可在设置中关闭。检查更新无需 GitHub 账号，不上传服务器连接信息。

当前安装包未作 Windows 代码签名；macOS 使用临时签名，未经 Apple 公证。Intel Mac 暂无安装包。

版本说明包含改动范围和验证边界。SHA256SUMS.txt 可用于核对下载文件是否完整。

## 深浅色界面

以下截图来自 v0.3.1 的真实 Electron 窗口，使用独立测试数据。

### 浅色

![NeoShell 浅色界面](./screenshots/v0.3.1/home-light.png)

### 深色

![NeoShell 深色界面](./screenshots/v0.3.1/home-dark.png)

终端分屏、批量执行、命令片段、会话日志、文件同步预览、过滤、搜索和图形化权限修改继续提供。终端 ANSI 彩色输出保留。
