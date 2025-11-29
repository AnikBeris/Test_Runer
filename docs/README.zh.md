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
3x-ui + SSL 证书的安装与配置指南
</h1>

<h2 align="center">
> 💡 本教程面向有一定技术背景的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对因使用本项目导致的任何后果概不负责。<br>
  请自行承担风险使用。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
使用该镜像需自行承担风险。

1. 使用本项目即表示您已自动同意相关的许可协议条款。

2. 作者不对镜像的准确性、完整性或适用于特定用途做出任何明示或暗示的保证。
3. 作者不对因使用或无法使用该镜像或伴随的文档所导致的任何损失负责，包括但不限于直接、间接、偶然、连带或特殊损失，即使已提前获得相关风险提示。

4. 使用本项目即表示您理解并接受所有与使用相关的风险。此外，您同意作者不对因使用本项目导致的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果本项目对您有帮助，欢迎您为其加星点赞。:star2: 
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
再小的捐赠都备受欢迎, 万分感谢您的支持 😌 
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
  <sub> 感谢您对本项目的关注与支持 💙 </sub>
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

我们的平台支持广泛的架构和设备，确保在不同的计算环境中提供灵活性。以下是我们支持的主要架构：

- **amd64:** 通用架构，是个人电脑和服务器的标准架构，支持大多数现代操作系统。

- **x86 / i386:** 广泛用于台式机和笔记本电脑。支持众多操作系统和应用，包括`Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 适用于现代移动设备和嵌入式设备，如`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`，`Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 用于较旧的移动设备和嵌入式设备，如`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等。

- **armv6 / arm / arm32:** 面向较老的嵌入式设备，例如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 比较古老的架构，多用于早期嵌入式系统。

- **s390x:** 常用于`IBM`主机，提供高性能和可靠性，适用于企业级负载。

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

## 📊 功能特色

<details> 
    <summary>⚙️ 展开说明</summary>

- 系统状态监控
- 查看所有入站连接和客户端
- 支持主题：`深色 / 浅色`
- 多用户和多协议支持
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、到期时间限制
- 自定义`Xray`配置模板
- 支持通过`HTTPS (自定义域名 + SSL证书)`访问面板
- 支持一键请求`SSL证书`并自动更新
- 更多高级配置选项可在面板中设置
- 改进的`API路由`（用户设置通过`API`配置）
- 支持通过面板编辑基于多种参数的配置
- 数据库支持导入/导出功能

</details> 

<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开说明 </summary>

使用该镜像需自行承担风险。使用本项目即表示您已自动同意相关的许可协议条款。

作者不对镜像的准确性、完整性或适用于特定用途做出任何明示或暗示的保证。作者不对因使用或无法使用该镜像或相关文档所导致的任何损失负责，包括但不限于直接、间接、偶然、连带或特殊损失，即使已提前获得相关风险提示。

使用本项目即表示您理解并接受所有与使用相关的风险。此外，您同意作者不对因使用本项目导致的任何问题或后果负责。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-内容目录">⬆️ 返回顶部</a> 
</h2>

<h1 align="center"> 
Cloudflare SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本内置了通过`Cloudflare`请求`SSL证书`的功能。要使用此脚本获取证书，请确保具备以下条件：

<details> 
    <summary> ⚙️ 展开说明 </summary>

- 在`Cloudflare`注册的邮箱
- Cloudflare 全局 API 密钥
- 域名通过`Cloudflare`解析到当前服务器

## 如何获取 Cloudflare 全局 API 密钥：

1. 在终端输入命令 `x-ui`，选择`Cloudflare SSL Certificate`。

2. 访问链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新验证身份，验证后会展示密钥（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

输入您的域名、`Email`和`API KEY`，示例如下：

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

# 2. 分步安装 3X

<details> 
    <summary> ⚙️ 展开说明 </summary>

# 📊 安装必备软件包

1. 更新系统
在安装前，请确保您的系统是最新的，执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必备软件包

确保您的服务器已安装必要的软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装3X-UI面板

在服务器上安装面板，运行以下命令启动脚本：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中，脚本会询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

回答`y`可以自定义端口，回答`n`时脚本会随机分配端口。
注意：请勿使用常规端口如`22, 80, 8080`，建议选择其他端口，如`8181`。

安装完成后会显示如下信息：

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成上述步骤后，面板安装完成。可通过以下链接访问面板：

```sh
http://<您服务器的IP地址>:端口/WebBasePath (例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在浏览器中访问地址后，输入脚本生成的用户名和密码登录面板。

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

打开版本和更新选项页面。

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新`GeoSite`和`GeoIP`数据文件。

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅功能

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入`设置`界面，启动订阅功能。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击`保存`并`重启面板`。

# X-Ray 设置

## 基础连接

进入`X-Ray 设置` -> 选择`基础设置` -> 打开`基础连接`子菜单。

按图示进行配置。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击`保存`并`重启 X-ray`。

</details> 

## DNS 设置

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入`X-Ray 设置` -> 选择`DNS` -> 打开`DNS`子菜单。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击`创建 DNS`按钮，依次添加下列`DNS 地址`：

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

完成后点击`保存`并`重启 X-ray`。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
配置第一个连接
</h1>

## 现在可以开始配置第一个连接了。

在侧边菜单中选择`"连接"` -> 点击`"添加连接"`。

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可协议 </h1>
<p align="center">
  <strong> 本项目基于 </strong> 
  <a href="/LICENSE">Apache License</a> 分发
</p>

---

<h2 align="center"> 
请查阅完整文档 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
