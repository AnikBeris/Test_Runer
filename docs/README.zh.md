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
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Stars&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
3x-ui安装和配置指南 + SSL证书
</h1>

<h2 align="center">
> 💡 本文档面向有经验的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对使用本项目的任何潜在后果不承担任何责任。<br>
  使用需自行承担风险。
</p>

<details align="center"> 
    <summary>⚠️完整说明⚠️</summary>
    
使用本项目需自行承担风险。

1. 使用本项目时，您即默认同意与其相关的许可协议条款。

2. 作者对本项目的准确性、完整性或特定用途适用性不提供任何明示或暗示的保证。
3. 对因使用或无法使用本项目或相关文档而导致的任何直接、间接、附带、间接或特殊损害，包括但不限于经济损失，即使作者提前被告知仍不承担责任。

4. 使用本项目即表示您确认并自愿承担使用带来的所有风险。此外，您同意作者不对因使用本项目而导致的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果本项目对您有所帮助，请为其点赞加星 :star2:
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="向项目作者捐赠">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="向项目作者捐赠">
  </a>
</p>

<h4 align="center"> 
任何数额的捐赠都受到热烈欢迎，感谢大力支持😌 
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
  <sub> 感谢您对本项目的关注和支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 内容目录

- [简介](#-简介)

## 🔗 相关链接


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

我们的平台与各种架构和设备兼容，提供多样化计算环境的灵活性。以下为主要支持的架构：

- **amd64:** 常见的架构，普遍用于个人电脑和服务器，同时支持当代大多数操作系统。

- **x86 / i386:** 通常用于桌面电脑和笔记本电脑的广泛支持架构，兼容 `Windows, macOS 和 Linux`等多个操作系统。

- **armv8 / arm64 / aarch64:** 为现代移动设备和嵌入式设备（如智能手机和平板电脑）设计。设备示例：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 用于较老的移动和嵌入式设备；仍然广泛应用于诸如 `Orange Pi Zero LTS`, `Orange Pi PC Plus`, `Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 面向较旧的嵌入式设备，例如 `Raspberry Pi 1`, `Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 主要与早期嵌入式系统相关，现代使用较少。

- **s390x:** 常见于 `IBM`主机架构，支持高性能、可靠的企业级工作负载。

</details> 

## 📊 支持的语言

<details> 
    <summary>⚙️ 展开说明</summary>

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
- 葡萄牙语(巴西)

</details> 

## 📊 功能 & 特点

<details> 
    <summary>⚙️ 展开说明</summary>

- 系统状态监测
- 搜索所有传入连接及客户端
- 黑暗/明亮主题
- 支持多用户与多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 原生 XTLS协议支持：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制和到期时间设置
- 可自定义的 `Xray` 配置模板
- 支持通过 `HTTPS（独立域名 + SSL证书）` 访问管理面板
- 支持一键 SSL证书申请及其自动更新
- 更多高级配置请见管理面板
- 修正了API路由（用户可通过 `API` 自定义设定）
- 支持通过面板多种参数调整配置
- 支持面板的数据导出/导入

</details> 

<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开说明 </summary>

使用本项目需自担风险。使用项目即表示默认接受有关的许可协议。

作者对本项目的准确性、完整性或适用性不作任何明示或暗示的保证。作者对因使用或无法使用项目及文档所造成的任何后果（包括直接损失或间接损失等）不承担责任。

使用本项目的同时，您应确认并接受所有相关风险。此外，作者不能对任何与使用本项目有关的问题或结果负责。

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

管理脚本内置通过 `Cloudflare` 请求 `SSL证书` 的功能。如需使用该脚本获取证书，您需要：

<details> 
    <summary> ⚙️ 展开说明 </summary>

- 在 `Cloudflare` 注册的邮箱
- Cloudflare 的 Global API Key
- 通过 `Cloudflare` 将域名解析至当前服务器



## 如何获取 Cloudflare 的 Global API Key:

1. 执行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 访问链接: [Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key`（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要再次身份验证，随后会显示 API 密钥（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

使用密钥时，按提示输入域名、`email` 和 `API KEY`。如下图所示：

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
3X-UI的安装
</h1>

# 1. 一键安装 3X

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

# 📊 安装所需包

1. 更新系统
确保系统已更新，运行以下指令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要组件

确保已安装组件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 管理面板

在服务器执行以下命令安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中，脚本会提示：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择 `y` 自定义端口，或 `n` 让脚本随机分配。
避免设置标准端口 `22, 80, 8080`。建议选择其他端口，例如 `8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成安装后可通过浏览器访问：

```sh
http://服务器IP地址:端口/WebBasePath(例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在面板登录界面，输入脚本生成的用户名和密码以登录。

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

## 更新 GeoSite 和 GeoIP 数据

<details> 
    <summary> ⚙️ 展开说明 </summary>

打开版本及更新设置面板：

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新 `GeoSite` 和 `GeoIP` 数据文件：

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅功能

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入 `设置` -> 启用 `订阅功能`：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击 `保存` 并 `重启面板`。

# X-Ray设置

## 基本连接设置

进入 `X-Ray设置` -> 选择 `通用设置` -> 打开 `基本连接` 子项目。

按如下设置：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

设置完成后，点击 `保存` 并 `重启 Xray`。

</details> 

## DNS 配置

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入 `X-Ray设置` -> 选择 `DNS` -> 打开 `DNS`子项：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建DNS` 依次录入 `DNS地址`：

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

完成后，点击 `保存` 并 `重启 Xray`。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
配置第一条连接
</h1>

## 现在可创建首个连接。

进入菜单 `"连接"` -> 点击 `"添加连接"`：

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong>本项目基于 </strong> 
  <a href="/LICENSE">Apache开源许可证</a> 
</p>

---

<h2 align="center"> 
阅读相关文档
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄语</a> |
  <a href="/docs/README.en.md">英语</a> |
  <a href="/docs/README.es.md">西班牙语</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
