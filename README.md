# NeoShell 下载与更新

NeoShell 是跨平台 SSH 终端和 SFTP 文件管理工具。本仓库只存放公开安装包、校验值和版本说明。

**[获取最新版本](https://github.com/niujt/NeoSHELL-Releases/releases/latest)**

- Windows：下载 x64 NSIS 安装版 `.exe`。
- macOS Apple Silicon（M 系列）：下载 arm64 DMG，将 NeoShell 拖入 Applications。
- 退出旧版再覆盖安装，原有连接、凭据和工作区保留。无需删除应用数据。

v0.3.0 起，可通过 **设置 → 应用更新** 或 **帮助 → 检查更新** 获取对应系统的下载链接。默认启动时检查一次，也可在设置中关闭。检查更新无需 GitHub 账号，不上传服务器连接信息。

当前安装包未作 Windows 代码签名；macOS 使用临时签名，未经 Apple 公证。Intel Mac 暂无安装包。

版本说明包含改动范围和验证边界。SHA256SUMS.txt 可用于核对下载文件是否完整。
