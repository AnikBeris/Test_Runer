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
    <img alt="项目Logo" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=星级&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
3x-ui安装与SSL证书配置指南
</h1>

<h2 align="center">
> 💡 本文面向具有一定技术基础的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用该项目可能导致的任何后果负责。<br>
  请自行承担风险。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
该镜像使用存在风险，请谨慎操作。

1. 使用该镜像即表示您已同意与其相关的许可协议条款。

2. 作者不对该镜像的准确性、完整性或适用于任何特定用途的适用性提供任何明示或默示的保证。 
3. 作者不对因使用或无法使用该镜像或附随文档而产生的任何损失负责，包括但不限于直接、间接、附带、间接或特殊损失，即使此前已被告知可能性。

4. 使用该镜像即表示您已确认并接受使用中可能产生的全部风险。此外，您同意作者不对因其使用造成的任何问题或后果承担责任。

</details> 

---

<h3 align="center"> 
💖 支持项目
</h3>

<p align="center"> 
如果该项目对您有所帮助，请为其点赞并给予星标。:star2: 
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="请我喝咖啡">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="请我喝咖啡">
  </a>
</p>

<h4 align="center"> 
无论捐款多少，您的支持对我都意义重大，非常感谢。😌 
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

## 🔗 相关链接

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
  <a href="#-目录"> ⬆️ 返回顶部 </a> 
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

## 📊 支持的架构及设备

<details> 
    <summary>⚙️ 展开说明</summary>

我们的平台与多种架构和设备兼容，以确保适用多种计算环境。以下列出我们主要支持的架构：

- **amd64:** 这一常见架构是个人计算机和服务器的标准，支持多数现代操作系统的流畅运行。

- **x86 / i386:** 在台式机和笔记本电脑上广泛使用的架构，支持许多操作系统和应用程序，包括`Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 针对现代的移动和嵌入式设备开发，例如智能手机和平板电脑。示例设备：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W, Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 为较旧的移动和嵌入式设备设计。仍广泛应用于`Orange Pi Zero LTS`, `Orange Pi PC Plus`, `Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 面向非常旧的嵌入式设备。尽管不太常见，但仍适用于`Raspberry Pi 1`, `Raspberry Pi Zero/Zero W`设备。

- **armv5 / arm / arm32:** 更老的架构，主要用于早期嵌入式系统。如今较为罕见，但可能仍用于一些旧设备，如早期`Raspberry Pi`版本和一些旧手机。

- **s390x:** 常见于`IBM`大型机，为企业负载提供高性能及高可靠性。

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
- 所有入站连接和客户端搜索
- 主题支持：`暗色/浅色`
- 支持多用户和多协议
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生XTLS协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、到期时间设置
- 可自定义的`Xray`配置模板
- 支持通过`HTTPS`访问面板（自有域名+SSL证书）
- 支持一键SSL证书请求与自动续期
- 对于高级配置选项，请参考面板
- 已修复的`API路由`（用户设置通过`API`创建）
- 支持面板参数的多种配置修改
- 数据库的导入/导出支持

</details> 

<h1 align="center">
⚠️ 免责声明 ⚠️
</h1>

<details align="center"> 
    <summary> ⚙️ 展开说明 </summary>

该镜像使用存在风险。使用该镜像即表示您已同意与其相关的许可协议条款。

作者不对该镜像的准确性、完整性或适用于任何特定用途的适用性提供任何明示或默示的保证。作者不对因使用或无法使用该镜像或附随文档而产生的任何损失负责，包括但不限于直接、间接、附带、间接或特殊损失，即使此前已被告知可能性。

使用该镜像即表示您已确认并接受使用中可能产生的全部风险。此外，您同意作者不对因其使用造成的任何问题或后果承担责任。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 返回顶部</a> 
</h2>

<h1 align="center"> 
Cloudflare SSL证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包含一个通过`Cloudflare`请求`SSL证书`的内置功能。要通过此脚本获取证书，您需要：

<details> 
    <summary> ⚙️ 展开说明 </summary>

- 在`Cloudflare`注册的电子邮件地址
- Global API Key Cloudflare
- 通过`Cloudflare`将域名指向当前服务器（已配置DNS）

## 如何获取Global API Key Cloudflare:

1. 在终端中运行命令`x-ui`，然后选择`Cloudflare SSL Certificate`。

2. 点击链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`（见下图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新验证身份。此后将显示密钥（见下图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

使用时，只需输入您的域名、`email` 和 `API KEY`。以下为示例：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 返回顶部</a> 
</h2>

<h1 align="center"> 
安装3X-UI
</h1>

# 1. 快速安装3X

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

# 2. 分阶段安装3X

<details> 
    <summary> ⚙️ 展开说明 </summary>

# 📊 安装必要的软件包

1. 升级系统  
在安装之前，请确保您的系统是最新的，运行如下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要的软件包  
确保您的服务器已安装必要软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装3X-UI面板

在服务器上运行以下脚本以进行安装：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择`y`手动设置端口，或`n`由脚本自动设置。建议避免使用标准端口`22, 80, 8080`，如`8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

通过以上步骤，面板安装成功。打开浏览器并访问以下地址登录：

```sh
http://您的服务器IP地址:端口/WebBasePath（如: http://192.168.0.10:40608/vpkPI6ex9ajesDX）
```

输入地址后，会跳转到面板登录页面，输入脚本提供的用户名及密码以登录。

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

## 更新GeoSite与GeoIP

<details> 
    <summary> ⚙️ 展开说明 </summary>

打开版本和更新设置面板：

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件`GeoSite`和`GeoIP`：

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入`设置`并启用订阅功能：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击`保存`并进行`面板重启`。

# X-Ray设置

## 基础连接

进入`X-Ray设置` -> 选择`基础设置` -> 打开`基本连接`。

如图设置：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击`保存`并`重启Xray`。

</details> 

## DNS

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入`X-Ray设置` -> 选择`DNS` -> 打开`s DNS`。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击`新建DNS`依次输入如下地址：

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

完成后点击`保存`并`重启Xray`。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
首次连接配置
</h1>

## 现在可以开始配置首次连接。

进入侧栏菜单`“连接”` -> 点击`“添加连接”`。

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目遵循 </strong> 
  <a href="/LICENSE">Apache License</a> 
</p>

---

<h2 align="center"> 
文档，请查阅。 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄文</a> |
  <a href="/docs/README.en.md">英文</a> |
  <a href="/docs/README.es.md">西班牙文</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
