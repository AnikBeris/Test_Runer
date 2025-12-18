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
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
3x-ui 安装与配置指南 + SSL证书
</h1>

<h2 align="center">
> 💡 本文档面向有一定经验的用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用本项目可能产生的任何后果负责。<br>
  请自行承担风险。
</p>

<details align="center"> 
    <summary>⚠️完整内容⚠️</summary>
    
使用本项目需自行承担风险。

1. 使用过程中，您将视为自动同意与本项目相关的许可协议条款。

2. 对于本项目的准确性、完整性或适用性，作者不提供任何明示或暗示的保证。 
3. 作者对因使用或无法使用本项目或其相关文档所造成的任何直接、间接、附带、特殊或衍生损失不承担任何责任，即使事先被告知可能会发生此类损失。

4. 使用本项目时，您需确认并接受相关风险。此外，您同意作者不对因使用本项目而产生的任何问题或后果负任何责任。

</details> 

---

<h3 align="center"> 
💖 支持此项目 
</h3>

<p align="center"> 
如果此项目对您有帮助，欢迎给个星标:star2: 
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="赞助我一杯咖啡">
  </a>
</p>



<h4 align="center"> 
无论捐款微薄与否，我们都深表感激，谢谢您的支持。😌 
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
  <sub> 感谢您关注和支持本项目 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



## 📚 目录

- [简介](#-简介)




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

我们的平台与多种计算架构和设备兼容，提供了多样化环境的灵活支持。支持的主要架构如下：

- **amd64:** 这是个人计算机和服务器的通用架构，与大多数现代操作系统兼容。

- **x86 / i386:** 广泛应用于台式电脑和笔记本，支持多个操作系统和软件，包括`Windows, macOS, Linux`。

- **armv8 / arm64 / aarch64:** 为现代移动和嵌入式设备设计，如智能手机和平板电脑。设备示例：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 面向较老的移动和嵌入式设备，广泛应用于`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 针对非常老旧的嵌入式设备，典型设备如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 较老的体系结构，主要与早期嵌入系统相关，现已较少见，可能出现在老旧设备中。

- **s390x:** 通常用于`IBM`大型机，为企业工作负载提供高性能和可靠性。

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




## 📊 功能特点

<details> 
    <summary>⚙️ 展开详情</summary>

- 系统状态监测
- 搜索所有入站连接及客户端
- 主题支持：`深色/浅色`
- 支持多用户与多协议
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生XTLS协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、过期时间限制
- 自定义`Xray`配置模板
- 支持基于`HTTPS`的面板访问（自定义域名+SSL证书）
- 支持一键申请`SSL证书`并自动续期
- 更多高级配置项详见面板
- 固定`API路径`（通过`API`创建用户设置）
- 支持通过面板更改配置的各类参数
- 支持数据库的导出/导入功能

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开详情 </summary>

使用本项目需自行承担风险。使用过程中，您将视为自动同意与其相关的许可协议。

作者不对本项目的准确性、完整性或适用性提供任何明示或暗示的保证。对因使用本项目或其文档所造成的任何直接、间接、附带、特殊或衍生损失，作者不承担责任，即使事先被告知可能会发生该类损失。

使用本项目时，您需确认并接受相关风险。此外，您同意作者不对因使用本项目而产生的任何问题或后果负责。

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

管理脚本包含通过`Cloudflare`申请`SSL证书`的内置功能。如果您希望通过此脚本申请证书，请确保已完成以下准备工作：


<details> 
    <summary> ⚙️ 展开详情 </summary>

- 注册在`Cloudflare`的电子邮箱
- Cloudflare的Global API Key
- 域名需通过`Cloudflare`的DNS指向当前服务器



## 如何获取Cloudflare Global API Key：

1. 在终端中执行命令`x-ui`，然后选择`Cloudflare SSL Certificate`。

2. 访问[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`（参见下图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要再次验证身份，完成后将显示API Key（示例如下）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


使用时只需输入您的域名、`email`和`API KEY`。示例如下：

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


# 1. 3X快速安装

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

# 📊 安装必要的包

1. 更新系统
安装之前，请确保系统已更新，执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要软件包

确保服务器上已安装必要的软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装3X-UI面板

要安装面板，请运行以下命令：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

输入`y`自行设置端口，或输入`n`让脚本自动分配。
请勿使用默认端口`22, 80, 8080`，建议选择其他端口，例如`8181`。


```sh
用户名: 3favnjd8

密码: Msdf823Ll

端口: 40608

路径: vpkPI6ex9ajesDX

访问链接: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成以上操作后，面板安装完成，可以通过以下地址访问面板：

```sh
http://您的服务器IP地址:端口/路径 (例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在浏览器输入上述地址后，将进入面板登录窗口，输入脚本生成的用户名和密码即可登录。

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
    <summary> ⚙️ 展开详情 </summary>

打开版本与更新选择面板

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件`GeoSite`与`GeoIP`

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

完成后点击`保存`并`重启面板`

# 配置 X-Ray 设置

## 基础连接

进入`X-Ray设置` -> 选择`基本设置` -> 找到`基础连接`

按照下图配置

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击`保存`并`重启Xray`

</details> 





## 配置DNS

<details> 
    <summary> ⚙️ 展开详情 </summary>


进入`X-Ray设置` -> 选择`DNS` -> 找到`DNS`

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击`创建DNS`，依次添加以下`DNS地址`

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

完成后点击`保存`并`重启Xray`

</details> 






<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
配置首个连接
</h1>

## 现在您可以开始配置第一个连接。

在侧边菜单中进入`“连接”` -> 点击`“添加连接”`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>




<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h1 align="center"> 📜 许可协议 </h1>
<p align="center">
  <strong> 本项目依据 </strong> 
  <a href="/LICENSE">Apache License</a> 分发。
</p>

---

<h2 align="center"> 
文档请参阅 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄语</a> |
  <a href="/docs/README.en.md">英语</a> |
  <a href="/docs/README.es.md">西班牙语</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
