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
安装与配置 3x-ui + SSL 证书指南
</h1>

<h2 align="center">
> 💡 本文档面向具备一定技术基础的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用本项目产生的任何后果负责。<br>
  使用项目需自行承担风险。
</p>

<details align="center"> 
    <summary>⚠️完整声明⚠️</summary>
    
使用本软件需自行承担风险。

1. 使用本软件即表示您自动同意与其相关的许可协议条款。

2. 作者对本软件的准确性、完整性或适合特定用途不提供任何明示或暗示的保证。

3. 作者对使用或无法使用本软件及其附带文档造成的任何损失（包括但不限于直接、间接、偶然、特殊或后果性损失）概不负责，即使已事先被告知此类损失的可能性。

4. 使用本软件即表明您同意并承担所有与其使用相关的风险。同时，您也认可，作者不对使用本软件引发的任何问题或后果承担任何责任。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果您觉得本项目对您有用，可以点赞支持 :star2: 
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
热烈欢迎任何大小的捐赠，非常感谢。😌 
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
  <sub> 感谢您关注本项目并给予支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 目录

- [简介](#-简介)

## 🔗 相关链接

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
  <a href="#-目录"> ⬆️ 回到顶部 </a> 
</h2>

<h1 align="center"> 
技术需求
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
- OpenSUSE Tubleweed
- Amazon Linux 2023
- Windows x64

</details>

## 📊 支持的架构和设备

<details> 
    <summary>⚙️ 展开详情</summary>

平台支持多种架构及设备，可适配不同计算环境。以下列出主要支持的架构：

- **amd64:** 常用于台式机和服务器，支持大多数现代操作系统。
  
- **x86 / i386:** 多见于台式机和笔记本电脑，广泛支持 `Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 面向现代移动设备，例如 `Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS` 等。

- **armv7 / arm / arm32:** 支持较老款移动和嵌入式设备，如 `Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2` 等。

- **armv6 / arm / arm32:** 应用于非常老旧的嵌入式设备，如 `Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 更旧的嵌入式设备架构，很少见，比如早期 `Raspberry Pi` 和部分老款智能手机。

- **s390x:** 常用于 `IBM 大型主机`，适合企业级负载的场景。

</details>

## 📊 支持语言

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
- 支持用户和连接的搜索
- 主题：`深色/浅色`
- 多用户和多协议支持
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、时效控制
- 自定义 `Xray` 配置模板
- 支持通过 `HTTPS`（自定义域名 + SSL 证书）访问面板
- 一键请求 SSL 证书及自动续签功能
- 适合高级配置参数的面板支持
- 修复的 `API 路由`（通过 `API` 创建用户配置）
- 支持面板中根据不同参数更改配置
- 支持通过面板导入/导出数据库

</details>

<h1 align="center">
⚠️ 免责声明 ⚠️
</h1>

<details align="center"> 
    <summary> ⚙️ 展开详情 </summary>

使用本软件需自行承担风险。使用即意味着您自动同意与其相关的许可协议条款。

作者对其准确性、完整性或适合某一特定用途不提供任何明示或暗示的保证。作者对使用或无法使用本软件及其相关文档可能导致的任何损失（包括直接、间接、偶然、特殊或后果性损失）概不负责，即便已预先知晓损失可能性。

使用本软件即表明您承担所有使用风险。此外，您同意无论发生任何问题或后果，作者不承担责任。

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

脚本管理工具集成了通过 `Cloudflare` 请求 `SSL 证书` 的功能。申请证书需满足以下条件：

<details> 
    <summary> ⚙️ 展开详情 </summary>

- 注册在 `Cloudflare` 的电子邮箱
- Cloudflare Global API Key
- 域名需通过 `Cloudflare` 指向当前服务器（即 DNS 解析到服务器）

## 如何获取 Cloudflare 的 Global API Key:

1. 在终端中执行命令 `x-ui`，选择 `Cloudflare SSL Certificate`。
2. 前往链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)
3. 点击 `View Global API Key`（参考下图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新验证身份，验证后将显示 API Key（见下图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

使用时请输入您的域名、电子邮件和 API Key。例如：

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

# 1. 3X 快速安装

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

# 2. 分步骤安装 3X

<details> 
    <summary> ⚙️ 展开详情 </summary>

# 📊 安装必要的软件包

1. 更新系统
安装开始之前，请确保系统是最新的。运行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要的软件包
确保服务器上安装了以下必要的软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 面板

在服务器上运行以下脚本，安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中，脚本将询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择 `y` 手动设置端口，或选择 `n` 让脚本随机生成端口。
避免选择常见端口，如 `22、80、8080`，建议使用其他端口，例如 `8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成后可通过以下路径通过浏览器访问面板：

```sh
http://服务器IP地址:端口号/WebBasePath（示例: http://192.168.0.10:40608/vpkPI6ex9ajesDX）
```

在浏览器中输入路径后，将打开登录面板页面，需输入步骤中脚本生成的用户名和密码。

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

## 更新 GeoSite 与 GeoIP

<details> 
    <summary> ⚙️ 展开详情 </summary>

打开版本与更新选择面板

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件 `GeoSite` 和 `GeoIP`

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details>

## 激活订阅

<details> 
    <summary> ⚙️ 展开详情 </summary>

进入 `设置` 并开启订阅功能

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击 `保存` 和 `重启面板`。

# X-Ray 设置

## 基本连接

进入 `X-Ray 设置` -> 选择 `常规` -> 打开 `基本连接` 分项

按下图进行设置

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击 `保存` 和 `重启 Xray`。

</details>

## DNS

<details> 
    <summary> ⚙️ 展开详情 </summary>

进入 `X-Ray 设置` -> 选择 `DNS` -> 打开 `DNS` 分项

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `新建 DNS` 并依次输入以下 `DNS 地址`

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

完成后点击 `保存` 和 `重启 Xray`。

</details>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
配置第一个连接
</h1>

## 现在可以开始配置第一个连接了。

进入侧边菜单 `"连接"` -> 点击 `"添加新连接"`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目根据 </strong> 
  <a href="/LICENSE">Apache License</a> 进行分发
</p>

---

<h2 align="center"> 
查看完整文档以获取更多信息 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
