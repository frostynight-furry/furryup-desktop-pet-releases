# FurryUP 桌宠

**没有自己的模型，也能拥有喜欢的主播桌宠。**

粉丝通过主播分享的官方连接，确认后即可使用主播已发布并授权的角色模型。主播可以把陪伴延伸到非开播时间，并在粉丝授权后触发表情、发送文字和开播提醒。

[官方网站](https://frostynight.top/furryup/desktop-pet) · [版本与下载](https://github.com/frostynight-furry/furryup-desktop-pet-releases/releases/tag/v0.3.0-beta.8)

## 下载客户端

当前版本：**0.3.0-beta.8**。本仓库镜像官网已公开发布的原始安装包。

| 系统 | 安装包 | 文件大小 | 更新方式 |
| --- | --- | --- | --- |
| Windows 10 / Windows 11，64 位（x64） | [下载 Windows 安装包（EXE）](https://github.com/frostynight-furry/furryup-desktop-pet-releases/releases/download/v0.3.0-beta.8/FurryUP-Desktop-Pet-Setup-0.3.0-beta.8-x64.exe) | 105.5 MiB | 应用内更新或手动安装 |
| Windows 7 SP1，32 位（x86）兼容版 | [下载 Win7 安装包（MSI）](https://github.com/frostynight-furry/furryup-desktop-pet-releases/releases/download/v0.3.0-beta.8/FurryUP-Desktop-Pet-Legacy-Win7-Installer-0.3.0-beta.8-ia32.msi) | 77.1 MiB | 手动更新 |

[下载 SHA-256 校验文件](https://github.com/frostynight-furry/furryup-desktop-pet-releases/releases/download/v0.3.0-beta.8/SHA256SUMS-0.3.0-beta.8.txt)

- 两个安装包均为未签名 Beta，Windows 可能显示未知发布者提示。安装前请核对官网来源与校验值。
- Win7 兼容版使用 Electron 22.3.27，独立安装，不连接 Win10/11 x64 自动更新源；已完成包体检查与隔离运行验证，尚未完成真实 Win7 安装验收。
- 首次启动不内置主播模型，确认主播连接后才下载已授权的模型内容。

## 校验下载文件

可在 PowerShell 中运行 `Get-FileHash -Algorithm SHA256 <安装包路径>`，并与校验文件中的对应记录比较。

## 版本说明

- 修复主播撤下模型后，粉丝刷新列表仍显示旧款的问题。
- 已下载模型继续保留；正在显示的模型被撤下时提示状态，不强制切换。
- 网络或校验失败时保留原列表。
- 保留屏幕边缘拖动与缩放修复。

## 关于本仓库

本仓库仅用于公开分发客户端和面向用户的发行说明，应用源码保持私有。GitHub 自动生成的 **Source code** 压缩包只包含本仓库的说明文件；安装客户端请使用上面的 EXE 或 MSI。

应用更新继续使用官网更新服务，GitHub 下载不会更改现有客户端的更新源。

发行主体：苏州工业园区夜霜文化创意工作室（个体工商户）  
客服邮箱：yeshuang@frostynight.cn
