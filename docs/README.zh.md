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
3x-ui + SSL证书的安装和配置指南
</h1>

<h2 align="center">
> 💡 本文档适用于有经验的用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对使用该项目可能导致的任何后果不承担任何责任。<br>
  后果自负。
</p>

<details align="center"> 
    <summary>⚠️完整免责声明⚠️</summary>
    
使用该镜像意味着您同意承担其使用的所有风险。

1. 使用该镜像即自动同意与之相关的许可协议中的条款。

2. 作者对该镜像的准确性、完整性或适用性没有任何明示或隐含的保证。 
3. 作者对因使用或无法使用该镜像或其附带文档而导致的任何损失（包括但不限于直接、间接、附带、特别或间接损失）不承担任何责任，即使事先已被告知这些损失的可能性。

4. 使用该镜像即表明您接受并承担所有相关风险。此外，您同意作者不对使用该镜像可能导致的任何问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果本项目对您有帮助，请为其星标评分。\:star2: 
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
无论金额多少，您的捐助都会受到欢迎。非常感谢。😌 
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
  <sub> 感谢您对该项目的关注与支持 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



## 📚 内容目录

- [简介](#-简介)




## 🔗 实用链接

  







* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
  <a href="#-内容目录"> ⬆️ 返回顶部 </a> 
</h2>

<h1 align="center"> 
技术要求
</h1>

## 📊 推荐的操作系统

<details> 
    <summary>⚙️ 查看详情</summary>

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
    <summary>⚙️ 查看详情</summary>

我们的平台支持广泛的架构和设备，能够适应多种计算环境。以下是我们支持的主要架构列表：

- **amd64:** 这种常见架构是台式机和服务器的标准选择，可以保证大多数现代操作系统的兼容性。

- **x86 / i386:** 广泛应用于桌面电脑和笔记本电脑。该架构得到包括`Windows, macOS 和 Linux`在内的众多操作系统和应用支持。

- **armv8 / arm64 / aarch64:** 适用于现代移动和嵌入式设备，如智能手机和平板电脑。示例设备：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS` 等。

- **armv7 / arm / arm32:** 面向较老的移动和嵌入式设备，仍广泛应用于如`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等设备。

- **armv6 / arm / arm32:** 针对较老的嵌入式设备，虽然不常见，但仍然适用于如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`等设备。

- **armv5 / arm / arm32:** 旧式架构，主要用于早期嵌入式系统，现在较为罕见，但可能用于某些过时设备，例如早期`Raspberry Pi`。

- **s390x:** 通常用于`IBM主机`，为企业工作负载提供高可用性和性能保障。

</details> 




## 📊 支持的语言

<details> 
    <summary>⚙️ 查看详情</summary>

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
    <summary>⚙️ 查看详情</summary>

- 系统状态监控
- 搜索所有入站连接和客户端
- 主题：`暗色模式 / 浅色模式`
- 支持多用户多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议：`RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、到期时间限制
- 可自定义`Xray`配置模板
- 支持通过`HTTPS（自定义域名+SSL证书）`访问面板
- 支持一键获取`SSL证书`及其自动续期
- 更多高级配置选项请参阅面板
- 修复的`API路由`（通过`API`创建用户设置）
- 支持在面板中根据各种参数修改配置
- 支持通过面板导入/导出数据库

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 查看详情 </summary>

使用该镜像意味着您同意承担其使用的所有风险。通过使用，您自动同意与之相关的许可协议中的条款。

作者对该镜像的准确性、完整性或适用性没有任何明示或隐含的保证。对于因使用或无法使用该镜像或其附带文件导致的任何损失（包括直接、间接、附带或特殊损失），作者均不负责，即使已被告知可能会发生此类损失。

通过使用该镜像，表明您同意承担所有使用相关风险。此外，作者对使用该镜像可能产生的任何问题或后果，概不负责。

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-内容目录">⬆️ 返回顶部</a> 
</h2>


<h1 align="center"> 
Cloudflare SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包含通过`Cloudflare`获取`SSL证书`的内置功能。要使用脚本获取证书，您需要以下内容：


<details> 
    <summary> ⚙️ 查看详情 </summary>

- 在`Cloudflare`注册的电子邮件
- Cloudflare 的 Global API Key
- 域名必须通过`Cloudflare`DNS指向当前服务器



## 如何获取 Cloudflare Global API Key：

1. 在终端中运行命令`x-ui`，然后选择`Cloudflare SSL Certificate`。

2. 打开链接：[Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`（见下方截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 您可能需要重新验证身份，通过后即可看到密钥（见下方截图）：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


使用时输入您的域名、`email`和`API KEY`。如下所示：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 



<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-内容目录">⬆️ 返回顶部</a> 
</h2>


<h1 align="center"> 
安装3X-UI
</h1>


# 1. 3X快速安装

<details> 
    <summary> ⚙️ 查看详情 </summary>


```sh
sudo apt update && sudo apt upgrade -y && \
sudo apt install -y git curl openssl qrencode systemd && \
rm -rf self_signed_certificate.sh && \
curl -O https://raw.githubusercontent.com/AnikBeris/self-signed-certificate/main/self_signed_certificate.sh && \
chmod +x self_signed_certificate.sh && \
bash ./self_signed_certificate.sh

```

</details> 

# 2. 3X分步骤安装


<details> 
    <summary> ⚙️ 查看详情 </summary>

# 📊 安装必要软件包

1. 系统更新
在开始安装前，请确保系统已更新。运行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要的软件包

确保您的服务器安装了以下软件包：

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## 安装3X-UI面板

在服务器上运行以下脚本以安装面板：

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

安装过程中，脚本会提出如下问题：

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

如果您想自定义端口，请输入`y`，否则输入`n`，脚本将自动设置随机端口。
建议不要使用常见的端口如`22, 80, 8080`，可以选择其他端口，比如`8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

执行这些步骤后，面板安装将完成，您可以通过以下路径访问面板：

```sh
http://您的服务器IP地址:端口/WebBasePath(例如: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在浏览器中输入地址后，将进入面板登录界面，输入脚本提供的用户名和密码即可登录。

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
    <summary> ⚙️ 查看详情 </summary>

打开版本和更新选项

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

更新数据文件`GeoSite`和`GeoIP`

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 


## 启用订阅

<details> 
    <summary> ⚙️ 查看详情 </summary>

进入`设置`，启用订阅功能

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成后，点击`保存`并`重启面板`

# X-Ray 设置

## 基本连接

进入`X-Ray设置` -> 选择`基本` -> 打开`基础连接`部分

按下图设置

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后，点击`保存`并`重启 Xray`

</details> 





## DNS

<details> 
    <summary> ⚙️ 查看详情 </summary>


进入`X-Ray设置` -> 选择`DNS` -> 打开`DNS`部分

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击`新建DNS`，分别添加以下`DNS地址`

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

完成后，点击`保存`并`重启 Xray`

</details> 






<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
配置第一个连接
</h1>

## 现在可以配置第一个连接。

在侧边菜单中选择`“连接”` -> 点击`“添加连接”`

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>




<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h1 align="center"> 📜 许可证 </h1>
<p align="center">
  <strong> 本项目遵循 </strong> 
  <a href="/LICENSE">Apache 许可证</a> 
</p>

---

<h2 align="center"> 
文档阅读请参考 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
