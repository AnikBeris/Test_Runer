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
    <img alt="项目标志" src="../media/logo-light.png" width="512" height="auto">
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
3x-ui + SSL证书安装与配置教程
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
  作者对因使用本项目可能导致的任何后果不承担责任。<br>
  使用风险自负。
</p>

<details align="center"> 
    <summary>⚠️全文⚠️</summary>
    
使用此镜像风险自负。

1. 使用本镜像即表示您自动同意与其相关的许可协议条款。

2. 作者不对该镜像的准确性、完整性或适用性提供任何明示或暗示的保证。 
3. 作者对因使用或无法使用本镜像或相关文档可能导致的直接、间接、附带或特殊损失概不负责，即使已经提前告知可能发生这些损失的可能性。

4. 使用此镜像即表示您确认并接受与其使用相关的所有风险。另外，您同意作者不对因使用本镜像而引起的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果本项目对您有用，您可以通过标星支持我们。:star2: 
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
即使是很小的捐赠也深表感谢。 😌 
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
  <sub> 感谢您对项目的关注和支持 💙 </sub>
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
    <summary>⚙️ 展开内容</summary>

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
    <summary>⚙️ 展开内容</summary>

我们的平台提供对多种架构和设备的兼容性，以满足不同计算环境的需求。以下是主要支持的架构：

- **amd64:** 这种常见架构是个人电脑和服务器的标准，支持大多数现代操作系统的无缝运行。

- **x86 / i386:** 广泛用于台式机和笔记本电脑，支持众多操作系统和应用程序，包括 `Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 针对现代移动和嵌入式设备设计，例如智能手机和平板电脑。实例设备包括 `Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`，`Orange Pi 3 LTS` 等。

- **armv7 / arm / arm32:** 为较旧的移动和嵌入式设备设计。还广泛应用于诸如 `Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2` 等设备。

- **armv6 / arm / arm32:** 面向非常旧的嵌入式设备。虽然较少见，但仍用于某些设备，比如 `Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 较旧的架构，主要与早期嵌入式系统相关。如今已较为稀少，但可能用于一些旧设备，如早期版本的 `Raspberry Pi` 和部分旧型号智能手机。

- **s390x:** 该架构通常用于 `IBM` 主机，为企业工作负载提供高性能和可靠性。

</details> 




## 📊 支持的语言

<details> 
    <summary>⚙️ 展开内容</summary>

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
    <summary>⚙️ 展开内容</summary>

- 系统状态监控
- 所有入站连接和客户端的搜索
- 主题：`深色模式/浅色模式`
- 支持多用户和多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持本地 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计，流量限制，过期时间限制
- 自定义 `Xray` 配置模板
- 通过 `HTTPS（自定义域名 + SSL证书）`支持访问面板
- 支持一键申请 `SSL证书` 并自动续订
- 更高级的配置选项请参考面板
- 已修复的 `API路径`（用户配置通过 `API` 创建）
- 支持通过面板对不同参数的配置进行修改
- 支持通过面板导入/导出数据库

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开内容 </summary>

使用此镜像风险自负。使用本镜像即表示您自动同意与其相关的许可协议条款。

作者不对镜像的准确性、完整性或适用性提供任何明示或暗示的保证。作者对因使用或无法使用镜像或相关文档导致的直接、间接、附带或特殊损失概不负责，即使已经提前告知可能发生这些损失。

使用此镜像即表示您确认并接受与其使用相关的所有风险。另外，您同意作者不对因使用本镜像而引起的任何问题或后果负责。

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
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloudflare " width="50%">
</div>

管理脚本内置了通过 `Cloudflare` 申请 `SSL证书` 的功能。通过此脚本获取证书需要以下条件：


<details> 
    <summary> ⚙️ 展开内容 </summary>

- 注册在 `Cloudflare` 的电子邮件
- Global API Key Cloudflare
- 域名需要通过 `Cloudflare` 指向（在DNS上配置）当前服务器

## 如何获取 Global API Key Cloudflare：

1. 在终端中执行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 点击链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key`（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要再次验证身份。之后会显示全局API密钥（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


在使用时，只需输入您的域名、`email` 和 `API KEY`。如下图所示：

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
3X-UI 安装
</h1>


# 1. 快速安装 3X

<details> 
    <summary> ⚙️ 展开内容 </summary>


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
    <summary> ⚙️ 展开内容 </summary>

# 📊 安装所需包

1. 更新系统
在开始安装前，确保您的系统是最新的。执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要的包

确认服务器上已安装以下必要的软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装 3X-UI 面板

要在服务器上安装面板，请执行以下脚本：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

回答 `y` 自定义端口，或选择 `n` 让脚本自动分配端口。
请勿使用默认端口 `22, 80, 8080`。推荐选择其他端口，例如 `8181`。


```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成这些步骤后，面板安装完成，可以通过浏览器访问以下路径：

```sh
http://您的服务器IP地址:端口/WebBasePath(例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在浏览器中输入此地址后，将进入登录页面，需要输入脚本提供的用户名和密码。

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

## 更新 GeoSite GeoIP

<details> 
    <summary> ⚙️ 展开内容 </summary>

打开面板选择版本更新选项

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件 `GeoSite` 和 `GeoIP`

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 


## 启用订阅功能

<details> 
    <summary> ⚙️ 展开内容 </summary>

进入 `设置` 启用订阅功能

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击  `保存` 并 `重启面板`

# X-Ray 设置

## 基本连接

进入 `X-Ray设置` -> 选择 `基本` -> 打开 `基本连接`

按照以下截图配置

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击 `保存` 并 `重启 Xray`

</details> 





## DNS 设置

<details> 
    <summary> ⚙️ 展开内容 </summary>


进入 `X-Ray设置` -> 选择 `DNS` -> 打开 `DNS`

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击创建 `DNS`，依次输入以下 `DNS地址`

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

## 现在可以开始配置第一个连接了。

进入侧边菜单 `"连接"` -> 点击 `"添加连接"`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>




<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目基于 </strong> 
  <a href="/LICENSE">Apache License</a> 
</p>

---

<h2 align="center"> 
请阅读文档 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄语</a> |
  <a href="/docs/README.en.md">英语</a> |
  <a href="/docs/README.es.md">西班牙语</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
