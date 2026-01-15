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
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Stars&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
3x-ui + SSL 证书安装与设置文章
</h1>

<h2 align="center">
> 💡 内容适用于具有一定基础的用户。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者对使用该项目的任何可能后果不承担责任。<br>
  使用自负风险。
</p>

<details align="center"> 
    <summary>⚠️完整文本⚠️</summary>
    
该镜像使用自负风险。

1. 使用该镜像，即表示您自动同意与之相关的许可协议条款。

2. 作者对该镜像的准确性、完整性或适用于任何特定目的的适用性不作任何明确或隐含的保证。
3. 作者不对因使用或无法使用该镜像或相关文档而造成的任何损失负责，包括但不限于直接、间接、附带、后果性或特殊损失，即便已事先通知有可能造成此类损失。

4. 使用该镜像，即表示您确认并自行承担所有与之相关的风险。此外，您同意作者不对因使用该镜像而导致的任何问题或后果承担责任。

</details> 

---

<h3 align="center"> 
💖 支持项目 
</h3>

<p align="center"> 
如果这个项目对您有帮助，您可以用点亮一颗星来表示支持。:star2: 
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="买杯咖啡">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="买杯咖啡">
  </a>
</p>

<h4 align="center"> 
即使是微小的捐赠也非常欢迎，感谢您的支持！😌 
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
  <sub> 感谢您关注和支持本项目！💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



## 📚 内容

- [引言](#-引言)




## 🔗 有用链接

  







* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
  <a href="#-内容"> ⬆️ 返回顶部 </a> 
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



## 📊 支持的架构与设备

<details> 
    <summary>⚙️ 展开描述</summary>

我们的平台支持多种架构和设备，为不同的计算环境提供灵活性。以下列出了主要支持的架构：

- **amd64:** 这是个人电脑和服务器的标准架构，支持大多数现代操作系统。

- **x86 / i386:** 普遍用于台式机和笔记本电脑，支持`Windows, macOS, Linux`等操作系统和应用程序。

- **armv8 / arm64 / aarch64:** 设计用于现代移动和嵌入式设备。例如：`Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`等。

- **armv7 / arm / arm32:** 针对较旧的移动和嵌入式设备。仍然被广泛用于`Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`等。

- **armv6 / arm / arm32:** 面向非常旧的嵌入式设备，例如`Raspberry Pi 1, Raspberry Pi Zero/Zero W`。

- **armv5 / arm / arm32:** 更古老的架构，主要适用于早期嵌入式系统。

- **s390x:** 通常用于`IBM`主机，为企业工作负载提供高性能和可靠性。

</details> 




## 📊 支持的语言

<details> 
    <summary>⚙️ 展开描述</summary>

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




## 📊 功能 || 特性

<details> 
    <summary>⚙️ 展开描述</summary>

- 系统状态监控
- 查询所有的入站连接和客户
- 主题: `深色/浅色`
- 支持多用户和多协议
- 支持的协议：`VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- 支持原生 XTLS 协议: `RPRX-Direct, Vision, REALITY`
- 流量统计、流量限制、到期时间限制
- 自定义 `Xray` 配置模板
- 支持通过`HTTPS`访问面板(自定义域名+SSL证书)
- 支持一键请求`SSL证书`并自动续期
- 有关更高级的配置选项，请参阅面板
- 修复了`API路由`(通过`API`创建用户设置)
- 支持对面板中可用的不同参数进行配置更改
- 支持通过面板导入/导出数据库

</details> 




<h1 align="center">
⚠️ 免责声明 ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ 展开描述 </summary>

该镜像的使用风险需自行承担。使用时即表示您自动同意与其相关的许可协议条款。

作者对该镜像的准确性、完整性或适用于任何特定目的的适用性不作任何明确或隐含的保证。作者对于因使用或无法使用该镜像及相关文档所导致的任何损失不负任何责任，包括但不限于直接、间接、附带、后果性或特殊损失，即便已被告知可能造成损失。

使用本镜像时，您承认并接受由此产生的所有风险。此外，您同意，作者无需对因使用该镜像而导致的任何问题或后果承担任何责任。

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-内容">⬆️ 返回顶部</a> 
</h2>


<h1 align="center"> 
Cloudflare SSL 证书
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

管理脚本包含通过`Cloudflare`请求 `SSL证书`的内置功能。要使用本脚本获取证书，您需要：


<details> 
    <summary> ⚙️ 展开描述 </summary>

- 注册在 `Cloudflare` 的电子邮件
- Cloudflare 的 Global API Key
- 域名需通过 `Cloudflare` 指向当前服务器



## 如何获得 Global API Key Cloudflare:

1. 在终端执行命令 `x-ui`，然后选择 `Cloudflare SSL Certificate`。

2. 访问链接: [Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. 点击`View Global API Key`(参见下图)：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. 可能需要重新身份验证。验证后钥匙将会显示(参见下图)：

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


使用时，只需输入您的域名，`email` 和 `API KEY`。示例如下：

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 



<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-内容">⬆️ 返回顶部</a> 
</h2>


<h1 align="center"> 
安装 3X-UI
</h1>


# 1. 一键安装 3X

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

# 📊 安装必要软件包

1. 更新系统
在开始安装之前，请确保您的系统是最新的。执行以下命令：

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. 安装必要的软件包

确保服务器上已安装以下必要的软件包：

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

选择 `y` 自定义端口，或选择 `n` 让脚本随机分配端口。
不要使用标准端口 `22, 80, 8080`，建议选择其他端口，例如 `8181`。

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

完成以上步骤后，安装面板完成，您可以通过浏览器访问面板路径：

```sh
http://服务器IP地址:端口/WebBasePath(例子:http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

在面板登录页面输入脚本提供的用户名和密码。

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

打开版本与更新选项面板。

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

进入`设置`并启用订阅功能。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

完成设置后点击`保存`并`重启面板`。

# X-Ray 设置

## 基础连接设置

进入`X-Ray设置`->选择`通用`->打开子选项`基础连接`。

按照图片进行设置：

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

完成后点击`保存`并`重启 Xray`。

</details> 





## DNS

<details> 
    <summary> ⚙️ 展开描述 </summary>


进入`X-Ray设置`->选择`DNS`->打开子选项`DNS`。

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

点击 `创建 DNS`，依次填写 `DNS 地址`：

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

完成后点击`保存`并`重启 Xray`。

</details> 






<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
配置第一个连接
</h1>

## 现在可以开始配置第一个连接。

在侧边菜单中转到`连接` -> 点击按钮`添加连接`。

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
  <strong> 授权。</strong>
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

