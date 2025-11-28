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
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Stars&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
3x-ui + SSL 证书的安装和配置指南
</h1>

<h2 align="center">
> 💡 本材料面向有经验的用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对使用本项目可能产生的任何后果不承担任何责任。<br>
  使用本项目需自担风险。
</p>

<details align="center"> 
    <summary>⚠️全文⚠️</summary>
    
使用本镜像需自担风险。

1. 使用本镜像即表示您自动同意其相关许可协议的条款。

2. 作者不对本镜像的准确性、完整性或适合性的任何特定用途提供任何明示或暗示的担保。 
3. 不论是否已经事先告知可能的风险，作者对因使用或无法使用本镜像或相关文档而导致的任何直接、间接、附带、衍生或特殊损失不承担任何责任。

4. 使用本镜像即表示您确认并自担其使用风险。同时，您同意作者不对因使用镜像而导致的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持本项目 
</h3>

<p align="center"> 
如果这个项目对您有帮助，请为其点亮小星星.:star2: 
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
即使是很小的捐赠亦受热烈欢迎，感激不尽。😌 
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
  <sub> 感谢您关注和支持本项目 💙 </sub>
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
  <a href="#-目录"> ⬆️ 返回顶部 </a> 
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



## 📊 支持的架构和设备

<details> 
    <summary>⚙️ 展开描述</summary>

我们的平台提供对各种架构和设备的兼容性，确保能在广泛的计算环境中灵活使用。以下是主要支持的架构列表：

- **amd64:** 这种流行的架构是个人电脑和服务器的标准，支持当今大多数现代操作系统顺畅运行。

- **x86 / i386:** 广泛用于台式机和笔记本电脑。这种架构得到了众多操作系统和应用程序支持，例如`Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 设计用于现代移动和嵌入式设备，如智能手机和平板电脑。实例设备包括：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 用作较旧的移动和嵌入式设备的架构。仍广泛用于`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 针对非常老的嵌入式设备的架构。尽管较少见，仍用于诸如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`等设备。

- **armv5 / arm / arm32:** 较老架构，多用于早期嵌入系统。尽管今天已经不常见，但在早期一些`Raspberry Pi`版本和一些老旧的智能手机中可能仍然找到。

- **s390x:** 这种架构通常用于`IBM`的大型主机（Mainframe），为企业负载提供高性能和可靠性。

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




## 📊 功能 || 特性

<details> 
    <summary>⚙️ 展开描述</summary>

- 系统健康状态监控
- 搜索所有入站连接和客户
- 主题：`深色 / 浅色`
- 多用户及多协议支持
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、有效期限制
- 可自定义的`Xray`配置模板
- 支持通过`HTTPS(自定义域名+SSL证书)`访问面板
- 支持单键申请`SSL证书`及其自动续期
- 更多高级配置选项详见面板
- 修复的`API路由`(通过`API`创建用户设置)
- 支持通过面板根据不同参数更改配置
- 支持面板数据库的导出/导入功能

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开描述 </summary>

使用本镜像需自担风险。使用即表示您自动同意其相关许可协议的条款。

作者不对本镜像的准确性、完整性或适用性的任何特定用途提供任何明示或暗示的担保。作者对因使用或无法使用本镜像或相关文档而导致的任何直接、间接、附带、衍生或特殊损失不承担任何责任，即便事前已告知可能的风险。

使用本镜像即表示您确认并自担其使用风险。同时，您同意作者不对因使用镜像而导致的任何问题或后果负责。

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-目录">⬆️ 返回顶部</a> 
</h2>


<h1 align="center"> 
Cloudflare SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包含通过 `Cloudflare` 申请 `SSL证书` 的功能。要通过该脚本获取证书，您需要：


<details> 
    <summary> ⚙️ 展开描述 </summary>

- 一个在 `Cloudflare` 注册过的电子邮件地址
- Cloudflare Global API Key
- 域名应通过 `Cloudflare` 指向当前服务器 (DNS 配置)

## 如何获取 Cloudflare Global API Key:

1. 在终端中执行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 访问以下链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key` (见下方截图)：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 您可能需要再次进行身份验证，验证后将显示密钥 (见下方截图)：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


使用时，只需输入您的域名、`email` 和 `API Key`。示例如下：

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

# 2. 分步骤安装 3X


<details> 
    <summary> ⚙️ 展开描述 </summary>

# 📊 安装必要的包

1. 更新系统
安装前先确保系统已更新，执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要的包

确保在您的服务器上已安装以下所需包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装 3X-UI 面板

在服务器上运行如下脚本即可安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中，脚本会问您：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

若您希望自行设定端口，回答 `y`；否则回答 `n`，脚本将自动分配一个随机端口。
不要选择标准端口 `22, 80, 8080`。推荐选择其他端口，例如 `8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成以上步骤后，安装面板即完成，您可以通过如下路径使用浏览器访问面板：

```sh
http://您的服务器IP地址:端口/WebBasePath (例: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

输入地址后，您将跳转到面板登录页面。在登录窗口输入脚本提供的用户名和密码即可。

<div align="center">
  <img src="../media/Tutorial/Article_3/Login.png" alt="Login" width="70%">
</div>

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
基本设置
</h1>

## 更新 GeoSite 与 GeoIP

<details> 
    <summary> ⚙️ 展开描述 </summary>

打开版本和更新选择面板

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新 `GeoSite` 与 `GeoIP` 数据文件

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 


## 启用订阅

<details> 
    <summary> ⚙️ 展开描述 </summary>

进入 `设置`，启用订阅功能

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击 `保存` 及 `重启面板`

# X-Ray 设置

## 基本连接

进入 `X-Ray 设置` -> 选择 `常规` -> 打开小节 `基础连接`

按下图设置

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击 `保存` 及 `重启 Xray`

</details> 





## DNS

<details> 
    <summary> ⚙️ 展开描述 </summary>


进入 `X-Ray 设置` -> 选择 `DNS` -> 打开小节 `DNS`

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建 DNS`，依次添加以下 `DNS 地址`

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

完成后点击 `保存` 及 `重启 Xray`

</details> 






<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
首次连接配置
</h1>

## 现在您可以操作首次连接配置。

进入侧边菜单的 `"连接"` -> 点击 `"添加连接"`

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
文档请参考 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄语</a> |
  <a href="/docs/README.en.md">英语</a> |
  <a href="/docs/README.es.md">西班牙语</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
