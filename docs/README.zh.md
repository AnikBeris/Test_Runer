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
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=星数&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
3x-ui 安装与 SSL 证书设置指南
</h1>

<h2 align="center">
> 💡 本内容适用于有一定经验的用户。
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️免责声明⚠️
</h2>

<p align="center">
  作者不对使用本项目可能产生的任何后果负责。<br>
  使用须自担风险。
</p>

<details align="center"> 
    <summary>⚠️查看完整文本⚠️</summary>
    
本项目的使用需要承担风险。

1. 使用即表示您自动同意与其相关的许可协议。

2. 作者不对本项目的准确性、完整性或适用性提供明确或隐含的保证，使用者需自行验证其适用性。 
3. 如因使用或无法使用本项目或其文档而导致任何直接、间接、附带、间接或特殊的损失，即使事先告知可能发生这样的损失，作者概不负责。

4. 使用本项目表示您确认并接受其所有风险，并同意不因使用本项目而对作者追求任何责任。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果本项目对您有帮助，欢迎为其点亮一颗星星 :star2:
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="赞助支持">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="赞助支持">
  </a>
</p>

<h4 align="center"> 
任何形式的支持与捐赠都受欢迎，感谢您的帮助 😌 
</h1>

<div align="center">

|  |  |
|-------------:|:-------------|
| **Tether USDT (BEP20)** |`0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Bitcoin (BTC)** |`1Dbwq9EP8YpF3SrLgag2EQwGASMSGLADbh`|
| **Ethereum (ERC20)** | `0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Binance Smart Chain (BEP20)** | `0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Solana (SOL)** | `yYYXsiVTzsvfvsMnBxfxSZEWTGytjAViE2ojf3hbLeF`|
| **Cloud tips** | [Cloud Tips](https://pay.cloudtips.ru/p/7249ba98) |

</div>

---

<p align="center">
  <sub> 感谢您关注并支持此项目 💙 </sub>
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

## 📊 支持的架构和设备

<details> 
    <summary>⚙️ 展开说明</summary>

我们平台支持多种架构和设备，以满足不同的计算环境需求。以下是主要支持的架构：

- **amd64:** 常用于桌面电脑和服务器，支持大多数现代操作系统。

- **x86 / i386:** 普遍使用于个人电脑和笔记本电脑，兼容多个系统如 `Windows, macOS 和 Linux`。

- **armv8 / arm64 / aarch64:** 适用于移动及嵌入式设备，例 `Raspberry Pi 4`、`Raspberry Pi Zero 2`等。

- **armv7 / arm / arm32:** 支持较老的嵌入式设备，如 `Orange Pi Zero LTS` 等。

- **armv6 / arm / arm32:** 为非常老旧的嵌入式设备设计，例 `Raspberry Pi 1`。

- **armv5 / arm / arm32:** 适配早期嵌入式系统，较少见。

- **s390x:** 通常用于 `IBM` 主机，适合高性能企业负载。

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

## 📊 功能与特性

<details> 
    <summary>⚙️ 展开说明</summary>

- 系统状态监控
- 查看所有连接及客户列表
- 主题支持：`暗/亮模式`
- 支持多用户与多协议
- 支持的协议包括：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持 XTLS 原生协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、时间过期限制
- 自定义 `Xray` 配置模板
- 支持 `HTTPS (独立域名 + SSL证书)` 访问界面
- 支持一键申请与自动续订 `SSL证书`
- 更多高级配置可在面板中设置
- 修复的 `API 路由` (用户设置可通过 `API` 创建)
- 允许导入/导出数据库

</details> 

<h1 align="center"> 
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开说明 </summary>

本项目的使用需要自行承担风险，所有责任与风险由使用者自行承担。

使用即表示您自动同意与其相关的许可协议。

作者不对本项目的准确性、完整性或适用性提供明确或隐含的保证。因使用或无法使用本项目或其文档而发生的任何直接、间接、附带、间接或特殊损失，作者概不负责，敬请慎用。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 返回顶部 </a> 
</h2>

<h1 align="center"> 
Cloudflare SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt="Cloudflare" width="50%">
</div>

管理脚本内置了通过 `Cloudflare` 申请 `SSL证书` 的功能。要使用此功能，请确保以下准备：

<details> 
    <summary> ⚙️ 展开说明 </summary>

- 使用 `Cloudflare` 注册的电子邮箱账户
- Cloudflare 的全球 API 密钥
- 需通过 `Cloudflare` 将域名指向当前服务器

## 如何获取 Cloudflare 全球 API 密钥：

1. 在终端输入命令 `x-ui`，选择 `Cloudflare SSL Certificate`。

2. 访问以下链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key`（参考下图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt="API Key 1" width="70%">
</div>

4. 可能会要求重新验证，验证通过即可查看密钥（参考下图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt="API Key 2" width="70%">
</div>

接着输入您的域名、注册邮箱及 `API KEY`。示例如下：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt="Detail Enter" width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h2 align="center">
  <a href="#-目录">⬆️ 返回顶部 </a> 
</h2>

<h1 align="center"> 
安装 3X-UI
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

# 2. 分步安装 3X

<details> 
    <summary> ⚙️ 展开说明 </summary>

# 📊 安装必要软件包

1. 系统更新
在开始安装前，请先更新系统。执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要软件包

确保您已安装以下所需软件：

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## 安装 3X-UI 面板

通过以下命令启动安装脚本：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会询问：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

回答 `y` 以自定义端口，或选择 `n` 让脚本自动分配端口。

不建议使用常见端口（如 `22, 80, 8080`），推荐设置其他端口如 `8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成上述步骤后，面板安装成功，您可以通过以下地址在浏览器中打开面板登录页面：

```sh
http://<您的服务器IP地址>:端口/<WebBasePath>(例如：http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在面板登录页面输入上面显示的用户名和密码登录。

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

## 更新 GeoSite 和 GeoIP

<details> 
    <summary> ⚙️ 展开说明 </summary>

打开版本选择及更新面板：

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件 `GeoSite` 和 `GeoIP`：

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## 开启订阅功能

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入 `设置`，开启订阅选项：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击 `保存` 并重新启动面板。

### 配置 X-Ray 设置

## 基础连接

进入 `X-Ray 设置`，选择 `基础连接` 并设置为下图所示：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击 `保存` 并重启 XRay。

</details> 

## 配置 DNS

<details> 
    <summary> ⚙️ 展开说明 </summary>

进入 `X-Ray 设置`，选择 `DNS`：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建 DNS` 并依次添加以下 DNS 地址：

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

完成后点击 `保存` 并重启 XRay。

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
配置初始连接
</h1>

## 现在可以创建第一个连接。

进入菜单 `连接`，点击按钮 `添加连接`：

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 📜 许可协议 </h1>
<p align="center">
  <strong> 本项目基于 </strong> 
  <a href="/LICENSE">Apache 协议</a> 
</p>

---

<h2 align="center"> 
查看文档获取更多信息 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄文</a> |
  <a href="/docs/README.en.md">英文</a> |
  <a href="/docs/README.es.md">西班牙文</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
