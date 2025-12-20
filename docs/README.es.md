<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Español</a> |
  <a href="/docs/README.zh.md">Chino</a> |
  <strong><-------</strong>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../media/logo-dark.png">
    <img alt="Logotipo del Proyecto" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Estrellas&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SEPARADOR" width="90%">
</div>

<h1 align="center"> 
Artículo sobre la instalación y configuración de 3x-ui + certificado SSL
</h1>

<h2 align="center">
> 💡 Este material está orientado a usuarios con experiencia.
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * *

<h2 align="center">
⚠️ Descargo de responsabilidad ⚠️
</h2>

<p align="center">
  El autor no se hace responsable de las posibles consecuencias del uso de este proyecto.<br>
  Úselo bajo su propio riesgo.
</p>

<details align="center"> 
    <summary>⚠️Texto completo⚠️</summary>
    
Use esta imagen bajo su propio riesgo.

1. Al utilizarlo, acepta automáticamente los términos del acuerdo de licencia asociado.

2. El autor no ofrece ninguna garantía, ya sea explícita o implícita, respecto a la exactitud, integridad o idoneidad de esta imagen para cualquier propósito en particular. 
3. El autor no se responsabiliza por ninguna pérdida, incluidos, entre otros, daños directos, indirectos, incidentales, resultantes o especiales derivados del uso o incapacidad de uso de esta imagen o su documentación asociada, incluso si se informó por adelantado sobre la posibilidad de tales daños.

4. Al utilizar esta imagen, confirma y asume todos los riesgos asociados con su uso. Además, acepta que el autor no puede ser considerado responsable de ningún problema o consecuencia derivada de su uso.

</details> 

---

<h3 align="center"> 
💖 Apoye el proyecto 
</h3>

<p align="center"> 
Si este proyecto le resultó útil, puede valorarlo con una estrellita.:star2: 
</p>

<p align="center">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="Cómprame un café">
  </a>
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="../media/buymeacoffe.png" alt="Cómprame un café">
  </a>
</p>

<h4 align="center"> 
Las donaciones son bienvenidas, pequeñas o grandes, y muchas gracias. 😌 
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
  <sub> Gracias por su atención al proyecto y por su apoyo 💙 </sub>
</p>

---

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 Contenido

- [Introducción](#-introducción)

## 🔗 Enlaces útiles

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
  <a href="#-contenido">⬆️ Regresar</a> 
</h2>

<h1 align="center"> 
Requisitos técnicos
</h1>

## 📊 Sistema Operativo Recomendado

<details> 
    <summary>⚙️ Desplegar descripción</summary>

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

## 📊 Arquitecturas y Dispositivos Compatibles

<details> 
    <summary>⚙️ Desplegar descripción</summary>

Nuestra plataforma ofrece compatibilidad con un amplio espectro de arquitecturas y dispositivos, proporcionando flexibilidad en diversos entornos computacionales. A continuación enumeramos las arquitecturas principales compatibles:

- **amd64:** Arquitectura estándar ampliamente utilizada para computadoras personales y servidores, que garantiza el funcionamiento fluido de la mayoría de los sistemas operativos modernos.

- **x86 / i386:** Común en computadoras de escritorio y portátiles. Su soporte abarca numerosos sistemas operativos y aplicaciones, incluyendo `Windows, macOS y Linux`.

- **armv8 / arm64 / aarch64:** Diseñada para dispositivos móviles y embebidos modernos como teléfonos inteligentes y tabletas. Ejemplos de dispositivos: `Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS`, entre otros.

- **armv7 / arm / arm32:** Arquitectura para dispositivos móviles y embebidos más antiguos, aún en uso en dispositivos como `Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2`, entre otros.

- **armv6 / arm / arm32:** Diseñada para dispositivos embebidos muy antiguos, aunque menos común aún es aplicable en modelos más desactualizados como el `Raspberry Pi 1, Raspberry Pi Zero/Zero W`.

- **armv5 / arm / arm32:** Arquitectura más antigua relacionada con sistemas embebidos iniciales; utilizada rara vez en dispositivos obsoletos como las primeras versiones del `Raspberry Pi` y algunos teléfonos inteligentes antiguos.

- **s390x:** Utilizada normalmente en mainframes de `IBM`, proporciona alto rendimiento y fiabilidad para cargas de trabajo corporativas.

</details> 

## 📊 Idiomas compatibles

<details> 
    <summary>⚙️ Desplegar descripción</summary>

- Inglés
- Persa
- Chino Tradicional
- Chino Simplificado
- Japonés
- Ruso
- Vietnamita
- Español
- Indonesio
- Ucraniano
- Turco
- Portugués (Brasil)

</details> 

## 📊 Funciones || Características

<details> 
    <summary>⚙️ Desplegar descripción</summary>

- Monitoreo del estado del sistema
- Búsqueda de todas las conexiones entrantes y clientes
- Tema: `oscuro / claro`
- Soporte para múltiples usuarios y multiprotocolo
- Soporte para protocolos: `VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- Soporte para protocolos nativos XTLS: `RPRX-Direct, Vision, REALITY`
- Estadísticas de tráfico, límite de tráfico, restricción por tiempo de expiración
- Plantillas de configuración personalizables de `Xray`
- Soporte de acceso por panel a través de `HTTPS (dominio propio + certificado SSL)`
- Soporte para solicitud de certificado `SSL` con un solo clic y renovación automática
- Para configuraciones avanzadas consulte el panel
- Rutas de `API` corregidas (configuración de usuarios creada a través de `API`)
- Soporte de cambios de configuración en diferentes parámetros disponibles en el panel
- Soporte para exportar/importar bases de datos mediante el panel

</details> 

<h1 align="center">
⚠️ Descargo de responsabilidad ⚠️
</h2>

<details align="center"> 
    <summary> ⚙️ Desplegar descripción </summary>

Use esta imagen bajo su propio riesgo. Al usarla, acepta automáticamente los términos del acuerdo de licencia asociado.

El autor no ofrece ninguna garantía, ya sea explícita o implícita, respecto a la exactitud, integridad o idoneidad de esta imagen para cualquier propósito en particular. El autor no se responsabiliza por ninguna pérdida, incluidos, entre otros, daños directos, indirectos, incidentales, resultantes o especiales derivados del uso o incapacidad de uso de esta imagen o su documentación asociada, incluso si se informó por adelantado sobre la posibilidad de tales daños.

Al utilizar esta imagen, confirma y asume todos los riesgos asociados con su uso. Además, acepta que el autor no puede ser considerado responsable de ningún problema o consecuencia derivada de su uso.

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SEPARADOR" width="90%">
</div>

<h2 align="center">
  <a href="#-contenido">⬆️ Regresar</a> 
</h2>

<h1 align="center"> 
Certificado SSL de Cloudflare
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

El script de gestión incluye una función incorporada para solicitar un certificado `SSL` a través de `Cloudflare`. Para obtener el certificado con este script, debe tener:

<details> 
    <summary> ⚙️ Desplegar descripción </summary>

- Un correo electrónico registrado en `Cloudflare`
- Clave Global API de Cloudflare
- Un nombre de dominio debe estar apuntado (registrado en DNS) al servidor actual a través de `Cloudflare`

## Cómo obtener la Clave Global API de Cloudflare:

1. Ejecute en el terminal el comando `x-ui` y seleccione `Cloudflare SSL Certificate`.

2. Visite: [Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. Haga clic en `View Global API Key` (vea la captura de pantalla a continuación):

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. Es posible que necesite autenticarse de nuevo. Después de esto, verá la clave mostrada (ver captura de pantalla a continuación):

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>

Cuando lo use, simplemente ingrese su dominio, `email` y `API KEY`. Ejemplo a continuación:

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SEPARADOR" width="90%">
</div>

<h2 align="center">
  <a href="#-contenido">⬆️ Regresar</a> 
</h2>

<h1 align="center"> 
Instalación de 3X-UI
</h1>

# 1. Instalación Rápida de 3X

<details> 
    <summary> ⚙️ Desplegar descripción </summary>

```sh
sudo apt update && sudo apt upgrade -y && \
sudo apt install -y git curl openssl qrencode systemd && \
rm -rf self_signed_certificate.sh && \
curl -O https://raw.githubusercontent.com/AnikBeris/self-signed-certificate/main/self_signed_certificate.sh && \
chmod +x self_signed_certificate.sh && \
bash ./self_signed_certificate.sh

```

</details> 

# 2. Instalación paso a paso de 3X

<details> 
    <summary> ⚙️ Desplegar descripción </summary>

# 📊 Instalación de paquetes necesarios

1. Actualización del sistema
Antes de empezar la instalación, asegúrese de que su sistema esté actualizado. Ejecute los siguientes comandos:

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. Instalación de paquetes necesarios

Asegúrese de que los paquetes necesarios estén instalados en su servidor:

```sh
apt-get install wget curl openssl qrencode systemd -y
```

## Instalación del panel 3X-UI

Para instalar el panel en el servidor ejecute el siguiente script:

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

Durante la instalación, el script hará la siguiente pregunta:

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

Responda `y` si desea configurar un puerto usted mismo, o `n` para que el script configure el puerto automáticamente. No utilice puertos estándar como `22, 80, 8080`. Se recomienda usar otro, por ejemplo, el `8181`.

```sh
Username: 3favnjd8

Password: Msdf823Ll

Port: 40608

WebBasePath: vpkPI6ex9ajesDX

Access URL: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

Después de completar estos pasos, la instalación del panel estará lista y podrá acceder a él mediante la URL indicada en el navegador:

```sh
http://DIRECCIÓN_IP_DE_SU_SERVIDOR:PUERTO/WebBasePath (ejemplo: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

Al ingresar la dirección en su navegador, llegará a la pantalla de inicio de sesión del panel, donde deberá ingresar el usuario y la contraseña proporcionados anteriormente por el script.

<div align="center">
  <img src="../media/Tutorial/Article_3/Login.png" alt="Login" width="70%">
</div>

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SEPARADOR" width="90%">
</div>

<h1 align="center"> 
Configuraciones generales
</h1>

## Actualización de GeoSite GeoIP

<details> 
    <summary> ⚙️ Desplegar descripción </summary>

Abrir la sección de elección de versiones y actualizaciones.

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

Actualizar los archivos de datos `GeoSite` y `GeoIP`.

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Update GeoSite GeoIP" width="70%">
</div>

</details> 

## Activar suscripciones

<details> 
    <summary> ⚙️ Desplegar descripción </summary>

Ir a `configuración` y activar suscripción.

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Setting" width="70%">
</div>

Cuando termine, haga clic en `guardar` y luego en `reiniciar el panel`.

# Configuración de X-Ray

## Conexiones Básicas

Ir a la sección de `configuración X-Ray` -> seleccionar `General` -> abrir la subsección `Conexiones básicas`.

Configúrelo todo como en la imagen:

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

Cuando termine, haga clic en `guardar` y en `reiniciar Xray`.

</details> 

## DNS

<details> 
    <summary> ⚙️ Desplegar descripción </summary>

Ir a la sección de `configuración X-Ray` -> seleccionar `DNS` -> abrir la subsección `DNS`.

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Setting Xray DNS" width="70%">
</div>

Hacer clic en `Crear DNS` y agregar uno por uno las direcciones de `DNS`:

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

Cuando termine, haga clic en `guardar` y en `reiniciar Xray`.

</details> 

<div align="center">
  <img src="../media/image0.gif" alt="SEPARADOR" width="90%">
</div>

<h1 align="center"> 
Configuración de la primera conexión
</h1>

## Ahora puede proceder con la configuración de la primera conexión.

Ir al menú lateral `"Conexiones"` -> Hacer clic en el botón `"Agregar conexión"`.

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="UI" width="70%">
</div>

<div align="center">
  <img src="../media/image0.gif" alt="SEPARADOR" width="90%">
</div>

<h1 align="center"> 📜 Licencia </h1>
<p align="center">
  <strong> Este proyecto está distribuido bajo la </strong> 
  <a href="/LICENSE">Licencia Apache</a> 
</p>

---

<h2 align="center"> 
Consulte la documentación para más información 
</h2>

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Español</a> |
  <a href="/docs/README.zh.md">Chino</a> |
  <strong><-------</strong>
</p>
