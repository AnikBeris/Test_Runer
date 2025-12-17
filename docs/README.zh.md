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
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Stars&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
3x-ui 安装与配置 + SSL 证书教程
</h1>

<h2 align="center">
> 💡 该内容适合具有一定技术基础的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对使用本项目可能产生的任何后果不承担任何责任。<br>
  使用请自行承担风险。
</p>

<details align="center"> 
    <summary>⚠️完整免责声明⚠️</summary>
    
使用此项目需自担风险。

1. 使用即表示您自动同意与本项目相关的许可协议条款。

2. 作者不提供任何明示或暗示的保证，不保证其准确性、完整性或特定用途的适用性。
3. 作者对因使用或无法使用本项目或其相关文档而造成的任何损失（直接、间接、附带或特殊损失）不承担责任，即使已被告知可能存在此类损失的风险。

4. 使用本项目即表示您确认并承担所有相关风险。此外，您同意作者不对由此造成的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持该项目 
</h3>

<p align="center"> 
如果您觉得本项目对您有帮助，可以通过评分来支持我们。:star2: 
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
即使是再小的捐赠也非常感谢您的支持，谢谢您。 😌 
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
  <sub> 感谢您对项目的关注与支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 目录

- [简介](#-简介)

## 🔗 有用链接

---

<h2 align="center">
  <a href="#-目录"> ⬆️ 回到顶部 </a> 
</h2>

<h1 align="center"> 
技术需求
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

## 📊 支持的架构和设备

<details> 
    <summary>⚙️ 展开描述</summary>

我们的平台支持多种架构和设备，灵活适应各种计算环境。主要支持的架构如下：

- **amd64:** 常用的PC与服务器架构，支持大多数现代操作系统。

- **x86 / i386:** 常见于桌面PC与笔记本电脑，与多种操作系统和应用程序兼容，比如`Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 专为现代移动和嵌入式设备设计，如智能手机和平板电脑。例如：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 针对旧款移动和嵌入式设备，仍广泛用于`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 面向较老的嵌入式设备，如`Raspberry Pi 1`, `Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 更老的嵌入式架构，常用于过时硬件。

- **s390x:** 通常用于`IBM`大型主机，为企业负载提供高性能与可靠性。

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

## 📊 功能 || 特点

<details> 
    <summary>⚙️ 展开描述</summary>

- 系统状态监控
- 支持所有入站连接和客户端的搜索
- 主题切换：`暗色 / 浅色`
- 支持多用户与多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、时间到期限制
- 可配置的`Xray`配置模板
- 支持通过`HTTPS`访问面板（自定义域 + SSL证书）
- 支持一键申请`SSL认证`及自动续期
- 更多高级配置请查看管理面板
- 修正`API接口`（通过`API`创建用户设置）
- 支持按面板参数修改配置
- 支持面板上的数据库导入/导出

</details> 

<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开描述 </summary>

使用本项目需自担风险。使用即表示您自动同意与本项目相关的许可协议条款。

作者不提供任何明示或暗示的保证，不保证其准确性、完整性或特定用途的适用性。对因使用或无法使用本项目或其相关文档造成的损失（包括直接、间接、附带或特殊损失），作者不承担任何责任，即使已被告知可能存在此类损失的风险。

使用本项目即表明您已知悉并承担所有相关风险。此外，您同意作者不对因使用本项目造成的任何问题或后果负责。

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
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包括通过`Cloudflare`请求`SSL证书`的内置功能。要通过脚本获取证书，需要：

<details> 
    <summary> ⚙️ 展开描述 </summary>

- 注册在 `Cloudflare` 的邮箱账户
- `Cloudflare` 的 Global API Key
- 域名必须指向(在 DNS 中解析到)当前服务器并通过 `Cloudflare` 管理

## 如何获得 Global API Key:

1. 在终端运行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 点击 [Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens) 链接。

3. 点击`View Global API Key`（如下图所示）：  

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新验证身份，之后显示密钥（如下图所示）：    

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>  

使用时输入域名、邮箱及`API KEY`即可。如下示例：

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

# 📊 安装必要软件包

1. 更新系统
在安装之前，确保您的系统是最新的。执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要包
确保服务器安装了全部必需的软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 面板

在服务器上运行以下脚本来安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

在安装过程中，脚本会提出如下问题：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

回答 `y` 设置自定义端口，或输入 `n` 让脚本随机分配。
不要使用默认端口 `22, 80, 8080`，推荐使用其他端口，例如 `8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成以上步骤后，即可通过路径访问面板：

```sh
http://您的服务器 IP 地址:端口/WebBasePath（示例：http://192.168.0.10:40608/vpkPI6ex9ajesDX）
```

输入地址后会来到面板的登录界面，键入之前脚本提供的用户名及密码即可。

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
    <summary> ⚙️ 展开描述 </summary>

打开版本选择与更新设置界面

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新 `GeoSite` 和 `GeoIP` 数据文件

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅功能

<details> 
    <summary> ⚙️ 展开描述 </summary>

前往 `设置` 启用订阅

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击 `保存` 并重启面板。

# X-Ray 配置

## 基础连接设置

进入`X-Ray设置` -> 选择`基础选项` -> 打开“基础连接”小节

依照如下所示设置

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

设置完毕后点击 `保存` 并重启 Xray。

</details> 

## DNS 设置

<details> 
    <summary> ⚙️ 展开描述 </summary>

进入 `X-Ray设置` -> 选择 `DNS` -> 打开“DNS”小节

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建 DNS` 按钮，依次输入以下地址：

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

完成后点击 `保存` 并重启 Xray。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div> 

<h1 align="center"> 
第一个连接配置 
</h1>

## 现在可以开始配置第一个连接。

在侧边菜单中选择`“连接”` -> 点击`“添加连接”`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目根据 </strong> 
  <a href="/LICENSE">Apache License</a> 
  <strong> 分发。 </strong> 
</p>

---

<h2 align="center"> 
请阅读项目文档 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>  
