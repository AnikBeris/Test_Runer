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
3x-ui 安装与 SSL 证书配置指南
</h1>

<h2 align="center">
> 💡 此内容适用于有一定经验的用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用本项目可能引发的任何后果承担责任。<br>
  自行承担使用风险。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
使用本项目需自行承担风险。

1. 使用该项目即表示您已自动同意附带的许可协议中的条款。

2. 作者对于本项目的准确性、完整性或适合特定用途的任何明示或暗示保证概不承担责任。 
3. 无论是否已警示可能存在的损失，作者对使用或无法使用本项目及其文档引起的任何损失，包括直接、间接、附带、继发或特殊损失，不负任何责任。

4. 使用本项目即表示您认可并接受与其使用相关的所有风险。此外，您同意作者不对因使用本项目导致的任何问题或后果承担责任。

</details> 

---

<h3 align="center"> 
💖 支持本项目 
</h3>

<p align="center"> 
如果您觉得本项目对您有帮助，可以给予支持，点亮一颗小星星✨。
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
即使很小的捐赠也备受欢迎，衷心感谢支持。😌 
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
  <sub> 感谢您对本项目的关注和支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



## 📚 目录

- [介绍](#-введение)




## 🔗 有用链接

  







* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
  <a href="#-введение"> ⬆️ 回到顶部 </a> 
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

我们的平台支持多种架构和设备，确保在多种计算环境中的灵活性。以下是主要支持的架构：

- **amd64**: 这种常见架构是个人计算机和服务器的标准，支持大多数现代操作系统的运行。

- **x86 / i386**: 广泛用于台式计算机和笔记本电脑。此架构拥有众多操作系统和应用支持，包括 `Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64**: 设计用于现代移动和嵌入式设备（如智能手机和平板电脑）。设备示例：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS` 等。

- **armv7 / arm / arm32**: 用于旧版移动和嵌入式设备，仍广泛用于设备如 `Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2` 等。

- **armv6 / arm / arm32**: 针对非常老的嵌入式设备，虽不常见，但仍可在 `Raspberry Pi 1, Raspberry Pi Zero/Zero W` 等设备上使用。

- **armv5 / arm / arm32**: 较老的架构，主要用于早期嵌入式系统。现已少见，但仍可能在较旧设备如早期版本的 `Raspberry Pi` 和一些旧智能手机中使用。

- **s390x:** 主要用于 `IBM` 大型机，为企业工作负载提供高性能和高可靠性。

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
- 监控所有入站连接及客户
- 主题支持：`深色/浅色模式`
- 支持多用户和多协议
- 支持的协议: `VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议: `RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、过期时间限制
- 可定制的 `Xray` 配置模板
- 管理面板通过 `HTTPS (自定义域名+SSL证书)` 访问支持
- 支持单击请求 `SSL证书` 及其自动续期
- 更多高级配置请参阅管理面板
- 修复的 `API 路由` (用户配置信息通过 `API` 创建)
- 管理面板支持按照不同参数修改配置
- 支持通过面板导出/导入数据库

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开说明 </summary>

使用本项目需自行承担风险。使用本项目即表示您同意附带的许可协议条款。

作者对于本项目的准确性、完整性或适合特定用途的任何明示或暗示保证概不承担责任。无论是否已警示可能存在的损失，作者对本项目及其文档的使用或无法使用而引起的任何直接、间接、附带或特殊损失，不负任何责任。

使用本项目即表示您认可并接受与使用相关的所有风险。此外，您同意作者不对其使用引发的任何问题或后果承担责任。

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-введение">⬆️ 回到顶部</a> 
</h2>



   
<h1 align="center"> 
Cloudflare SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包含通过 `Cloudflare` 请求 `SSL证书` 的内置功能。要使用此脚本获取证书，您需要：


<details> 
    <summary> ⚙️ 展开说明 </summary>

- 注册在 `Cloudflare` 的邮箱
- Global API Key Cloudflare
- 域名必须通过 `Cloudflare` 指向当前服务器 (DNS 配置)



## 如何获取 Global API Key Cloudflare:

1. 在终端执行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 打开链接: [Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key` (参见下图):

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要再次验证身份，之后将显示密钥 (参考下图):

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


使用过程中，只需填写您的域名、`email` 和 `API KEY`。示例如下：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 



<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h2 align="center">
  <a href="#-введение">⬆️ 回到顶部</a> 
</h2>


<h1 align="center"> 
3X-UI 安装
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

# 📊 安装必要软件包

1. 系统更新
在开始安装之前，确保您的系统已经更新，执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 必需的基本软件包

确保您的服务器已安装以下必要的软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装 3X-UI 控制面板

在服务器上输入下列命令以运行安装控制面板的脚本：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会提出以下问题：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择 `y` 可自行设置端口，选择 `n` 将由脚本自动随机分配端口。
请勿使用默认端口如 `22, 80, 8080`。推荐选择其他端口，例如 `8181`。


```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成这些步骤后，控制面板便会安装完成，可以通过浏览器输入路径连接到面板：

```sh
http://您的服务器IP地址:端口/WebBasePath
（例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX）
```

输入地址后，您会看到控制面板的登录页面，需要输入脚本提供的用户名和密码。

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

打开版本和更新选择面板

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新 `GeoSite` 和 `GeoIP` 数据文件

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 


## 启用订阅

<details> 
    <summary> ⚙️ 展开说明 </summary>

打开 `设置` 启用订阅功能

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击 `保存`，然后 `重启面板`

# X-Ray 设置

## 基础连接

进入 `X-Ray 设置` -> 点击 `常规` -> 打开子菜单 `基本连接`

设置如图所示

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击 `保存` 并 `重启 Xray`

</details> 





## DNS 设置

<details> 
    <summary> ⚙️ 展开说明 </summary>


进入 `X-Ray 设置` -> 点击 `DNS` -> 打开子菜单 `DNS`

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `添加 DNS` 然后依次输入 `DNS 地址`

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
配置第一个连接
</h1>

## 现在可以开始配置第一个连接。

在侧边菜单中选择 `"连接"` -> 点击 `"添加连接"`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>




<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h1 align="center"> 📜 License </h1>
<p align="center">
  <strong> 本项目使用 </strong> 
  <a href="/LICENSE">Apache License</a>分发
</p>

---

<h2 align="center"> 
请参阅文档以获取更多信息 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
