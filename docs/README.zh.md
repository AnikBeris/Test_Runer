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
安装与配置 3x-ui + SSL 证书指南
</h1>

<h2 align="center">
> 💡 本文适用于有技术基础的用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对使用本项目可能产生的任何后果概不负责。<br>
  使用需自行承担风险。
</p>

<details align="center"> 
    <summary>⚠️完整声明⚠️</summary>
    
使用该镜像时需自行承担风险。

1. 使用时，您自动同意与之相关的许可协议条款。

2. 作者不对该镜像的准确性、完整性或特定用途适用性作任何明示或暗示的保证。
3. 作者不对因此镜像或其相关文档的使用或无法使用引起的任何损失负责。包括但不限于直接、间接、附带、衍生或特殊损失，即使事先已被告知可能性。

4. 使用该镜像即表示您承认并接受所有相关的使用风险。此外，您同意作者不对使用该镜像可能产生的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持本项目 
</h3>

<p align="center"> 
如果您觉得本项目对您有用，可以点亮小星星支持我们 :star2: 
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
我们非常欢迎任何金额的捐款，非常感谢您的支持！😌 
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
  <a href="#-目录"> ⬆️ 回到顶部 </a> 
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

本平台支持多种架构和设备，以便在不同的计算环境中实现灵活性。以下列出了支持的主要架构：

- **amd64:** 普通桌面电脑和服务器标准架构，兼容现代操作系统。

- **x86 / i386:** 常见于桌面电脑和笔记本电脑。支持众多操作系统和应用，包括`Windows`, `macOS`和`Linux`。

- **armv8 / arm64 / aarch64:** 主要针对现代移动设备与嵌入式设备，如智能手机与平板电脑。例如：`树莓派 4`, `树莓派 3`, `橙子派 3 LTS`等。

- **armv7 / arm / arm32:** 适用于较早前的移动与嵌入式设备，适配于`橙子派 Zero LTS`, `橙子派 PC Plus`, `树莓派 2`等。

- **armv6 / arm / arm32:** 针对非常早期的嵌入式设备，例如`树莓派 1`, `树莓派 Zero/Zero W`。

- **armv5 / arm / arm32:** 用于更古老的一些嵌入式系统，现在使用较少，但仍可能支持某些旧设备。

- **s390x:** 大型机`s390x`提供高性能和高可靠性，广泛应用于企业级任务。

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
- 搜索所有入站连接和客户端
- 主题模式：`暗黑/明亮`
- 支持多用户和多协议
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生的 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制及过期时间控制
- 配置模式定制 `Xray`
- 面板 HTTPS 支持：`自定义域名 + SSL 证书`
- 支持一键申请 `SSL证书` 并自动续期
- 更高级的配置选项详见面板
- 修复的 `API 路由`（通过 `API` 创建用户设置）
- 支持面板中的多参配置修改
- 数据库的导入/导出支持

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开详情 </summary>

使用该镜像时需自行承担风险。使用即视为同意其相关的许可协议条款。

作者不对该镜像的准确性、完整性或特定用途适用性作任何明示或暗示的保证。作者不对因此镜像或其相关文件使用或无法使用引起的任何直接、间接、附带、衍生或特殊损失负责，即使事先已被告知可能性。

使用该镜像即表示您承认并接受所有相关的使用风险。此外，您同意作者不对使用该镜像可能产生的任何问题或后果负责。

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-目录">⬆️ 回到顶部</a> 
</h2>



   
<h1 align="center"> 
配置 Cloudflare 的 SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包括通过 `Cloudflare` 请求 `SSL证书` 的内置功能。您需要具备以下条件：


<details> 
    <summary> ⚙️ 展开详情 </summary>

- 注册在 `Cloudflare` 的电子邮件地址
- Cloudflare 的 Global API Key
- 必须通过 `Cloudflare` 将域名 DNS 指向当前服务器



## 如何获取 Cloudflare 的 Global API Key：

1. 在终端中运行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 点击链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key`（参见下方截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新验证身份，以查看 API Key。例如：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


在使用过程中输入您的域名、电子邮件和 API Key 。示例如下：

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
安装 3X-UI
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

# 📊 安装必要包

1. 更新系统
安装开始前，请确认您的系统已更新。运行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要依赖包

确保您的操作环境已装好所需依赖：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装 3X-UI 面板

在服务器上运行以下命令安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择 `y` 以手动设置端口，或选择 `n` 由脚本随机生成。
请勿使用常见端口如 `22, 80, 8080`，建议选择如 `8181` 等其他端口。


```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

至此，安装完成，可以通过以下路径访问面板：

```sh
http://您的服务器IP:端口/WebBasePath（如：http://192.168.0.10:40608/vpkPI6ex9ajesDX）
```

在浏览器中输入该地址即可进入登录页面，使用脚本提供的用户名和密码登录。

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

## 更新 GeoSite GeoIP 数据

<details> 
    <summary> ⚙️ 展开详情 </summary>

打开版本与更新选项

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
    <summary> ⚙️ 展开详情 </summary>

进入 `设置` 并启用订阅功能：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击 `保存` 并选择 `重启面板`

# X-Ray 配置

## 基础连接

进入 `X-Ray 设置` -> 选择 `常规` -> 打开子选项 `基础连接`

按如下设置，确保正确：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击 `保存` 并选择 `重启 X-Ray`

</details> 





## DNS 设置

<details> 
    <summary> ⚙️ 展开详情 </summary>


进入 `X-Ray 设置` -> 选择 `DNS` -> 打开子选项 `DNS`

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建 DNS` 然后逐个添加 `DNS地址`

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

完成后点击 `保存` 并选择 `重启 X-Ray`

</details> 






<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
设置第一个连接
</h1>

## 现在可以设置第一个连接了。

在左侧菜单中进入 `"连接"` -> 点击 `"新增连接"`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>




<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h1 align="center"> 📜 许可协议 </h1>
<p align="center">
  <strong> 本项目采用 </strong> 
  <a href="/LICENSE">Apache License</a> 
</p>

---

<h2 align="center"> 
文档信息，请查阅 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
