<p align="center">
  <strong>-------></strong> 
  <a href="/README_en_EN.md">English</a> | 
  <a href="/README.md">Русский</a> 
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
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Звёзды&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
安装与设置 3x-ui + SSL证书的文章
</h1>

<h2 align="center">
> 💡 本文面向有一定经验的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️免责声明⚠️
</h2>
<p align="center">
  作者不对使用本项目可能产生的任何后果负责。<br>
  使用风险自负。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
使用此镜像需自行承担风险。

1. 使用该镜像即表示您自动接受与之相关的许可协议条款。

2. 作者对于该镜像和文档的正确性、完整性或是否适合特定用途不提供任何明示或隐含的担保。
3. 作者对因使用或无法使用镜像及相关文档造成的任何损失包括但不限于直接、间接、附带或特殊损失概不负责，即使已提前通知存在这种损失的可能性。

4. 使用该镜像即表示您确认并接受所有与使用相关的风险。此外，您同意作者不因使用该镜像可能引发的任何问题或后果承担责任。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果该项目对您有所帮助，可以通过给星标来表达支持 :star2: 
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
无论捐赠多少都深表感谢，真心感谢您的支持。😌 
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
  <sub> 感谢您对项目的关注和支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 内容目录

- [简介](#-简介)

## 🔗 有用链接

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
  <a href="#-内容目录"> ⬆️ 返回顶部 </a> 
</h2>

<h1 align="center"> 
技术要求
</h1>

## 📊 推荐的操作系统

<details> 
    <summary>⚙️ 展开说明</summary>

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
    <summary>⚙️ 展开说明</summary>

我们的平台兼容多种架构和设备，提供在各种计算环境中的灵活性。以下是我们支持的主要架构：

- **amd64:** 常见架构，个人电脑和服务器的标准，支持大多数现代操作系统。

- **x86 / i386:** 广泛用于桌面电脑和笔记本电脑。支持众多操作系统和应用，包括`Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 专为现代移动和嵌入式设备设计，例如智能手机和平板电脑。设备例子：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 用于较旧的移动和嵌入式设备。仍广泛适用于如`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 面向更老旧的嵌入式设备。虽然较罕见，但仍用于如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`等设备。

- **armv5 / arm / arm32:** 较早的架构，主要应用于早期嵌入式系统。现已较少使用，但可能会出现在过时的设备上，如早期`Raspberry Pi`和一些老旧智能手机。

- **s390x:** 通常用于`IBM`大型机，提供企业级工作负载的高性能和可靠性。

</details> 

## 📊 支持的语言

<details> 
    <summary>⚙️ 展开说明</summary>

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

## 📊 功能 || 特点

<details> 
    <summary>⚙️ 展开说明</summary>

- 系统状态监控
- 搜索所有传入连接和客户端
- 主题：`深色/浅色`
- 支持多用户和多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生的 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、到期时间限制
- 可定制的`Xray`配置模板
- 支持通过`HTTPS(专属域名 + SSL证书)`访问面板
- 支持一键请求`SSL证书`及其自动续期
- 更多高级配置参数详见面板
- 修复了`API路由`（用户设置通过`API`创建）
- 支持通过不同参数更改配置，面板中提供
- 支持通过面板导入/导出数据库

</details> 

<h1 align="center">
⚠️免责声明⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开说明 </summary>

使用此镜像需自行承担风险。使用该镜像即表示您自动接受与之相关的许可协议条款。

作者对于该镜像和文档的正确性、完整性或是否适合特定用途不提供任何明示或隐含的担保。作者对因使用或无法使用镜像及相关文档造成的任何损失包括但不限于直接、间接、附带或特殊损失概不负责，即使已提前通知存在这种损失的可能性。

使用该镜像即表示您确认并接受所有与使用相关的风险。此外，您同意作者不因使用该镜像可能引发的任何问题或后果承担责任。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-内容目录">⬆️ 返回顶部</a> 
</h2>

<h1 align="center"> 
Cloudflare SSL证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本中包含通过`Cloudflare`获取`SSL证书`的内置功能。要使用该脚本获取证书，您需要：

<details> 
    <summary> ⚙️ 展开说明 </summary>

- 注册于`Cloudflare`的电子邮箱
- Cloudflare Global API Key
- 域名必须通过`Cloudflare`DNS解析到当前服务器

## 如何获取 Cloudflare 的 Global API Key：

1. 在终端中执行命令`x-ui`，然后选择`Cloudflare SSL Certificate`。

2. 访问链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`(查看截图如下)：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 您可能需要再次进行身份验证，然后会显示 API Key (查看截图如下)：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

在使用时，只需输入您的域名，`email`和`API Key`。示例如下所示：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-内容目录">⬆️ 返回顶部</a> 
</h2>

<h1 align="center"> 
安装 3X-UI
</h1>

# 1. 快速安装 3X

<details> 
    <summary> ⚙️ 展开说明 </summary>

```sh
sudo apt update && sudo apt upgrade -y && \
sudo apt install -y git curl openssl qrencode systemd && \
rm -rf self_signed_certificate.sh && \
curl -O https://raw.githubusercontent.com/AnikBeris/self-signed-certificate/main/self_signed_certificate.sh && \
chmod +x self_signed_certificate.sh && \
bash ./self_signed_certificate.sh

```

</details> 

# 2. 分步骤安装 3X

<details> 
    <summary> ⚙️ 展开说明 </summary>

# 📊 安装所需的软件包

1. 更新系统
安装前确保系统是最新的。运行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必需的软件包

确保您的服务器安装了必要的软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 面板

要在服务器上安装面板，执行以下命令运行安装脚本：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装期间脚本会提问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

回答`y`可自行设置端口，回答`n`则脚本会自动分配端口。请避免使用常见端口（如`22, 80, 8080`），建议选择其他端口，例如`8181`。

```sh
用户名: 3favnjd8

密码: Msdf823Ll

端口: 40608

WebBasePath: vpkPI6ex9ajesDX

访问网址: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成上述步骤后，面板安装完成，可以通过浏览器访问面板路径：

```sh
http://您的服务器IP地址:端口号/WebBasePath(例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

输入地址后，您将看到登录框，需输入脚本安装期间提供的用户名和密码。

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

## 更新 GeoSite 和 GeoIP

<details> 
    <summary> ⚙️ 展开说明 </summary>

打开版本选择和更新面板:

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件`GeoSite`和`GeoIP`

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入设置页面启用订阅:

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击保存并返回面板。

# 设置 X-Ray

## 基本连接

进入`X-Ray设置`->选择`基础`->打开子项`基本连接`

根据图片设置所有项目:

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击保存并重新启动 Xray。

</details>

## DNS

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入`X-Ray设置`->选择`DNS`->打开子项`DNS`

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击`创建DNS`后依次输入以下地址:

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
设置首次连接
</h1>

## 现在可以开始设置第一个连接

进入侧边栏菜单`"连接"` -> 点击`"添加连接"`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜许可证 </h1>
<p align="center">
  <strong> 本项目基于 </strong> 
  <a href="/LICENSE">Apache License</a> 
</p>

---

<h2 align="center"> 
文档详情，请认真阅读
</h2>

<p align="center">
  <strong>-------></strong> 
  <a href="/README_en_EN.md"> English </a> | 
  <a href="/README.md"> Русский </a> 
  <strong><-------</strong>
</p>
