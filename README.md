# kidsblock-tools

KidsBlock 编译工具链托管仓库。

本仓库通过 **GitHub Releases** 托管 KidsBlock 所需的编译工具链，包括：

- `Arduino CLI` — Arduino 代码编译与烧录命令行工具
- `core-avr` — Arduino AVR 核心库（版本 1.8.6）
- `core-esp32` — ESP32 核心库（版本 3.2.0）
- `core-esp8266` — ESP8266 核心库（版本 3.1.2）
- `Python` — Micro:bit 烧录所需的 Python 环境（含 uflash、microfs）
- `firmwares` — 各硬件平台的实时固件

## 支持平台

| 平台 | 架构 | 资产文件名 |
| :--- | :--- | :--- |
| Windows | x64 / ia32 | `kidsblock-tools-win32-x64-{version}.zip` |
| macOS | x64 | `kidsblock-tools-darwin-x64-{version}.zip` |
| Linux | x64 | `kidsblock-tools-linux-x64-{version}.zip` |

## 使用方式

`openblock-link` 程序在**首次启动时**会自动检测本地 `tools/` 目录，若不存在则自动从本仓库的最新 Release 下载对应平台的工具包并解压缓存，无需手动操作。

## 版本说明

| 版本 | 说明 |
| :--- | :--- |
| v1.0.0 | 初始版本，基于 kidsblock-tools v1.0.0|
