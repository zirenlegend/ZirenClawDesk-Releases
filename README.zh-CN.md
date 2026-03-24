# ZirenClawDesk 发布仓库

[!\[Download\](https://img.shields.io/github/downloads/zirenlegend/ZirenClawDesk-Releases/total.svg null)](https://github.com/zirenlegend/ZirenClawDesk-Releases/releases)
[!\[Latest Release\](https://img.shields.io/github/v/release/zirenlegend/ZirenClawDesk-Releases?label=latest null)](https://github.com/zirenlegend/ZirenClawDesk-Releases/releases/latest)

本仓库包含 **ZirenClaw **的官方发布版本 - 一款基于 [OpenClaw](https://github.com/zirenlegend/openclaw) 的多模型、多渠道 AI 桌面工作台。

## 下载

从 [Releases](https://github.com/zirenlegend/ZirenClawDesk-Releases/releases/latest) 获取最新版本。

### Windows

| 架构              | 文件                          |
| --------------- | --------------------------- |
| x64 (Intel/AMD) | `ZirenClaw-*-win-x64.exe`   |
| ARM64           | `ZirenClaw-*-win-arm64.exe` |

### Linux

| 格式            | 架构    | 文件                                  |
| ------------- | ----- | ----------------------------------- |
| AppImage（推荐）  | x64   | `ZirenClaw-*-linux-x86_64.AppImage` |
| AppImage      | ARM64 | `ZirenClaw-*-linux-arm64.AppImage`  |
| Debian/Ubuntu | x64   | `ZirenClaw-*-linux-amd64.deb`       |
| Debian/Ubuntu | ARM64 | `ZirenClaw-*-linux-arm64.deb`       |
| RPM           | x64   | `ZirenClaw-*-linux-x86_64.rpm`      |

## 安装说明

### Windows

- **SmartScreen 警告**：点击"更多信息" → "仍要运行"
- 安装程序支持自动更新功能

### Linux AppImage

```bash
# 添加执行权限
chmod +x ZirenClaw-*.AppImage

# Ubuntu 22.04
sudo apt install libfuse2

# Ubuntu 24.04
sudo apt install libfuse2t64
```

### Linux .deb (Ubuntu 24.04)

```bash
# 如需安装依赖
sudo apt install libgtk-3-0t64 libnotify4t64 libxss1t64

# 安装软件包
sudo dpkg -i ZirenClaw-*.deb
```

## 自动更新

ZirenClawDesk 内置自动更新功能。当有新版本发布时，您将收到通知，可以一键更新。

## 支持

- **问题反馈**：[GitHub Issues](https://github.com/zirenlegend/ZirenClawDesk-Releases/issues)
- **讨论交流**：[GitHub Discussions](https://github.com/zirenlegend/ZirenClawDesk-Releases/discussions)

## 许可证

Apache-2.0 许可证
