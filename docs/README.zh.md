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
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Звёзды&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
3x-ui 安装与配置文章 + SSL 证书
</h1>

<h2 align="center">
> 💡 本文面向有一定技术背景的用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对任何使用本项目可能导致的后果不承担任何责任。<br>
  使用者需自担风险。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
使用本项目需自行承担风险。

1. 使用本项目即表明您自动同意与其相关的许可协议条款。

2. 作者不对本项目在准确性、完整性或适用于任何具体目标方面提供任何明示或暗示的担保。 
3. 对使用或无法使用本项目及其随附文档而导致的任何损失，包括但不限于直接、间接、偶然、后果性或特别损失，作者概不负责，即使此前已被告知可能会造成这样的损失。

4. 使用该项目即表明您已确认并自愿承担与其使用相关的所有风险。此外，您也同意作者对因使用本项目而产生的任何问题或后果不承担责任。

</details> 

---

<h3 align="center"> 
💖 支持本项目 
</h3>

<p align="center"> 
如果此项目对您有帮助，请给它点亮一颗小星星:star2: 
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
无论金额多大，捐赠都深受欢迎，感谢您的支持。😌 
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
  <sub> 感谢您对本项目的支持和关注 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



## 📚 目录

- [介绍](#-介绍)




## 🔗 相关链接







* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
  <a href="#-目录"> ⬆️ 返回顶部 </a> 
</h2>

<h1 align="center"> 
系统要求
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



## 📊 支持的架构与设备

<details> 
    <summary>⚙️ 展开描述</summary>

我们的平台支持多种架构和设备，能够适应各种计算环境。以下是我们支持的主要架构列表：

- **amd64:** 这种常见架构是个人电脑和服务器的标准，能够顺畅地支持大多数现代操作系统。

- **x86 / i386:** 主流桌面电脑和笔记本使用的架构，得到广泛的操作系统与应用支持，包括 `Windows, macOS and Linux` 等。

- **armv8 / arm64 / aarch64:** 专为现代移动及嵌入式设备设计，例如智能手机与平板。支持设备例子：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS` 等。

- **armv7 / arm / arm32:** 更早的移动与嵌入式设备架构，如 `Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2` 等。

- **armv6 / arm / arm32:** 针对非常旧的嵌入式设备，如 `Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 更旧的嵌入系统架构，主要存在于早期 `Raspberry Pi` 和部分老款智能手机中。

- **s390x:** 通常用于 `IBM` 主机，提供企业级负载的高性能和可靠性。

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




## 📊 功能 || 特性

<details> 
    <summary>⚙️ 展开描述</summary>

- 系统状态监控
- 所有入站连接与客户端的搜索
- 主题支持：`黑暗/明亮`
- 支持多用户与多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、过期时间限制
- 可定制的 `Xray` 配置模板
- 支持通过 `HTTPS` 的管理界面（自定义域名 + SSL 证书）
- 支持一键申请 `SSL 证书` 并自动更新
- 对高级配置选项请参考控制面板
- 修复了 `API 路由`（用户设置通过 `API` 创建）
- 支持在面板中通过多种参数更改配置
- 支持通过面板导出/导入数据库

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary>⚙️ 展开描述</summary>

使用本项目需自行承担风险。使用即表明您同意与其相关的许可协议条款。

作者不对本项目的准确性、完整性或适合任何具体目的提供明示或暗示的任何担保。对于任何因使用或无法使用本项目及其文档产生的损失，包括但不限于直接、间接、附带的损失，作者概不负责。

使用本项目即表明您确认并接受与应用本项目相关的所有风险。此外，您同意作者对由此使用引发的任何问题或后果不承担责任。

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-目录">⬆️ 返回顶部</a> 
</h2>



   
<h1 align="center"> 
Cloudflare SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本带有一键申请 `SSL 证书` 的功能，通过 `Cloudflare` 完成。要通过脚本获取证书，您需要：


<details> 
    <summary>⚙️ 展开描述</summary>

- 注册在 `Cloudflare` 的电子邮件
- Global API Key Cloudflare
- 域名需要通过 `Cloudflare` 定向到当前服务器（DNS 记录需正确配置）



## 如何获取 Global API Key:

1. 在终端运行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 打开链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key`（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要再次身份验证。然后会显示 API Key（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


在使用时，输入您的域名、`email` 和 `API KEY`。例子如下图所示：

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
3X-UI 安装步骤
</h1>


# 1. 快速安装 3X

<details> 
    <summary>⚙️ 展开描述</summary>


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
    <summary>⚙️ 展开描述</summary>

# 📊 安装必要依赖

1. 系统更新
在开始安装之前，请确保系统已更新。运行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装依赖包

确保您的服务器安装了这些必要依赖：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装 3X-UI 面板

运行以下命令通过脚本安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

回答 `y` 自定义端口，或选 `n` 由脚本随机分配。
请不要使用默认端口 `22, 80, 8080` 等，建议选择随机端口，如 `8181`。


```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成此步骤后，面板安装完毕，可以通过浏览器访问以下地址：

```sh
http://IP_您服务器的地址:端口/WebBasePath(例: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

输入地址后，页面会跳转至登录界面，输入脚本提供的用户名和密码即可登录。

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

## 更新 GeoSite 与 GeoIP 数据

<details> 
    <summary>⚙️ 展开描述</summary>

打开版本和更新设置菜单：

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新 `GeoSite` 和 `GeoIP` 数据：

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 


## 启用订阅功能

<details> 
    <summary>⚙️ 展开描述</summary>

进入 `设置` 页面启用订阅功能：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成设置后点击 `保存` 并重启面板。

# X-Ray 设置

## 基础连接配置

进入 `X-Ray 设置` -> 选择 `基础设置` -> 打开子选项 `基础连接`

按照下图设置：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成设置后点击 `保存` 并重启 Xray。

</details> 





## DNS 设置

<details> 
    <summary>⚙️ 展开描述</summary>


进入 `X-Ray 设置` -> 子分类选择 `DNS`

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建 DNS` 依次输入以下 `DNS 地址`：

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

完成设置后点击 `保存` 并重启 Xray。

</details> 






<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
首次连接设置
</h1>

## 现在可以进行首次连接设置。

在左侧菜单选择 `"连接"` -> 点击 `"添加连接"` 按钮：

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>




<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 此项目依据 </strong> 
  <a href="/LICENSE">Apache License</a> 
  <strong> 进行分发 </strong>
</p>

---

<h2 align="center"> 
阅读相关文档 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
