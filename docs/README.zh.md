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
3x-ui安装与配置教程 + SSL证书
</h1>

<h2 align="center">
> 💡 此材料适用于已具备相关基础的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️免责声明⚠️
</h2>

<p align="center">
  作者对使用此项目可能造成的任何后果不承担责任。<br>
  使用前请自担风险。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
使用此项目需要自行承担风险。

1. 如果使用此项目，即表示您自动同意其相关的许可协议条款。

2. 作者不对该项目的准确性、完整性或适用性提供任何明示或默示的保证。 
3. 对于因使用或无法使用该项目或相关文档而产生的任何损失，作者概不负责，包括但不限于直接、间接、附带、从属或特殊损失，即使已经事先告知可能造成此类损失。

4. 使用此项目即表示您完全了解并愿意承担与其应用相关的所有风险。此外，您同意作者不对因其使用导致的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持本项目 
</h3>

<p align="center"> 
如果您觉得此项目对您有帮助，可以给它一个星标:star2:。
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
所有捐赠，不管金额大小，我们都非常感谢。😌
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
  <sub> 感谢您的关注与支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 目录

- [简介](#简介)

## 🔗 有用链接

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
  <a href="#目录"> ⬆️ 返回目录 </a> 
</h2>

<h1 align="center"> 
技术要求
</h1>

## 📊 推荐操作系统

<details> 
    <summary>⚙️ 展开详情</summary>

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
- OpenSUSE Tumbleweed
- Amazon Linux 2023
- Windows x64

</details> 

## 📊 支持的架构及设备

<details> 
    <summary>⚙️ 展开详情</summary>

我们的平台支持多种架构和设备，为各种计算环境提供灵活性。以下为主要支持的架构：

- **amd64:** 常见的PC和服务器标准架构，支持绝大多数现代操作系统。

- **x86 / i386:** 广泛用于桌面电脑和笔记本电脑，支持多个操作系统及应用程序，包括`Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 专为智能手机、平板等现代设备设计，例如`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 针对老旧设备，仍适用于`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等。

- **armv6 / arm / arm32:** 用于更老的嵌入式设备，如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 面向早期嵌入系统，尽管现已少见，但如旧版`Raspberry Pi`及部分旧智能手机仍在使用。

- **s390x:** 常用于`IBM`大型机，提供高性能及可靠性，用于企业负载。

</details> 

## 📊 支持的语言

<details> 
    <summary>⚙️ 展开详情</summary>

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

## 📊 功能特点

<details> 
    <summary>⚙️ 展开详情</summary>

- 系统状态监控
- 搜索所有入站连接和客户端
- 主题支持：`深色/浅色`
- 支持多用户及多协议
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生XTLS协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、过期时间限制
- 可定制的`Xray`配置模板
- 支持通过`HTTPS`访问控制面板（自定义域 + SSL证书）
- 一键请求并自动续订`SSL证书`
- 高级配置参数请参考控制面板
- 修复的`API路由`（用户设置通过`API`创建）
- 支持通过面板调整多种配置参数
- 支持通过面板导入/导出数据库

</details> 

<h1 align="center">
⚠️免责声明⚠️
</h1>

<details align="center"> 
    <summary> ⚙️ 展开详情 </summary>

使用此项目需自担风险。若使用即表示您同意其相关许可协议。

作者不对项目的准确性、完整性或适用性作任何明示或暗示的担保。同时，对于因使用或无法使用项目或相关文档而造成的直、间接损失，作者概不负责。使用此项目即表示您了解并愿承担所有与其使用有关的风险。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#目录">⬆️ 返回目录</a> 
</h2>

<h1 align="center"> 
Cloudflare SSL证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包含通过`Cloudflare`请求`SSL证书`的内置功能。您需要以下内容以通过脚本获取证书：

<details> 
    <summary> ⚙️ 展开详情 </summary>

- 使用`Cloudflare`注册的邮箱
- Cloudflare的Global API Key
- 使用`Cloudflare`将域名解析至当前服务器

## 获取Cloudflare的Global API Key:

1. 在终端运行指令`x-ui`，然后选择`Cloudflare SSL Certificate`。

2. 打开链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新认证，认证成功后会显示API Key（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

使用时输入您的域名、邮箱及`API KEY`，如下图所示：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#目录">⬆️ 返回目录</a> 
</h2>

<h1 align="center"> 
3X-UI安装
</h1>

# 1. 3X快速安装

<details> 
    <summary> ⚙️ 展开详情 </summary>

```sh
sudo apt update && sudo apt upgrade -y && \
sudo apt install -y git curl openssl qrencode systemd && \
rm -rf self_signed_certificate.sh && \
curl -O https://raw.githubusercontent.com/AnikBeris/self-signed-certificate/main/self_signed_certificate.sh && \
chmod +x self_signed_certificate.sh && \
bash ./self_signed_certificate.sh
```

</details> 

# 2. 分步骤安装3X

<details> 
    <summary> ⚙️ 展开详情 </summary>

# 📊 安装必要的包

1. 系统更新
在安装前，请确保您的系统已经更新。执行以下指令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必需的包

确保您的服务器已安装以下必要包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装3X-UI面板

在服务器上运行以下脚本进行安装：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装期间脚本会提示：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择`y`可手动设置端口，选择`n`将由脚本自动设置端口。建议勿使用默认端口，选择其它，例如`8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成后可通过浏览器访问面板地址：

```sh
http://服务器_IP地址:端口/WebBasePath(例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

输入浏览器页面后，会进入登录界面，输入脚本提示的用户名及密码。

<div align="center">
  <img src="../media/Tutorial/Article_3/Login.png" alt="Login" width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
常规设置
</h1>

## 更新GeoSite及GeoIP

<details> 
    <summary> ⚙️ 展开详情 </summary>

打开面板设置界面

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新`GeoSite`及`GeoIP`数据文件

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅服务

<details> 
    <summary> ⚙️ 展开详情 </summary>

进入`设置`然后启用订阅服务

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后，点击`保存`并`重启面板`。

# X-Ray设置

## 基础连接

进入`X-Ray设置` -> 选择`基础设置` -> 打开`基础连接`

按照下图设置

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击`保存`，选择`重启Xray服务`

</details> 

## DNS设置

<details> 
    <summary> ⚙️ 展开详情 </summary>

进入`X-Ray设置` -> 选择`DNS设置` -> 打开`DNS`

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击`新增DNS`，逐条添加以下`DNS`地址:

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

完成后点击`保存`并选择`重启Xray服务`。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
第一个连接设置
</h1>

## 现在设置第一个连接。

在侧边菜单中点击`"连接"` -> 点击`"添加连接"`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目采用 </strong> 
  <a href="/LICENSE">Apache License</a> 
</p>

---

<h2 align="center"> 
请阅读相关文档 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
