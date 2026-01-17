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
    <img alt="项目标志" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=明星&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
3x-ui安装和配置指南 + SSL证书
</h1>

<h2 align="center">
> 💡 本文面向高级用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用该项目可能引发的任何后果负责。<br>
  请根据您自身风险承担能力使用。
</p>

<details align="center"> 
    <summary>⚠️全文⚠️</summary>
    
使用此镜像需自担风险。

1. 使用此镜像即表明您自动同意其相关的协议条款。

2. 作者对该镜像的准确性、完整性或适用性（无论明示或暗示）不作任何担保。 
3. 因使用或无法使用此镜像或其随附文档而造成的任何损失，包括但不限于直接、间接、附带性或特殊损失，即便已预先告知可能性，作者均不承担任何责任。

4. 使用该镜像表示您认可并自行承担所有使用风险，并同意作者不对使用所产生的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果这个项目对您有用，您可以点亮一个小星星来支持我们吧。:star2: 
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="买杯咖啡支持我">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="买杯咖啡支持我">
  </a>
</p>



<h4 align="center"> 
如果您能贡献一份支持（无论多少），我们表示衷心感谢。😌 
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

- [介绍](#-介绍)




## 🔗 实用链接

  







* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



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

我们的平台为广泛的架构和设备提供支持，以确保在各种计算环境中的灵活性。以下是我们支持的主要架构：

- **amd64:** 这是个人电脑及服务器的标准架构，支持大多数现代操作系统。

- **x86 / i386:** 广泛用于台式电脑和笔记本。该架构支持多种操作系统和应用，例如 `Windows, macOS 以及 Linux` 等。

- **armv8 / arm64 / aarch64:** 面向现代移动设备与嵌入式设备，如智能手机和平板。支持的设备示例：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS` 等。

- **armv7 / arm / arm32:** 多为旧款移动和嵌入式设备的架构，也广泛使用于`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 适配更老的嵌入式设备，应用较少但仍可用于如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`等。

- **armv5 / arm / arm32:** 更老旧的架构，主要面向早期嵌入式系统，现在较少使用，仅用于旧式设备如早期版的 `Raspberry Pi` 及部分老旧手机。

- **s390x:** 该架构常用于 `IBM`主机，支持企业级任务的高性能与可靠性。

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

- 系统状态监控
- 检索所有入站连接与客户端
- 主题设置：`黑暗模式 / 明亮模式`
- 多用户与多协议支持
- 支持协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生XTLS协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、到期时间限制
- 可自定义 `Xray` 配置模板
- 支持通过 `HTTPS（自定义域名 + SSL证书）`访问面板
- 支持一键申请`SSL证书`并自动续订
- 更高级的配置选项可在面板中查看
- 固定的 `API 路径`(`用户的设置通过API创建`)
- 面板中支持多种参数配置的修改
- 支持数据库的导入/导出功能

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开描述 </summary>

使用此镜像需自担风险。使用即表明您同意其相关的协议条款。

作者对于该镜像的正确性、完整性或适用性（无论明示或者暗示）不作任何保证。因使用或无法使用该镜像或其相关文档而造成的任何损失，包括但不限于直接损失、间接损失、附带性损失或其他特殊损失，即便是预先得知损失可能性的情况下，作者概不负责。

使用该镜像表示您认可自行面对使用的所有风险，且默认同意因其使用而导致的任何问题或后果无需由作者负责。

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-目录">⬆️ 回到顶部</a> 
</h2>



   
<h1 align="center"> 
Cloudflare的SSL证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包含通过 `Cloudflare` 请求 `SSL证书` 的内置功能。您需要满足以下条件才能使用此脚本获取证书：


<details> 
    <summary> ⚙️ 展开描述 </summary>

- 已注册在 `Cloudflare` 的电子邮箱
- Global API Key Cloudflare
- 域名必须通过 `Cloudflare` 定向（设置到DNS中）至当前服务器



## 如何获取Cloudflare的Global API Key：

1. 在终端输入命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 打开链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击 `View Global API Key`（参考截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 系统可能需要再次进行身份验证。完成后，将显示密钥（参考截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


在使用过程中，只需输入您的域名，`email` 和 `API KEY`。以下图示为例：

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


# 1. 快速安装3X

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

# 2. 分步安装3X


<details> 
    <summary> ⚙️ 展开描述 </summary>

# 📊 安装必需的包

1. 更新系统
安装之前，请确保您的系统已经更新。使用以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要的软件包

确认您的服务器上已安装下列软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装 3X-UI 面板

在服务器上运行如下命令以安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中脚本会提示：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

选择 `y` 手动设置端口，或选择 `n` 让脚本自动分配端口。
请勿使用默认的 `22, 80, 8080` 端口。建议使用其他如 `8181` 的端口。


```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成上述步骤后，即可完成面板的安装，并通过浏览器访问。

```sh
http://您的服务器IP地址:端口/WebBasePath(示例: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在浏览器访问地址时，您将看到登录面板的页面，输入脚本生成的用户名和密码即可。

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
    <summary> ⚙️ 展开描述 </summary>

打开“版本和更新”面板。

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新 `GeoSite` 和 `GeoIP` 数据文件。

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 


## 启用订阅功能

<details> 
    <summary> ⚙️ 展开描述 </summary>

进入 `设置` 并启用订阅。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后点击 `保存` 并重新启动面板。

# X-Ray 设置

## 基础连接设置

进入 `X-Ray 设置` -> 选择 `基本设置` -> 打开 `基础连接` 子项。

根据图片设置所有选项。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击`保存`并重新启动Xray。

</details> 





## DNS

<details> 
    <summary> ⚙️ 展开描述 </summary>


进入 `X-Ray 设置` -> 选择 `DNS` -> 打开 `DNS` 子项。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建 DNS`，依次填写下列 `DNS 地址`：

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

完成后点击 `保存`并重新启动Xray。

</details> 






<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
设置首个连接
</h1>

## 现在可以进行第一个连接的设置。

在侧边菜单中打开 `"连接"` -> 点击 `"添加连接"` 按钮。

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>




<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目受 </strong> 
  <a href="/LICENSE">Apache License</a> 
</p>

---

<h2 align="center"> 
请务必阅读文档。 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄文</a> |
  <a href="/docs/README.en.md">英文</a> |
  <a href="/docs/README.es.md">西班牙文</a> |
  <a href="/docs/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>
