<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄语</a> | 
  <a href="/docs/README.en.md">英语</a> | 
  <a href="/docs/README.es.md">西班牙语</a> | 
  <a href="/docs/README.zh.md">中文</a> | 
  <strong><-------</strong>
</p>



<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../media/logo-dark.png">
    <img alt="项目标志" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Stars&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
安装和配置 3x-ui + SSL 证书指南
</h1>

<h2 align="center">
> 💡 本文面向有经验的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对使用本项目可能产生的任何后果不承担任何责任。<br>
  使用该项目的风险由您自行承担。
</p>

<details align="center"> 
    <summary>⚠️ 完整免责声明 ⚠️</summary>
    
使用该镜像需自行承担风险。

1. 使用此镜像，即表示您自动同意相关许可协议的条款。

2. 作者不对镜像在特定目的下的准确性、完整性或合适性提供任何明示或暗示的保证。对使用或无法使用该镜像或其文档所产生的直接、间接、附带、间接或特殊损失，即使已提前提醒可能的此类损失，作者也概不负责。

3. 使用此镜像时，您确认并接受与使用此镜像相关的所有风险。此外，您亦同意作者不因使用该镜像所产生的任何问题或后果承担责任。

</details>

---

<h3 align="center"> 
💖 支持本项目 
</h3>

<p align="center"> 
如果该项目对您有帮助，您可以点亮小星星 :star2: 来支持我们。 
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="请作者喝咖啡">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="请作者喝咖啡">
  </a>
</p>

<h4 align="center"> 
即使是小小的捐赠，也将不胜感激，非常感谢。😌 
</h4>

<div align="center">

|  |  |
|-------------:|:-------------|
| **Tether USDT (BEP20)** |`0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Bitcoin (BTC)** |`1Dbwq9EP8YpF3SrLgag2EQwGASMSGLADbh`|
| **Ethereum (ERC20)** | `0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Binance Smart Chain (BEP20)** | `0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Solana (SOL)** | `yYYXsiVTzsvfvsMnBxfxSZEWTGytjAViE2ojf3hbLeF`|
| **Cloud tips** | [cloudtips](https://pay.cloudtips.ru/p/7249ba98) |

</div>

---

<p align="center">
  <sub> 感谢您关注本项目，并给予支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



## 📚 目录

- [介绍](#-介绍)

## 🔗 有用链接

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
  <a href="#-目录"> ⬆️ 返回顶部 </a> 
</h2>

<h1 align="center"> 
技术要求
</h1>

## 📊 推荐操作系统

<details> 
    <summary>⚙️ 展开描述</summary>

- Ubuntu 20.04+
- Debian 11+
- CentOS 8+
- OpenEuler 22.03+
- Fedora 36+
- Arch Linux
- Parch Linux
- Manjaro
- Armbian
- AlmaLinux 8.0+
- Rocky Linux 8+
- Oracle Linux 8+
- OpenSUSE Tubleweed
- Amazon Linux 2023
- Windows x64

</details> 

## 📊 支持的架构和设备

<details> 
    <summary>⚙️ 展开描述</summary>

我们的平台支持多种架构和设备，提供灵活的计算环境兼容性。以下为主要支持的架构：

- **amd64:** 常见于个人电脑和服务器，是大多数现代操作系统的标准架构。

- **x86 / i386:** 广泛用于台式机和笔记本。支持包括 `Windows, macOS 和 Linux` 在内的多种操作系统。

- **armv8 / arm64 / aarch64:** 针对智能手机、平板等现代移动和嵌入式设备。例如 `Raspberry Pi 4`, `Raspberry Pi 3`, `Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS` 等。

- **armv7 / arm / arm32:** 支持较老一代的移动和嵌入式设备。如 `Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2` 等。

- **armv6 / arm / arm32:** 用于非常老旧的嵌入式设备。如 `Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 比较老旧的架构，主要用于早期的嵌入式系统。

- **s390x:** 通常用于`IBM 大型计算机`，专为企业负载提供高性能和可靠性。

</details> 

## 📊 支持的语言

<details> 
    <summary>⚙️ 展开描述</summary>

- 英语
- 波斯语
- 繁体中文
- 简体中文
- 日语
- 俄语
- 越南语
- 西班牙语
- 印尼语
- 乌克兰语
- 土耳其语
- 葡萄牙语（巴西）

</details> 

## 📊 功能 || 特性

<details> 
    <summary>⚙️ 展开描述</summary>

- 系统状态监控
- 能搜索所有入站连接和客户端
- 支持主题：`深色 / 浅色`
- 支持多用户和多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、到期时间限制
- 可定制的 `Xray` 配置模板
- 支持通过 `HTTPS (自定义域名 + SSL 证书)` 访问面板
- 支持一键请求 `SSL 证书` 并自动续期
- 高级配置请参考面板选项
- 修复后的 `API 路由` (用户设置通过 `API` 创建)
- 支持通过面板调整不同参数的配置
- 支持通过面板导入/导出数据库功能

</details>

...
