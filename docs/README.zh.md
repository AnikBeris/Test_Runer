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
    <img alt="项目图标" src="../media/logo-light.png" width="512" height="auto">
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
3x-ui + SSL 证书安装和配置文章
</h1>

<h2 align="center">
> 💡 本文面向有经验的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️免责声明⚠️
</h2>

<p align="center">
  作者对使用本项目可能导致的任何后果概不负责。<br>
  使用时请自行承担相关风险。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>

使用本项目请自行承担所有风险。  

1. 使用本项目即代表您自动同意与之相关的许可协议条款。

2. 作者对于此项目的准确性、完整性或适用性都不提供任何明示或默示的保证。

3. 作者不对任何损失负责，包括但不限于直接、间接、附带、间接或特殊损失，无论这些损失是否因使用或试图使用此项目及其附属文档，或被提前告知可能发生此类损失。

4. 使用本项目时您确认并承担所有相关风险。同时，您同意，作者不会因使用本项目导致的任何问题或后果被追究责任。

</details> 

---

<h3 align="center"> 
💖支持本项目 
</h3>

<p align="center"> 
如果您觉得本项目对您有帮助，可以为其点击星标：:star2:
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="Buy Me a Coffee">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="Buy Me a Coffee">
  </a>
</p>

<h4 align="center">
您的捐助无论多少我们都将感激，并向您致以深深的感谢 😌 
</h1>

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
  <sub> 感谢您对本项目的关注与支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 目录

- [简介](#-简介)

## 🔗 实用链接

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
  <a href="#-目录">⬆️ 回到顶部</a> 
</h2>

<h1 align="center"> 
技术要求
</h1>

## 📊 推荐的操作系统

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

我们的平台兼容各种架构和设备，适应不同计算环境的需求。以下是支持的主要架构：

- **amd64:** 这一广泛使用的架构是个人电脑和服务器的标准，支持大多数现代操作系统的运行。
- **x86 / i386:** 常见于台式电脑和笔记本电脑，支持许多操作系统和应用程序，例如`Windows, macOS与Linux`。
- **armv8 / arm64 / aarch64:** 专为现代移动设备（如智能手机和平板电脑）设计，例如`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。
- **armv7 / arm / arm32:** 用于较旧的移动设备和嵌入式设备，仍在`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等设备中使用。
- **armv6 / arm / arm32:** 针对较早期的嵌入式设备，虽然不常见，但仍在一些老旧设备（如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`）中使用。
- **armv5 / arm / arm32:** 属于更加旧的架构，主要应用于早期嵌入式系统，如最早期`Raspberry Pi`版本和某些老旧智能手机。
- **s390x:** 这一架构通常用于IBM大型机，为企业级工作负载提供高性能和可靠性。

</details> 

## 📊 支持的语言

<details> 
    <summary>⚙️ 展开描述</summary>

- English
- Persian
- Traditional Chinese
- Simplified Chinese
- Japanese
- Russian
- Vietnamese
- Spanish
- Indonesian
- Ukrainian
- Turkish
- Português (Brazil)

</details> 

## 📊 功能与特点

<details> 
    <summary>⚙️ 展开描述</summary>

- 系统状态监控
- 入站连接和客户端查询
- 主题：`亮色 / 暗色`
- 支持多用户和多协议
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、到期时间限制
- 可自定义的`Xray`配置模板
- 支持通过`HTTPS（自定义域名 + SSL 证书）`访问面板
- 支持一键请求`SSL 证书`并自动续费
- 更多高级配置参数见控制面板
- 固定的`API 路径`（用户配置通过`API`完成）
- 支持通过面板按不同参数修改配置
- 支持通过面板导出/导入数据库

</details> 

<h1 align="center">
⚠️免责声明⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开描述 </summary>

使用本项目请自行承担所有风险。使用本项目即代表您自动同意与之相关的许可协议条款。  

作者对于本项目的准确性、完整性或适用性都不提供任何明示或默示的保证。作者不对任何损失负责，包括但不限于直接、间接、附带、间接或特殊损失，无论这些损失是否因使用或试图使用此项目及其附属文档，或被提前告知可能发生此类损失。

使用本项目时您确认并承担所有相关风险。同时，您同意，作者不会因使用本项目导致的任何问题或后果被追究责任。

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

管理脚本提供了通过`Cloudflare`请求`SSL 证书`的内置功能。要使用此脚本获取证书，您需要：

<details> 
    <summary> ⚙️ 展开描述 </summary>

- 在`Cloudflare`注册的电子邮箱
- Global API Key Cloudflare
- 域名需要通过`Cloudflare`指向（DNS设置）当前服务器

## 如何获取Global API Key Cloudflare：

1. 在终端执行命令`x-ui`，然后选择`Cloudflare SSL Certificate`。

2. 点击以下链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)。

3. 点击`View Global API Key`（参见如下截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要再次验证身份，之后密钥会显示出来（参见如下截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

使用时只需输入您的域名、`email`和`API KEY`。参考如下示例：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 回到顶部</a> 
</h2>

<h1 align="center"> 
3X-UI 的安装
</h1>

# 1. 快速安装 3X

<details> 
    <summary> ⚙️ 展开描述 </summary>

```sh
sudo apt update && sudo apt upgrade -y && \
sudo apt install -y git curl openssl qrencode systemd && \
rm -rf self_signed_certificate.sh && \
curl -O https://raw.githubusercontent.com/AnikBeris/self-signed-certificate/main/self_signed_certificate.sh && \
chmod +x self_signed_certificate.sh && \
bash ./self_signed_certificate.sh
```

</details> 

# 2. 分步安装 3X

<details> 
    <summary> ⚙️ 展开描述 </summary>

# 📊 安装所需软件包

1. 系统更新  

开始安装之前确保系统已更新。执行以下命令：  

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要的软件包  

确认服务器安装了必备软件包：  

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 面板

运行以下脚本开始在服务器上安装面板：  

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会询问：  

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

如果想自定义端口选择`y`，否则选择`n`让脚本随机分配端口。  
不要选择常用端口如`22, 80, 8080`，建议选择其他端口，比如`8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成这些步骤后，面板安装完成。可以通过以下地址在浏览器中访问：  

```sh
http://<您的服务器IP>:<端口>/<WebBasePath>(例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

输入地址后会跳转到登录面板页面，输入脚本提供的用户名和密码即可。

<div align="center">
  <img src="../media/Tutorial/Article_3/Login.png" alt="登录" width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
通用设置
</h1>

## 更新 GeoSite GeoIP

<details> 
    <summary> ⚙️ 展开描述 </summary>

打开版本和更新选项卡：

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新`GeoSite`和`GeoIP`数据文件：

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="更新 GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅

<details> 
    <summary> ⚙️ 展开描述 </summary>

进入`设置`，然后启用订阅：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="设置" width="70%">
</div>

点击保存后重新启动面板。

# X-Ray 设置

## 基础连接

进入`X-Ray 设置` -> 选择`基本` -> 打开子项`基础连接`：

按以下图片设置：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="设置 Xray DNS" width="70%">
</div>

完成后点击保存并重新启动 Xray。

</details> 

## DNS

<details> 
    <summary> ⚙️ 展开描述 </summary>

进入`X-Ray 设置` -> 选择`DNS` -> 打开子项`DNS`：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="设置 Xray DNS" width="70%">
</div>

点击`创建 DNS`依次输入以下`DNS 地址`：

```bash
tcp://8.8.8.8
```

```bash
tcp://1.1.1.1
```

```bash
tcp://9.9.9.9
```

<div align="center">
  <img src="../media/Tutorial/Article_3/DNS.png" alt="DNS" width="70%">
</div>

完成后点击保存并重新启动 Xray。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
配置首个连接
</h1>

## 现在可以开始配置首个连接

进入侧边菜单`“连接”` -> 点击`“添加连接”`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>

<p align="center">
  <strong> 本项目基于 </strong> 
  <a href="/LICENSE">Apache License</a> 
</p>

---

<h2 align="center"> 
请参考文档进行了解 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄语</a> |
  <a href="/docs/README.en.md">英语</a> |
  <a href="/docs/README.es.md">西班牙语</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
