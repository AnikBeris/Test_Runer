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
    <img alt="项目Logo" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=星标&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
3x-ui + SSL证书安装与配置指南
</h1>

<h2 align="center">
> 💡 本文面向有经验的用户。
</h2>

* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用本项目可能导致的任何后果承担责任。<br>
  使用本项目需自担风险。
</p>

<details align="center"> 
    <summary>⚠️完全文本⚠️</summary>
    
使用本项目需自担风险。

1. 使用本项目即表示您自动同意其相关许可证协议中的条款。

2. 作者不对本项目的准确性、完整性或适用性做任何明示或默示的保证。 
3. 作者不对因使用或无法使用本项目或其关联文档引起的任何损失（包括但不限于直接、间接、附带、间接或特殊损失）承担责任，即使已提前告知可能发生这样的损失。

4. 使用本项目即表示您接受并承担与其使用相关的所有风险。此外，您同意作者不对由于使用本项目而产生的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持本项目 
</h3>

<p align="center"> 
如果本项目对您有帮助，可以通过点击星标 :star2: 给予支持。
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="请我喝杯咖啡">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="请我喝杯咖啡">
  </a>
</p>

<h4 align="center"> 
任何小的捐赠都会受到热烈欢迎，非常感谢。😌 
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
  <sub> 感谢您对本项目的关注和支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 

## 📚 目录

- [简介](#-简介)

## 🔗 有用链接

---

<h2 align="center">
  <a href="#-目录"> ⬆️ 回到顶部 </a> 
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

我们的平台与广泛的架构和设备兼容，提供灵活的计算环境。支持的主要架构如下：

- **amd64:** 标准个人电脑和服务器架构，支持大多数现代操作系统。
- **x86 / i386:** 桌面与笔记本电脑常用架构，支持`Windows, macOS, Linux`。
- **armv8 / arm64 / aarch64:** 移动设备架构，如`Raspberry Pi`系列设备等。
- **armv7 / arm / arm32:** 较旧设备架构，如`Orange Pi Zero LTS, Raspberry Pi 2`等。
- **armv6 / arm / arm32:** 面向较旧嵌入式设备。
- **s390x:** 用于`IBM`的大型机架构。

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
- 巴西葡萄牙语

</details> 

## 📊 功能列表

<details> 
    <summary>⚙️ 展开描述</summary>

- 系统状态监控
- 全入站连接及客户端搜索
- 主题切换：`深色/浅色`
- 多用户及多协议支持
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持XTLS协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、过期时间设置
- 自定义`Xray`配置模板
- 支持`SSL证书`请求及自动续期
- 高级配置详情请参考控制面板

</details> 

<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开描述 </summary>

使用本项目需自担风险。使用即自动同意许可证条款。

作者不对项目的准确性、完整性或适用性做任何保证或承诺。不对直接、间接、附带或特殊损失负责。

使用即接受所有风险，作者不对因使用本项目而导致的任何问题或后果负责。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 回到顶部</a> 
</h2>

<h1 align="center"> 
Cloudflare SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包含通过 `Cloudflare` 请求`SSL证书`的内置功能。需要以下信息：

<details> 
    <summary> ⚙️ 展开描述 </summary>

- 注册在`Cloudflare`的电子邮件
- Global API Key Cloudflare
- 域名需通过`Cloudflare`解析指向当前服务器

## 如何获取Global API Key Cloudflare：

1. 在终端执行`x-ui`命令，选择`Cloudflare SSL Certificate`。

2. 打开链接: [Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`(查看截图下方步骤)。

4. 如需身份验证后显示密钥即可。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 回到顶部</a> 
</h2>

<h1 align="center"> 
安装3X-UI
</h1>


