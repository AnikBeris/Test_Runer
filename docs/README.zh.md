<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../media/logo-dark.png">
    <img alt="Project Logo" src="../media/logo-light.png" width="512" height="auto">
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
3x-ui安装及配置指南 + SSL证书
</h1>

<h2 align="center">
> 💡 本资料面向具有一定经验的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对使用此项目可能造成的任何后果不承担责任。<br>
  使用风险需自行承担。
</p>

<details align="center"> 
    <summary>⚠️全文⚠️</summary>

使用此镜像需自行承担风险。

1. 使用即表示您自动同意与此镜像相关的许可协议条款。

2. 作者对该镜像的准确性、完整性或适用于任何特定目的的保证，包括任何明示或暗示的保证，不承担责任。 
3. 无论是否已提前告知可能的损害，作者对使用或无法使用此镜像或其文档所造成的任何损害，均不承担责任，包括但不限于直接、间接、附带、偶然或特殊损失。

4. 使用此镜像即表示您确认并承担与其应用相关的所有风险。此外，您同意作者不对因使用产生的任何问题或后果承担责任。

</details> 

---

<h3 align="center"> 
💖 支持项目
</h3>

<p align="center"> 
若您觉得此项目对您有所帮助，请为其加星标以示支持。:star2: 
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
任何金额的捐赠都将受到热烈欢迎，非常感谢。😌 
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
  <sub>感谢您关注及支持本项目 💙</sub>
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
  <a href="#-目录">⬆️ 返回顶部</a> 
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

平台与多种架构和设备兼容，确保在多种计算环境中的灵活性。主要支持的架构如下：

- **amd64:** 常用于个人电脑和服务器，大多数现代操作系统所依赖的标准架构。

- **x86 / i386:** 广泛用于桌面和笔记本电脑，也被多种操作系统和应用支持，如`Windows, macOS 和 Linux`等。

- **armv8 / arm64 / aarch64:** 致力于现代移动及嵌入式设备，例如智能手机和平板。设备例如：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 用于旧型号移动及嵌入式设备。例如：`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 瞄准老旧嵌入式设备，例如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 老式架构，主要用于早期嵌入式系统。

- **s390x:** 用于`IBM`大型主机，专注高性能和可靠性。

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

## 📊 功能及特点

<details> 
    <summary>⚙️ 展开描述</summary>

- 系统状态监控
- 检索所有入站连接和客户端
- 主题：`暗黑/明亮`
- 多用户及多协议支持
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生XTLS协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、过期时间限制
- 可自定义的`Xray`配置模板
- 通过`HTTPS (自定义域名 + SSL证书)`访问面板支持
- 一键SSL证书申请及自动续期支持
- 更多高级配置请查看控制面板
- 修复的`API路由`（用户使用的设置可通过`API`创建）
- 可通过控制面板修改多维配置
- 数据库导入/导出支持

</details> 

<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开描述 </summary>

使用此镜像需自行承担风险。使用即表示您自动同意与此镜像相关的许可协议条款。

作者对该镜像的准确性、完整性或适用于任何特定目的的保证，包括任何明示或暗示的保证，不承担责任。无论是否已提前告知可能的损失，作者对因使用或无法使用该镜像或文档而导致的任何直接、间接、附带、偶然或特殊损失，均不承担责任。

使用即接受和承担所有相关风险。此外，您同意作者不对因其使用产生的任何问题或后果负责。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 返回顶部</a> 
</h2>

<h1 align="center"> 
SSL证书 - Cloudflare
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本内置通过`Cloudflare`申请`SSL证书`的功能。要使用此功能获取证书，请满足以下条件：

<details> 
    <summary> ⚙️ 展开描述 </summary>

- 使用`Cloudflare`注册的电子邮件
- Global API Key Cloudflare
- 通过`Cloudflare`将域名DNS指向当前服务器

## 如何获取Global API Key Cloudflare：

1. 在终端输入命令`x-ui`，然后选择`Cloudflare SSL Certificate`。

2. 访问链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`（如下图）。

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新认证，认证后会显示密钥（如下图）。

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

使用时只需输入域名、`email`及`API KEY`。示例如下图所示。

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 返回顶部</a> 
</h2>

<h1 align="center"> 
安装3X-UI
</h1>

# 1. 快速安装3X

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

# 2. 分步安装3X

<details> 
    <summary> ⚙️ 展开描述 </summary>

# 📊 安装必要的包

1. 更新系统：
```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要软件包：
```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装3X-UI面板

在服务器上运行下述命令来安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中会提示：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择`y`自行设置端口，或`n`由脚本自动分配端口。
请勿设置为标准端口`22, 80, 8080`，建议选择如`8181`等端口。

```sh
Username: 3favnjd8
Password: Msdf823Ll
Port: 40608
WebBasePath: vpkPI6ex9ajesDX
Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成步骤后即可通过路径连接至面板：

```sh
http://服务器IP地址:端口/WebBasePath (示例：http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

<div align="center">
  <img src="../media/Tutorial/Article_3/Login.png" alt="Login" width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
通用设置
</h1>

## 更新GeoSite GeoIP

<details> 
    <summary> ⚙️ 展开描述 </summary>

打开版本和更新选择面板。

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件`GeoSite`和`GeoIP`。

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅

<details> 
    <summary> ⚙️ 展开描述 </summary>

进入`设置`并启用订阅。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

点击`保存`并选择`重启面板`。

# X-Ray设置

## 基础连接

在`X-Ray设置`中选择`基础设置`，并设置如下图所示。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击`保存`并重启`Xray`。

</details> 

## DNS

<details> 
    <summary> ⚙️ 展开描述 </summary>

进入`X-Ray设置` -> `DNS`，点击`创建DNS`并依次输入以下地址：

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

完成后点击`保存`，并重新启动`Xray`。

</details>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
配置第一个连接
</h1>

## 现在可以开始配置第一个连接了。

在侧边菜单选择`连接` -> 点击`添加连接`。

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目根据 </strong> 
  <a href="/LICENSE">Apache许可证</a> 
  <strong>分发。</strong>
</p>

---

<h2 align="center"> 
详细文档，请参阅。
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
