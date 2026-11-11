# XueMianTong (学面通) — Desktop downloads

[Official website](https://xuexi.inono.xyz/www/?lang=en) · [Release notes and checksums](https://github.com/bubu-nono/xuemian-client-downloads/releases/latest)

This repository contains the official desktop installers and installation instructions. GitHub downloads do not require a GitHub account.

| Platform | Download |
| --- | --- |
| Windows (x64) | [Windows installer (.exe)](https://github.com/bubu-nono/xuemian-client-downloads/releases/latest/download/XueMianTong-Setup-x64.exe) |
| Mac with an Apple chip, macOS 13 or later | [Apple chip installer (.dmg)](https://github.com/bubu-nono/xuemian-client-downloads/releases/latest/download/XueMianTong-Mac-arm64.dmg) |

Intel Macs are no longer supported by new releases. To check your Mac, choose Apple menu → About This Mac and look for “Chip.” On the Releases page, use the installer under **Assets**; the automatic source archives only contain this README.

## Install and get started

1. **Windows:** Open the EXE and follow the installer. **Mac:** Open the DMG and drag 学面通 into Applications. The current Mac installer is not signed with an Apple Developer ID. If macOS blocks it, do not disable system protections; use the official website for help.
2. Launch the app and sign in with Google or WeChat, then choose your default language. The app supports Simplified Chinese, English, Japanese and Korean.
3. In the preparation screen, choose the job you want to practice for and check system audio. On Mac, follow the system prompt to allow system audio recording and reopen the app if asked. No virtual audio driver is required on Mac.
4. Play a sample question and check that text appears before entering the workspace.

## Verify your download

Compare the SHA-256 hash with the `SHA256SUMS.txt` attached to the **same release**. If it differs, do not run the installer.

- Windows PowerShell: `Get-FileHash .\XueMianTong-Setup-x64.exe -Algorithm SHA256`
- Mac Terminal: `shasum -a 256 XueMianTong-Mac-arm64.dmg`

## 中文说明

上方提供 Windows x64 和 Apple 芯片 Mac 安装包；新版不再支持 Intel Mac。Windows 运行 EXE；Mac 打开 DMG，将学面通拖入「应用程序」。首次打开后登录，设置语言和职位，再按提示检测系统声音。下载后可核对同一版本附带的 SHA-256。

如需帮助，请访问[学面通官网](https://xuexi.inono.xyz/www/?lang=zh-CN)。反馈请提供系统、客户端版本和复现步骤，避免公开账号凭据、简历和面试内容。
