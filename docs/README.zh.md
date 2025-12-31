<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄文</a> |
  <a href="/docs/README.en.md">英文</a> |
  <a href="/docs/README.es.md">西班牙文</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../media/logo-dark.png">
    <img alt="项目 Logo" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=点赞&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
3x-ui + SSL 证书安装与配置指南
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
  作者不对使用该项目可能导致的任何后果负责。<br>
  该项目请在自担风险的情况下使用。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
使用本程序需自行承担风险。

1. 使用本程序即表示您自动同意与其相关的许可证条款。

2. 作者对本程序的准确性、完整性或适合性，不提供任何明示或暗示的担保。
3. 因使用本程序及其相关的文档或无法使用其造成的任何损失，包括但不限于直接、间接、附带或特殊损失，作者概不负责，即使已事先被告知相关风险的可能性。

4. 使用本程序，即表示您确认并承担所有相关的应用风险。此外，您同意作者不对使用本程序可能造成的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果此项目对您有帮助，请关注并标记为星标:star2: 
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="为我买杯咖啡">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="为我买杯咖啡">
  </a>
</p>

<h4 align="center"> 
无论捐赠多少，都深表感谢。 😌 
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
  <sub> 谢谢您对项目的关注与支持 💙 </sub>
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

## 📊 支持的架构与设备

<details> 
    <summary>⚙️ 展开描述</summary>

我们的平台支持多种架构和设备，提供在各种计算环境中的灵活性。以下是我们支持的主要架构：

- **amd64:** 常见于个人电脑和服务器，是大多数现代操作系统标准的架构。

- **x86 / i386:** 广泛应用于台式计算机和笔记本电脑，受到多个操作系统和应用程序的支持，例如 `Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 适用于现代移动和嵌入式设备，比如智能手机和平板。设备示例：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`，`Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 用于较旧的移动和嵌入式设备，如`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等。

- **armv6 / arm / arm32:** 面向非常旧的嵌入式设备，例如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 更老的架构，通常见于早期嵌入式系统，可用在较旧设备上，如早期版本的 `Raspberry Pi`及部分老式智能手机。

- **s390x:** 通常用于 `IBM` 大型机，针对企业负载提供高性能和高可靠性。

</details>

## 📊 支持的语言

<details> 
    <summary>⚙️ 展开描述</summary>

- 英文
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

## 📊 功能 || 特色

<details> 
    <summary>⚙️ 展开描述</summary>

- 系统状态监控
- 所有入站连接和客户端搜索
- 主题：`深色模式/浅色模式`
- 支持多用户和多协议
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、过期时间限制
- 可定制的 `Xray` 配置模板
- 支持通过 `HTTPS（自定义域名+SSL证书）访问面板`
- 一键申请 `SSL证书` 并自动续订
- 更多高级选项见面板
- 修复的 `API 路由`（用户设置通过 `API` 创建）
- 面板中支持按不同参数修改配置
- 支持通过面板导入/导出数据库

</details>

<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开描述 </summary>

使用本程序需自行承担风险。使用本程序即表示您自动同意与其相关的许可证条款。

作者对本程序的准确性、完整性或适用性，不提供任何明示或暗示的担保。作者对因使用或不能使用本程序及其附带文档的任何损失，包括但不限于直接、间接、附带或特殊损失，不承担任何责任，即使事先已告知存在此类损失的可能性。

使用本程序即表示您确认并承担所有与其应用相关的风险。此外，您同意作者不对使用本程序导致的任何问题或后果负责。

</details>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 回到顶部</a> 
</h2>

<h1 align="center"> 
Cloudflare 的 SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt="Cloudflare" width="50%">
</div>

管理脚本包含了通过 `Cloudflare` 请求 `SSL 证书` 的内置功能。要使用这个脚本获得证书，您需要：

<details> 
    <summary> ⚙️ 展开描述 </summary>

- 一个已经注册在 `Cloudflare` 上的邮箱
- Cloudflare 的 Global API Key
- 域名需要通过 `Cloudflare` 指向当前服务器（在 `DNS` 中设定）

如何获取 Cloudflare 的 Global API Key：

1. 在终端输入命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。
2. 点击链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)
3. 点击 `View Global API Key`（见下面截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt="API Key 1" width="70%">
</div>

4. 可能需要重复身份验证，之后将会显示 API Key（见下面截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt="API Key 2" width="70%">
</div>

使用时直接输入您的域名、`email` 和 `API KEY`。如下所示：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt="Detail Enter" width="70%">
</div>

</details>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 回到顶部</a> 
</h2>

<h1 align="center"> 
3X-UI 安装
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

# 📊 安装所需包

1. 系统更新
在安装前，请确保您的系统已更新。输入以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装所需依赖包

确保您的服务器上已安装必要的依赖包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 面板

在服务器上运行以下命令以启动安装脚本：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程会有以下提示：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择 `y` 可以自定义端口，选择 `n` 则脚本会随机分配端口。
请勿使用默认端口 `22, 80, 8080`，推荐选择如 `8181` 的端口。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成这些步骤后安装结束，通过浏览器输入以下网址访问面板：

```sh
http://Your_Server_IP_Address:Port/WebBasePath (e.g., http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

登录界面会要求输入安装脚本提供的用户名和密码。

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

## 更新 GeoSite 和 GeoIP 数据

<details> 
    <summary> ⚙️ 展开描述 </summary>

打开版本和更新选项

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件 `GeoSite` 和 `GeoIP`

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="更新 GeoSite 和 GeoIP" width="70%">
</div>

</details>

## 启用订阅

<details> 
    <summary> ⚙️ 展开描述 </summary>

转到 `设置` 并启用订阅

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成点击 `保存` 并 `重启面板`

# X-Ray 设置

## 基本连接

转到 `X-Ray 设置` -> 选择 `基本设置` -> 打开 `基本连接` 子菜单

参考以下截图进行设置：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="设置 Xray DNS" width="70%">
</div>

完成后点击 `保存` 和 `重启 Xray`.

</details>

## DNS

<details> 
    <summary> ⚙️ 展开描述 </summary>

转到 `X-Ray 设置` -> 选择 `DNS` -> 打开 `DNS` 子菜单

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="设置 Xray DNS" width="70%">
</div>

点击 `创建 DNS`，依次添加以下 `DNS 地址`：

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

完成后点击 `保存` 并 `重启 Xray`

</details>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
设置第一个连接
</h1>

## 现在可以开始设置第一个连接。

在侧边菜单中选择 `"连接"` -> 点击 `"添加连接"`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目基于 </strong> 
  <a href="/LICENSE">Apache 许可证</a> 
</p>

---

<h2 align="center"> 
查看文档 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄文</a> |
  <a href="/docs/README.en.md">英文</a> |
  <a href="/docs/README.es.md">西班牙文</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
