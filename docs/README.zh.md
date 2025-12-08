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
3x-ui + SSL证书安装和配置指南
</h1>

<h2 align="center">
> 💡 本教程适合具备一定技术基础的用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用本项目可能造成的任何后果负责。<br>
  使用本项目须自行承担相应的风险。
</p>

<details align="center"> 
    <summary>⚠️完整声明⚠️</summary>
    
使用本项目时需要自行承担风险。

1. 使用该项目即表示您同意与之相关的许可协议条款。

2. 作者不对该项目及其文档的准确性、完整性或适用性作出任何明示或隐含的保证。 
3. 作者对因使用或无法使用该项目或其相关文档所导致的任何损失概不负责，包括但不限于直接、间接、附带、衍生或特殊损失，即使事先已被告知可能发生此类损失。

4. 使用本项目表明您确认并接受与其使用相关的所有风险，同时同意作者不对使用过程中产生的任何问题或后果承担责任。

</details> 

---

<h3 align="center"> 
💖 支持本项目 
</h3>

<p align="center"> 
如果您觉得本项目对您有帮助，可以为项目点上一颗星🌟。 
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
即使是再小的捐赠我们都深表感谢，衷心感谢您的支持。 😌 
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
- OpenSUSE Tubleweed
- Amazon Linux 2023
- Windows x64

</details> 



## 📊 支持的架构和设备

<details> 
    <summary>⚙️ 展开详情</summary>

我们的平台支持多种架构和设备，适用于多种计算环境。以下为主要支持的架构：

- **amd64:** 这种常见架构是个人电脑和服务器的标准，支持大多数现代操作系统。

- **x86 / i386:** 广泛应用于台式电脑和笔记本电脑。支持众多操作系统和应用，包括但不限于`Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 专为现代移动设备和嵌入式设备（如手机和平板电脑）设计。支持以下设备：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS` 等。

- **armv7 / arm / arm32:** 用于较旧的移动和嵌入式设备。如：`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2` 等。

- **armv6 / arm / arm32:** 针对非常旧的嵌入式设备。尽管较少使用，仍用于一些设备，例如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 较旧的架构，主要用于早期嵌入式系统。如早期的`Raspberry Pi`版本以及一些旧款智能手机。

- **s390x:** 通常用于`IBM`的主机，提供企业级工作负载的高性能和可靠性。

</details> 




## 📊 支持的语言

<details> 
    <summary>⚙️ 展开详情</summary>

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




## 📊 功能特点

<details> 
    <summary>⚙️ 展开详情</summary>

- 系统状态监控
- 搜索所有入站连接及客户端
- 主题支持：`深色/浅色`
- 支持多用户和多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生XTLS协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制及到期时间限制
- 可定制的`Xray`配置模板
- 支持通过`HTTPS`(自定义域名 + SSL证书)访问控制面板
- 支持一键申请`SSL证书`并自动续期
- 更多高级配置选项请参考控制面板
- 固定的`API路由`(用户设置通过`API`创建)
- 支持通过面板根据多种参数更改配置
- 支持通过面板导入/导出数据库

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开详情 </summary>

使用本项目需要自行承担风险。使用本项目即表示您同意与之相关的许可协议条款。

作者不对本项目及其相关文档的准确性、完整性及适用性作出任何明示或暗示的保证。同时，作者不对因使用或无法使用本项目所导致的任何损失负责，包括但不限于直接损失、间接损失、附带损失、衍生损失、特别损失等。

使用本项目表明您已确认并承担所有相关风险，同时明确同意作者不对因使用本项目引发的任何问题或后果承担责任。

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

管理脚本内置通过`Cloudflare`申请`SSL证书`的功能。要通过此脚本获取证书，您需要：


<details> 
    <summary> ⚙️ 展开详情 </summary>

- 注册了`Cloudflare`的邮箱
- `Cloudflare`的Global API Key
- 域名需通过`Cloudflare`的DNS解析指向当前服务器



## 如何获取Cloudflare的Global API Key:

1. 在终端中运行命令`x-ui`，选择`Cloudflare SSL Certificate`。

2. 打开链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新验证身份。之后会显示API Key（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


在使用时，只需输入您的域名，`email`和`API KEY`。如下所示：

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


# 1. 快速安装3X

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

# 2. 分步骤安装3X


<details> 
    <summary> ⚙️ 展开详情 </summary>

# 📊 安装必要包

1. 更新系统
在安装前，请确保系统已更新。执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要包

确保服务器已安装以下必要包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装3X-UI控制面板

要在服务器上安装控制面板，请运行以下脚本命令：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中会有如下提示：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

回答`y`表示自定义端口设置，回答`n`则会随机分配端口。
请勿使用常见端口`22, 80, 8080`，建议选择其他端口，例如`8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成这些步骤后，安装即告完成。您可以通过以下路径访问控制面板：

```sh
http://您的服务器IP地址:端口/WebBasePath (例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

输入地址后，会跳转至面板登录界面，在此输入您刚刚获得的用户名和密码。

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

## 更新GeoSite和GeoIP

<details> 
    <summary> ⚙️ 展开详情 </summary>

打开版本和更新选项

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新`GeoSite`和`GeoIP`数据文件

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 


## 启用订阅

<details> 
    <summary> ⚙️ 展开详情 </summary>

进入`设置`并启用订阅

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后，点击`保存`并`重启控制面板`。

# X-Ray设置

## 基本连接设置

进入`X-Ray设置`->选择`基本`->打开`基本连接`选项。

按图示设置：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后，点击`保存`并`重启Xray`。

</details> 





## DNS设置

<details> 
    <summary> ⚙️ 展开详情 </summary>


进入`X-Ray设置`->选择`DNS`->打开`DNS`选项。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击`创建DNS`，依次添加以下`DNS地址`：

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

完成后，点击`保存`并`重启Xray`。

</details> 






<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
首次连接设置
</h1>

## 现在可以进行首次连接的配置。

进入侧栏菜单，点击`"连接"` -> 点击`添加连接`。

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
请查阅文档 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
