<p align="center">
  <strong>-------></strong>
  <a href="/README.md"> Рус文 </a> |
  <a href="/docs/README.en.md"> 英文 </a> |
  <a href="/docs/README.es.md"> 西班牙文 </a> |
  <a href="/docs/README.zh.md"> 中文 </a> |
  <strong><-------</strong>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../media/logo-dark.png">
    <img alt="项目标志" src="../media/logo-light.png" width="512" height="auto">
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
安装和配置 3x-ui + SSL证书的指南
</h1>

<h2 align="center">
> 💡 本文面向有一定基础的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对项目使用可能导致的任何后果负责。<br>
  使用一切后果由用户自行承担。
</p>

<details align="center"> 
    <summary>⚠️完整免责声明⚠️</summary>
    
使用此项目风险自负。

1. 通过使用本项目，您自动同意与其相关的许可协议条款。

2. 作者对于该项目的准确性、完整性或适用性不作任何明示或暗示的担保，也不承担任何责任。 
3. 作者对因使用或无法使用本项目或其相关文档而造成的任何损失，包括但不限于直接、间接、附带或特别损失不承担责任，即使提前告知有此类损失的可能。

4. 使用本项目即表明用户承担所有相关风险。此外，用户同意不会因项目使用过程中出现的问题或后果追究作者责任。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果你觉得此项目对你有帮助，可以给它点一颗小星星 :star2: 
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
所有捐款，无论多少，都表示衷心感谢。😌 
</h4>

<div align="center">

|  |  |
|-------------:|:-------------|
| **Tether USDT (BEP20)** |`0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Bitcoin (BTC)** |`1Dbwq9EP8YpF3SrLgag2EQwGASMSGLADbh`|
| **Ethereum (ERC20)** |`0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Binance Smart Chain (BEP20)** |`0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Solana (SOL)** |`yYYXsiVTzsvfvsMnBxfxSZEWTGytjAViE2ojf3hbLeF`|
| **Cloud tips** | [cloudtips](https://pay.cloudtips.ru/p/7249ba98) |

</div>

---

<p align="center">
  <sub> 感谢您关注和支持这个项目 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 目录

- [介绍](#-введение)

## 🔗 有用链接

---

<h2 align="center">
  <a href="#-содержание">⬆️ 返回顶部</a>
</h2>

<h1 align="center"> 
技术要求
</h1>

## 📊 推荐操作系统

<details> 
    <summary>⚙️ 查看详情</summary>

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

## 📊 支持的架构和设备

<details> 
    <summary>⚙️ 查看详情</summary>

我们的平台支持多种架构和设备，以适应不同的计算环境。以下是支持的主要架构：

- **amd64:** 常见的台式电脑和服务器架构，支持大多数现代操作系统。

- **x86 / i386:** 台式电脑和笔记本电脑广泛使用，支持`Windows, macOS 和 Linux`等系统。

- **armv8 / arm64 / aarch64:** 适用于现代移动和嵌入式设备，如`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 用于较老的移动和嵌入式设备，如`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等。

- **armv6 / arm / arm32:** 面向非常旧的嵌入式设备，例如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 更老的架构，以早期嵌入式系统为目标的设备，比如一些旧`Raspberry Pi`和智能手机。

- **s390x:** 常用于`IBM`大型主机上，提供高性能及可靠性。

</details> 

## 📊 支持语言

<details> 
    <summary>⚙️ 查看详情</summary>

- 英文
- 波斯文
- 繁体中文
- 简体中文
- 日语
- 俄语
- 越南语
- 西班牙语
- 印度尼西亚语
- 乌克兰语
- 土耳其语
- 葡萄牙语（巴西）

</details> 

## 📊 功能特色

<details> 
    <summary>⚙️ 查看详情</summary>

- 系统状态监控
- 所有入站连接和客户端的搜索
- 主题支持：`深色/浅色`
- 支持多用户和多协议
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct，Vision，REALITY`
- 流量统计、流量限制、过期时间限制
- 可自定义的`Xray`配置模板
- 面板支持通过 `HTTPS` 访问（自定义域+SSL证书）
- 支持一键申请`SSL证书`及其自动续期
- 更多高级配置选项可在面板中查看
- 可通过面板导入/导出数据库

</details> 

<h1 align="center">
⚠️ 免责声明 ⚠️
</h1>

<details align="center"> 
    <summary> ⚙️ 查看详情 </summary>

使用此项目风险自负。通过使用，您自动同意与其相关的许可协议条款。

作者对本项目的准确性、完整性或适用性不作任何担保。作者对因使用或无法使用本项目或文档导致的任何损失，包括但不限于直接、间接、附带或特殊损失，均不承担责任。

您确认自行承担使用本项目的所有风险，并同意作者不对因使用本项目引起的任何问题或后果负责。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-содержание">⬆️ 返回顶部</a>
</h2>

<h1 align="center"> 
Cloudflare SSL证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt="Cloudflare" width="50%">
</div>

管理脚本内置`SSL证书`的`Cloudflare`申请功能。申请证书需要：

<details>
    <summary> ⚙️ 查看详情 </summary>

- 注册在`Cloudflare`的电子邮件
- Cloudflare的Global API Key
- 域名需要通过`Cloudflare`DNS指向当前服务器

## 获取Cloudflare Global API Key的步骤：

1. 在终端执行命令`x-ui`，选择`Cloudflare SSL Certificate`。
2. 打开链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)
3. 点击`View Global API Key`（参考下图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt="API Key 1" width="70%">
</div>

4. 可能需要再次身份验证，之后会显示API Key（参考下图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt="API Key 2" width="70%">
</div>

使用时，请输入域名、`email`和`API KEY`。示例如下：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt="Detail Enter" width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-содержание">⬆️ 返回顶部</a>
</h2>

<h1 align="center"> 
安装 3X-UI
</h1>

# 1. 快速安装 3X

<details> 
    <summary> ⚙️ 查看详情 </summary>

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
    <summary> ⚙️ 查看详情 </summary>

# 📊 安装依赖包

1. 系统更新
确保系统已经更新，运行以下命令：
```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要依赖包
```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 面板
运行以下安装脚本：
```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程会提示：
```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```
选择`y`自定义端口，或者选择`n`使用随机端口。建议避免使用标准端口如 `22, 80, 8080`，可选择其他端口如 `8181`。

安装完成后，脚本会生成以下信息：
```sh
Username: 3favnjd8
Password: Msdf823Ll
Port: 40608
WebBasePath: vpkPI6ex9ajesDX
Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

通过浏览器访问：
```sh
http://服务器IP:生成的端口/WebBasePath(例如：http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在浏览器登录页面输入脚本提供的用户名和密码即可。

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

## 更新 GeoSite GeoIP

<details>
    <summary> ⚙️ 查看详情 </summary>

打开版本及更新设置面板：
<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新`GeoSite`和`GeoIP`数据文件：
<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅

<details> 
    <summary> ⚙️ 查看详情 </summary>

进入设置启用订阅功能：
<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击“保存”和“重新启动面板”。

# X-Ray 设置

## 基础连接

步骤：
进入`X-Ray设置` -> 选择`基本` -> 打开`基础连接`子选项。
按照以下截图设置：
<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

调整完成后点击“保存”和“重新启动Xray”。

</details> 

## DNS

<details> 
    <summary> ⚙️ 查看详情 </summary>

进入`X-Ray设置` -> 选择`DNS` -> 打开`DNS`子选项：
<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

依次添加以下`DNS地址`：
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

调整完成后点击“保存”和“重新启动Xray”。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
配置第一个连接
</h1>

## 现在可以配置第一个连接。

步骤：
在侧边菜单中，点击“连接” -> 点击“添加连接”。
<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可协议 </h1>
<p align="center">
  <strong> 此项目依据 </strong> 
  <a href="/LICENSE">Apache License协议</a> 
  <strong> 发行。</strong>
</p>

---

<h2 align="center"> 
查看项目文档
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md"> Рус文 </a> |
  <a href="/docs/README.en.md"> 英文 </a> |
  <a href="/docs/README.es.md"> 西班牙文 </a> |
  <a href="/docs/README.zh.md"> 中文 </a> |
  <strong><-------</strong>
</p>
