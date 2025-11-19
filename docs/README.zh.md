<p align="center">
  <strong>-------></strong> 
  <a href="/README_en_EN.md">English</a> | 
  <a href="/README.md">Русский</a> 
  <strong><-------</strong>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./media/logo-dark.png">
    <img alt="Project Logo" src="./media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=星标&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="./media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
文章：安装与设置 3x-ui + SSL证书
</h1>

<h2 align="center">
> 💡 本文适用于有一定技术经验的用户。
</h2>

---

---

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用此项目可能产生的任何后果承担责任。<br>
  请自行承担风险使用。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
使用此项目请自行承担风险。

1. 使用此项目即表示您自动同意与其相关的许可协议内容。

2. 作者不对该项目的准确性、完整性或适用性提供任何明示或隐含的保证。
3. 作者不对因使用或无法使用该项目或其附属文档而产生的直接损失、间接损失、附带损失或特别损失承担责任，即使已告知可能存在此类损失的风险。

4. 使用此项目即表示您确认并承担所有相关风险。此外，您还同意因使用本项目而导致的任何问题或后果，作者不负任何责任。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果此项目对您有所帮助，欢迎为其点赞:star2: 
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="./media/buymeacoffe.png" alt="Buy Me a Coffee">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="./media/buymeacoffe.png" alt="Buy Me a Coffee">
  </a>
</p>

<h4 align="center"> 
无论捐赠额大小，热烈欢迎并衷心感谢！ 😌 
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
  <sub> 感谢您关注和支持该项目 💙 </sub>
</p>

---

---

---

## 📚 内容目录

- [介绍](#-介绍)

## 🔗 有用链接

  

---

---

---

<h2 align="center">
  <a href="#-内容目录"> ⬆️ 回到顶部 </a> 
</h2>

<h1 align="center"> 
技术需求
</h1>

## 📊 推荐操作系统

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

我们的平台支持广泛的架构和设备，能够在各类计算环境中提供灵活性。以下是主要支持的架构：

- **amd64:** 此架构是个人电脑和服务器的标准，为多数现代操作系统提供无缝运行。

- **x86 / i386:** 广泛应用于台式机和笔记本电脑。许多操作系统和应用程序支持此架构，包括 `Windows, macOS 和 Linux` 等。

- **armv8 / arm64 / aarch64:** 针对现代移动设备及嵌入式设备，例如智能手机和平板电脑。设备示例：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS` 等。

- **armv7 / arm / arm32:** 是较老款的移动设备及嵌入式设备的架构。仍广泛用于 `Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2` 等设备。

- **armv6 / arm / arm32:** 面向更老款的嵌入式设备。虽然较少使用，但仍适用于如 `Raspberry Pi 1, Raspberry Pi Zero/Zero W` 等设备。

- **armv5 / arm / arm32:** 更老的架构，主要用于早期嵌入式系统。当前较少见，但仍可用于一些旧设备，如早期版 `Raspberry Pi` 或部分旧款智能手机。

- **s390x:** 此架构通常应用于 `IBM` 大型机，为企业工作负载提供高性能和可靠性。

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
- 搜索所有入站连接和客户端
- 主题选择：`深色/浅色`
- 支持多用户、多协议
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、到期时间限制
- 可定制的 `Xray` 配置模板
- 支持通过 `HTTPS (自定义域 + SSL证书)` 访问面板
- 支持一键申请 `SSL证书` 及自动续期
- 更多高级配置可通过面板查看
- 修复的 `API 路径` (用户设置通过 `API` 创建)
- 支持根据面板中提供的不同参数修改配置
- 支持通过面板导入/导出数据库

</details> 

<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开说明 </summary>

使用此项目请自行承担风险。使用即表示您自动同意相关的许可协议内容。

作者不对该项目的准确性、完整性或适用性提供任何明示或隐含的保证。作者不对因使用或无法使用该项目或其附属文档而产生的直接损失、间接损失、附带或特别损失承担责任，即使已告知可能存在此类损失的风险。

使用此项目即表示您确认并承担所有相关风险。此外，您还同意因使用本项目而导致的任何问题或后果，作者不负任何责任。

</details> 

<div align="center">
  <img src="./media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-内容目录">⬆️ 回到顶部</a> 
</h2>

<h1 align="center"> 
SSL证书 Cloudflare
</h1>

<div align="center">
  <img src="./media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本内置了通过 ` Cloudflare ` 请求 ` SSL证书 ` 的功能。要使用脚本获得证书，您需要满足以下条件：

<details> 
    <summary> ⚙️ 展开说明 </summary>

- 在 `Cloudflare` 注册的邮箱
- Global API Key Cloudflare
- 域名需通过 `Cloudflare` 定向（DNS解析）至当前服务器

## 如何获取 Cloudflare Global API Key：

1. 在终端执行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 前往以下链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key`（如下图所示）：

<div align="center">
  <img src="./media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 您可能需要重新认证身份认证。之后会显示 API Key（如下图所示）：

<div align="center">
  <img src="./media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

在使用时，只需输入您的域名、`email` 和 `API KEY`. 示例如下：

<div align="center">
  <img src="./media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 

<div align="center">
  <img src="./media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-内容目录">⬆️ 回到顶部</a> 
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

# 2. 分步安装 3X

<details> 
    <summary> ⚙️ 展开说明 </summary>

# 📊 安装必要包

1. 系统更新
安装前确保系统已更新。执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装依赖包

确保您的服务器已安装所需包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 面板

运行安装脚本以安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本将询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择 `y` 自定义端口，或者选择 `n` 自动分配端口
不要使用标准端口 `22, 80, 8080`。推荐选择其他端口，例如 `8181`

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成这些步骤后，面板安装完成，可通过以下路径使用浏览器访问面板：

```sh
http://服务器的IP地址:端口/WebBasePath (例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在浏览器中输入地址后，您会进入面板登录界面，输入脚本生成的用户名和密码即可进入。

<div align="center">
  <img src="./media/Tutorial/Article_3/Login.png" alt="Login" width="70%">
</div>

</details> 

<div align="center">
  <img src="./media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
通用设置
</h1>

## 更新 GeoSite GeoIP

<details> 
    <summary> ⚙️ 展开说明 </summary>

打开版本选择与更新面板：

<div align="center">
  <img src="./media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新 `GeoSite` 和 `GeoIP` 数据文件：

<div align="center">
  <img src="./media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅功能

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入 `设置`，开启订阅功能：

<div align="center">
  <img src="./media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

设置完成后点击 `保存` 并 `重启面板`

# 配置 X-Ray

## 基本连接

进入 `X-Ray设置` -> 选择 `基本` -> 打开子栏 `基本连接`

按照下图进行配置：

<div align="center">
  <img src="./media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

设置完成后点击 `保存` 并 `重启Xray`

</details> 

## DNS

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入 `X-Ray设置` -> 选择 `DNS` -> 打开子栏 `DNS`

<div align="center">
  <img src="./media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建DNS` 并依次添加以下 `DNS地址`：

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
  <img src="./media/Tutorial/Article_3/DNS.png" alt="DNS" width="70%">
</div>

设置完成后点击 `保存` 并 `重启Xray`

</details> 

<div align="center">
  <img src="./media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
配置第一个连接
</h1>

## 现在可以开始配置第一个连接。

进入侧边栏的 `"连接"` -> 点击 `"添加连接"`

<div align="center">
  <img src="./media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

---

<div align="center">
  <img src="./media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目基于 </strong> 
  <a href="/LICENSE">Apache License</a> 
  发布
</p>

---

<h2 align="center"> 
查看文档 
</h2>

<p align="center">
  <strong>-------></strong> 
  <a href="/README_en_EN.md"> English </a> | 
  <a href="/README.md"> Русский </a> 
  <strong><-------</strong>
</p>
