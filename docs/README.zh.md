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
> 💡 本文面向有经验的用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对使用本项目可能导致的任何后果不承担责任。<br>
  一切后果由用户自行承担。
</p>

<details align="center"> 
    <summary>⚠️完整免责声明⚠️</summary>
    
使用本项目时，您需自担风险。

1. 使用本项目即表示您已自动同意相关许可协议的条款。

2. 作者对本项目的准确性、完整性或适用性不作任何明示或暗示的保证。 

3. 作者对由于使用或无法使用本项目或其文档所引发的任何损失（包括直接、间接、附带、特殊损失等）不负责任，即使事先已获知可能存在此类损失。

4. 使用本项目即表示您同意承担其带来的所有风险，并同意作者对因使用本项目而产生的任何问题或后果不负责任。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果您觉得本项目对您有所帮助，可以给它点个⭐:star2: 
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
您的每一份捐赠，无论多少，都深表感谢。 😌 
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

我们的平台与多种架构和设备兼容，适用于不同的计算环境，以下是我们支持的主要架构：

- **amd64:** 这种常见架构是个人电脑和服务器的标准，支持大多数现代操作系统。

- **x86 / i386:** 广泛应用于台式机和笔记本，支持`Windows、macOS和Linux`等多种操作系统和应用。

- **armv8 / arm64 / aarch64:** 适用于现代移动设备和嵌入式设备，例如`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 用于早期的移动设备和嵌入式设备，仍然广泛用于`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 面向非常老旧的嵌入式设备，例如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 更早期的架构，主要在早期嵌入式系统中使用，现较为少见。

- **s390x:** 用于`IBM`大型机，提供企业级高性能和可靠性。

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




## 📊 功能 || 特性

<details> 
    <summary>⚙️ 展开详情</summary>

- 系统状态监控
- 所有入站连接和客户端的搜索
- 主题：`深色模式/浅色模式`
- 支持多用户和多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生XTLS协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、过期时间控制
- 可自定义`Xray`配置模板
- 支持通过`HTTPS`访问面板（自定义域名+SSL证书）
- 支持一键申请`SSL证书`和自动续订
- 更多高级配置参数请查看控制面板
- 改良的`API路由`（用户设置通过`API`创建）
- 支持面板中根据可用参数修改配置
- 支持通过面板导出/导入数据库

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开详情 </summary>

使用本项目时，您需自担风险。使用即表示您同意相关许可协议的条款。

作者对本项目的准确性、完整性或适用性不作任何明示或暗示的保证。作者对由于使用或无法使用本项目或其文档所引发的任何损失（包括直接、间接、附带、特殊损失等）不负责任，即使事先已获知可能存在此类损失。

使用本项目即表示您同意承担其带来的所有风险，并同意作者对因使用本项目而产生的任何问题或后果不负责任。

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

管理脚本包含内置功能，可以通过`Cloudflare`申请`SSL证书`。申请证书需具备以下条件：


<details> 
    <summary> ⚙️ 展开详情 </summary>

- 注册`Cloudflare`的电子邮箱
- Cloudflare的Global API Key
- 域名需通过`Cloudflare`解析并指向当前服务器



## 如何获取Cloudflare Global API Key：

1. 在终端运行命令`x-ui`，选择`Cloudflare SSL Certificate`。

2. 打开链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`（参见下方截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新验证身份，完成后显示密钥（参见下方截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


申请时仅需输入您的域名、`email`和`API KEY`。如下实例所示：

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
3X-UI安装
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

# 2. 3X分步安装


<details> 
    <summary> ⚙️ 展开详情 </summary>

# 📊 安装所需软件包

1. 系统更新
安装前确认系统已更新，运行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要软件包

确认服务器中安装了以下软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装3X-UI面板

运行以下脚本在服务器上安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会提示问题：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

回答`y`可以自行设置端口，回答`n`则脚本会随机设置。
不要使用固定端口`22, 80, 8080`，推荐选择其它端口，例如`8181`。


```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成这些步骤后，即可通过以下URL访问面板：

```sh
http://服务器的IP地址:端口/WebBasePath(例子：http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在浏览器中打开地址后，输入脚本提供的用户名和密码即可登录面板。

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

打开版本和更新界面：

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
    <summary> ⚙️ 展开详情 </summary>

进入`设置`并启用订阅设置：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击`保存`并`重启面板`。

# X-Ray设置

## 基础连接

进入`X-Ray设置` -> 选择`一般` -> 打开子选项`基础连接`

参考如下配置：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击`保存`并`重启Xray`。

</details> 





## DNS

<details> 
    <summary> ⚙️ 展开详情 </summary>


进入`X-Ray设置` -> 选择`DNS` -> 打开子选项`DNS`

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击`创建DNS`并依次添加以下`DNS地址`：

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
连接配置
</h1>

## 现在可以开始配置第一个连接了。

在侧边菜单中选择`"连接"` -> 点击`"添加连接"`：

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
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
