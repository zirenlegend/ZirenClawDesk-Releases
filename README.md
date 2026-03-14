# ZirenClawDesk Releases

[![Download](https://img.shields.io/github/downloads/zirenlegend/ZirenClawDesk-Releases/total.svg)](https://github.com/zirenlegend/ZirenClawDesk-Releases/releases)
[![Latest Release](https://img.shields.io/github/v/release/zirenlegend/ZirenClawDesk-Releases?label=latest)](https://github.com/zirenlegend/ZirenClawDesk-Releases/releases/latest)

This repository contains official release builds of **ZirenClawDesk** - a multi-model, multi-channel AI desktop workbench based on [OpenClaw](https://github.com/zirenlegend/openclaw).

## Download

Get the latest version from [Releases](https://github.com/zirenlegend/ZirenClawDesk-Releases/releases/latest).

### Windows

| Architecture | File |
|-------------|------|
| x64 (Intel/AMD) | `ZirenClawDesk-*-win-x64.exe` |
| ARM64 | `ZirenClawDesk-*-win-arm64.exe` |

### Linux

| Format | Architecture | File |
|--------|-------------|------|
| AppImage (Recommended) | x64 | `ZirenClawDesk-*-linux-x86_64.AppImage` |
| AppImage | ARM64 | `ZirenClawDesk-*-linux-arm64.AppImage` |
| Debian/Ubuntu | x64 | `ZirenClawDesk-*-linux-amd64.deb` |
| Debian/Ubuntu | ARM64 | `ZirenClawDesk-*-linux-arm64.deb` |
| RPM | x64 | `ZirenClawDesk-*-linux-x86_64.rpm` |

## Installation Notes

### Windows

- **SmartScreen warning**: Click "More info" → "Run anyway"
- The installer supports auto-update functionality

### Linux AppImage

```bash
# Add execute permission
chmod +x ZirenClawDesk-*.AppImage

# Ubuntu 22.04
sudo apt install libfuse2

# Ubuntu 24.04
sudo apt install libfuse2t64
```

### Linux .deb (Ubuntu 24.04)

```bash
# Install dependencies if needed
sudo apt install libgtk-3-0t64 libnotify4t64 libxss1t64

# Install the package
sudo dpkg -i ZirenClawDesk-*.deb
```

## Auto-Update

ZirenClawDesk includes built-in auto-update functionality. When a new version is released, you'll be notified and can update with one click.

## Support

- **Issues**: [GitHub Issues](https://github.com/zirenlegend/ZirenClawDesk-Releases/issues)
- **Discussions**: [GitHub Discussions](https://github.com/zirenlegend/ZirenClawDesk-Releases/discussions)

## License

Apache-2.0 License