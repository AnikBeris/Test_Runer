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
3x-ui安装与配置指南 + SSL证书
</h1>

<h2 align="center">
> 💡 本文面向有一定基础的用户阅读。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用本项目可能导致的任何后果负责。<br>
  使用请自负风险。
</p>

<details align="center"> 
    <summary>⚠️查看完整免责声明⚠️</summary>
    
使用本项目需自负风险。

1. 使用本项目，即表示您自动同意与之相关的许可协议条款。

2. 作者不提供关于该项目的准确性、完整性或适用性的任何明示或暗示保证。
3. 作者对因使用或无法使用本项目或其相关文档所导致的任何损失，包括但不限于直接、间接、偶然、间接或特殊损失不承担责任，即使用户已被明确告知这种损失的可能性。

4. 使用本项目即表示您确认并愿意承担与之相关的所有风险。此外，您同意作者不对因使用本项目而引起的任何问题或后果承担责任。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果您觉得这个项目对您有所帮助，请为它点赞并加星以示支持。:star2: 
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
任何金额的捐赠都表示热烈欢迎，真心感谢。😌 
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

## 📊 支持的架构及设备

<details> 
    <summary>⚙️ 展开详情</summary>

我们的平台支持各种架构和设备，能够适应多种计算场景。以下是主要支持的架构列表：

- **amd64:** 标准的个人电脑及服务器架构，广泛支持现代操作系统。

- **x86 / i386:** 广泛用于台式电脑和笔记本，支持诸多操作系统和应用程序，包括`Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 用于现代移动和嵌入式设备，如智能手机和平板电脑。支持设备示例：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`，`Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 支持较旧的移动和嵌入设备，如`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等。

- **armv6 / arm / arm32:** 针对更旧的嵌入设备，应用于如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 较旧的架构，与早期嵌入式系统相关。 现较为罕见，但在如早期`Raspberry Pi`版本及一些旧款手机中有应用。

- **s390x:** 多用于IBM大型主机，为企业任务提供高效性能及可靠性。

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
- 印尼语
- 乌克兰语
- 土耳其语
- 葡萄牙语（巴西）

</details> 

## 📊 功能及特性

<details> 
    <summary>⚙️ 展开详情</summary>

- 系统状态监控
- 对所有入站连接和客户端的搜索
- 支持`深色/浅色`主题
- 多用户及多协议支持
- 支持以下协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 原生支持XTLS协议：`RPRX-Direct, Vision, REALITY`
- 数据流量统计、流量限制、过期时间限制
- `Xray`可配置模板
- 支持通过`HTTPS`访问面板（自定义域名+SSL证书）
- 支持一键申请`SSL证书`及其自动续期
- 更多高级配置参数详见面板
- 修复的`API路由`（通过`API`创建用户配置）
- 支持通过面板调整不同参数的配置
- 数据库的导入/导出支持

</details> 

<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开详情 </summary>

使用本项目需自负风险。使用本项目即表示您自动同意与之相关的许可协议条款。

作者不对本项目的准确性、完整性或适用性提供任何明示或暗示的保证。不论是否已被明确告知可能的损失，因使用或无法使用本项目或其文档而导致的损失，包括但不限于直接、间接、偶然、间接或特殊损失，作者都概不负责。

使用本项目即表示您确认并愿意承担相关风险。此外，您同意作者不对因使用本项目而引发的任何问题或后果承担责任。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 返回顶部</a> 
</h2>

<h1 align="center"> 
SSL证书 Cloudflare
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包含通过`Cloudflare`申请`SSL证书`的内置功能。使用此脚本申请证书需要以下条件：

<details> 
    <summary> ⚙️ 展开描述 </summary>

- 注册在`Cloudflare`的邮箱
- Cloudflare 的 Global API Key
- 域名需通过`Cloudflare`解析到当前服务器

## 如何获取 Cloudflare 的 Global API Key:

1. 在终端执行命令`x-ui`，然后选择`Cloudflare SSL Certificate`。
2. 点击链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)
3. 点击`View Global API Key`（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要进行再次身份验证，之后将显示API密钥（如下图所示）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

在使用时，只需输入您的域名、`email`和`API KEY`即可。以下为示例：

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
安装 3X-UI
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

# 📊 安装必要包

1. 更新系统
在开始安装前，确保您的系统是最新的。执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要的软件包

确保您的服务器已安装以下必要软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 面板

在服务器上运行以下命令即可安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会提问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择`y`可手动设置端口，或选择`n`则脚本会自动分配端口。
建议不要使用常用端口号，例如`22, 80, 8080`，推荐选择其他端口，比如`8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成此过程后，面板安装将完成，您可以通过以下路径在浏览器中访问面板：

```sh
http://你的服务器IP地址:端口/WebBasePath (例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

进入面板登录页面后，输入脚本中提供的用户登录名与密码。

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
    <summary> ⚙️ 展开描述 </summary>

打开版本和更新选择选项卡：

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新 `GeoSite` 和 `GeoIP` 数据文件。

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 启用订阅

<details> 
    <summary> ⚙️ 展开描述 </summary>

点击`设置`并启用订阅。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后记得点击`保存`并`重启面板`。

# 设置 X-Ray

## 基本连接

点击`X-Ray设置` -> 选择`常规` -> 展开`基本连接`。

将选项设置如图所示：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击`保存`并`重启Xray`。

</details> 

## DNS

<details> 
    <summary> ⚙️ 展开描述 </summary>

点击`X-Ray设置` -> 选择`DNS`。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击`创建DNS`后分别输入以下`DNS地址`：

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
配置首个连接
</h1>

## 现在可以开始配置第一个连接。

在侧边栏菜单中点击`"连接"` -> 点击`"添加连接"`。

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 协议 </h1>
<p align="center">
  <strong> 该项目基于 </strong> 
  <a href="/LICENSE">Apache协议</a> 
</p>

---

<h2 align="center"> 
建议查看完整文档进行了解
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄语</a> |
  <a href="/docs/README.en.md">英语</a> |
  <a href="/docs/README.es.md">西班牙语</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
