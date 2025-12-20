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
    <img alt="项目 Logo" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=星标&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="空格" width="90%">
</div>

<h1 align="center"> 
3x-ui安装与SSL证书设置指南
</h1>

<h2 align="center">
> 💡 该内容面向有经验的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️免责声明⚠️
</h2>

<p align="center">
  作者对于使用该项目可能引发的任何后果概不负责。<br>
  使用时请自行承担风险。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
使用此模板需承担相应风险。

1. 使用本模板即表示您同意与模板相关的许可协议条款。

2. 作者不对本模板的准确性、完整性或针对特定用途的适用性提供任何明示或暗示的保证。
3. 作者对于因使用或无法使用本模板或其附带文档而产生的任何损失（直接、间接、附带、后果性或特殊损失）概不负责，即使事先已被告知可能会有此类损失。

4. 使用本模板即表明您确认并接受与其应用相关的所有风险。此外，您同意作者不得因使用本模板引发的任何问题或后果被追究责任。

</details> 

---

<h3 align="center"> 
💖 支持项目
</h3>

<p align="center"> 
如果您觉得此项目对您有帮助，可以通过给星标来评价它。:star2:
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="请我喝杯咖啡">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="请我喝杯咖啡">
  </a>
</p>

<h4 align="center"> 
所有捐赠都将非常感激，无论金额大小，谢谢您的支持。😌 
</h1>

<div align="center">

|  |  |
|-------------:|:-------------|
| **Tether USDT (BEP20)** |`0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Bitcoin (BTC)** |`1Dbwq9EP8YpF3SrLgag2EQwGASMSGLADbh`|
| **Ethereum (ERC20)** | `0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Binance Smart Chain (BEP20)** | `0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Solana (SOL)** | `yYYXsiVTzsvfvsMnBxfxSZEWTGytjAViE2ojf3hbLeF`|
| **Cloud tips** | [Cloudtips](https://pay.cloudtips.ru/p/7249ba98) |

</div>

---

<p align="center">
  <sub> 感谢您关注和支持本项目 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 内容目录

- [简介](#-简介)

## 🔗 相关链接

---

<h2 align="center">
  <a href="#-内容目录">⬆️ 回到顶部</a> 
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
- OpenSUSE Tumbleweed
- Amazon Linux 2023
- Windows x64

</details> 

## 📊 支持的架构和设备

<details> 
    <summary>⚙️ 展开详情</summary>

我们的平台支持多种架构和设备，具有灵活的计算环境使用特性。以下罗列了主要支持的架构：

- **amd64:** 这种流行的架构是个人电脑和服务器的标准，支持大部分现代操作系统。

- **x86 / i386:** 广泛应用于台式机和笔记本电脑，支持包括`Windows, macOS和Linux`在内的多种操作系统和应用程序。

- **armv8 / arm64 / aarch64:** 针对现代移动和嵌入式设备设计，例如`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 用于较旧的移动和嵌入式设备，例如`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等。

- **armv6 / arm / arm32:** 面向非常旧的嵌入式设备，例如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 更旧的架构，用于早期嵌入式系统。

- **s390x:** 通常用于`IBM`大型机，为企业工作负载提供高性能和可靠性解决方案。

</details> 

## 📊 支持的语言

<details> 
    <summary>⚙️ 展开详情</summary>

- 英语
- 波斯语
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

## 📊 功能 || 特性

<details> 
    <summary>⚙️ 展开详情</summary>

- 系统状态监控
- 查找所有入站连接及客户端
- 支持`深色模式 / 浅色模式`
- 支持多用户及多协议
- 支持协议: `VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生`XTLS`协议: `RPRX-Direct, Vision, REALITY`
- 流量统计、限制、时间过期限制
- 可配置的`Xray`配置模板
- 支持通过`HTTPS`访问面板（自定义域名 + SSL证书）
- 支持一键申请并自动续期`SSL认证`
- 更多高级设置详见面板
- 修复的`API路由`（用户设置由`API`管理）
- 支持多参数配置的修改（详见面板）
- 支持通过面板进行数据库导入/导出

</details> 

<h1 align="center">
⚠️免责声明⚠️
</h1>

<details align="center"> 
    <summary> ⚙️ 展开详情 </summary>

使用此模板需承担相应风险。使用本模板即表示您同意与模板相关的许可协议条款。

作者不对本模板的准确性、完整性或针对特定用途的适用性提供任何明示或暗示的保证。作者对于因使用或无法使用本模板或其附带文档而产生的任何损失（直接、间接、附带、后果性或特殊损失）概不负责，即使事先已被告知可能会有此类损失。

使用本模板即表明您确认并接受与其应用相关的所有风险。此外，您同意作者不得因使用本模板引发的任何问题或后果被追究责任。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="空格" width="90%">
</div>

<h2 align="center">
  <a href="#-内容目录">⬆️ 回到顶部</a> 
</h2>

<h1 align="center"> 
Cloudflare SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloudflare " width="50%">
</div>

管理脚本包含一个通过`Cloudflare`请求SSL证书的集成功能。要用此脚本获取证书，您需要：

<details> 
    <summary> ⚙️ 展开详情 </summary>

- 注册了`Cloudflare`的电子邮件
- Global API Key Cloudflare
- 域名需通过`Cloudflare`解析并指向当前服务器

## 如何获取Global API Key Cloudflare：

1. 在终端执行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 点击链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key` （参见下面的截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要再次身份验证。通过验证后将显示密钥（参见截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

实际使用时，需输入您的域名、`email`及`API KEY`。如下为示例：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details>  

<div align="center">
  <img src="../media/image0.gif" alt="空格" width="90%">
</div>

<h2 align="center">
  <a href="#-内容目录">⬆️ 回到顶部</a> 
</h2>

<h1 align="center"> 
3X-UI 安装
</h1>

# 1. 快速安装 3X

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

# 2. 分步安装 3X

<details> 
    <summary> ⚙️ 展开详情 </summary>

# 📊 必要包安装

1. 系统更新
在开始安装前，请确保您的系统已更新。执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要包

确保您的服务器已安装所需的包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 3X-UI 面板安装

要在服务器上安装面板，请运行以下脚本命令：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择`y`来自行设置端口，或选择`n`由脚本自动设置端口。 请勿使用标准端口`22, 80, 8080`。建议选择其他端口，如`8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成这些步骤后，面板的安装即完成。您可以通过以下路径访问面板：

```sh
http://您的服务器IP地址:端口/WebBasePath（例：http://192.168.0.10:40608/vpkPI6ex9ajesDX）
```

在浏览器输入地址后，将跳转到面板登录页面，输入之前获取的用户名和密码即可。

<div align="center">
  <img src="../media/Tutorial/Article_3/Login.png" alt="Login" width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="空格" width="90%">
</div>

<h1 align="center"> 
通用设置
</h1>

## 更新 GeoSite 和 GeoIP

<details> 
    <summary> ⚙️ 展开详情 </summary>

进入版本和更新设置界面：

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件 `GeoSite` 和 `GeoIP`：

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅

<details> 
    <summary> ⚙️ 展开详情 </summary>

进入 `设置`，启用订阅功能：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击 `保存` 并 `重启面板`。

# X-Ray 设置

## 基础连接配置

进入 `X-Ray设置 -> 基础` -> 打开子选项 `基础连接`。

按图配置所有项：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击 `保存` 并 `重启Xray`。

</details> 

## DNS 

<details> 
    <summary> ⚙️ 展开详情 </summary>

进入 `X-Ray设置 -> DNS -> 子选项 DNS`：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建DNS` 并依次输入`DNS地址`：

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

完成后点击 `保存` 并 `重启Xray`。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="空格" width="90%">
</div>

<h1 align="center"> 
第一次连接的设置
</h1>

## 现在可以配置第一个连接了。

进入侧边菜单 `"连接"` -> 点击按钮 `"添加连接"`。

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="空格" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目根据 </strong> 
  <a href="/LICENSE">Apache 协议</a> 
  <strong> 分发 </strong> 
</p>

---

<h2 align="center"> 
请查阅文档了解更多内容 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄语</a> |
  <a href="/docs/README.en.md">英语</a> |
  <a href="/docs/README.es.md">西班牙语</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
