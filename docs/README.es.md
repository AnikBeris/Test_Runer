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
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Estrellas&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
artículo sobre la instalación y configuración de 3x-ui + certificado SSL
</h1>

<h2 align="center">
> 💡 Este material está orientado a usuarios experimentados.
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ Descargo de responsabilidad ⚠️
</h2>

<p align="center">
  El autor no se hace responsable de las posibles consecuencias que puedan derivarse del uso de este proyecto.<br>
  Úselo bajo su propio riesgo.
</p>

<details align="center"> 
    <summary>⚠️texto completo⚠️</summary>
    
Utilice esta imagen bajo su propio riesgo.

1. Al usarla, acepta automáticamente los términos del acuerdo de licencia vinculado a ella.

2. El autor no brinda ninguna garantía, expresa o implícita, sobre la precisión, integridad o idoneidad de esta imagen para cualquier propósito específico. 
3. El autor no se hace responsable de ninguna pérdida, incluidas, pero no limitadas a, pérdidas directas, indirectas, incidentales, consecuentes o especiales, que resulten del uso o imposibilidad de usar esta imagen o la documentación adjunta, incluso si se le ha informado de la posibilidad de tales daños.

4. Al usar esta imagen, confirma y acepta todos los riesgos asociados con su aplicación. Además, acepta que el autor no puede ser responsabilizado por ningún problema o consecuencia derivado de su uso.

</details> 

---

<h3 align="center"> 
💖 Apoya el proyecto 
</h3>

<p align="center"> 
Si este proyecto le resultó útil, puede valorarlo con una estrella.:star2: 
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
Las donaciones son muy bien recibidas, por pequeñas que sean, y muchas gracias. 😌 
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
  <sub> Gracias por su interés en el proyecto y por su apoyo 💙 </sub>
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
  <a href="#-contenido"> ⬆️ Arriba </a> 
</h2>

<h1 align="center"> 
Requisitos técnicos
</h1>

## 📊 Sistemas Operativos recomendados

<details> 
    <summary>⚙️ Ampliar descripción</summary>

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
- OpenSUSE Tumbleweed
- Amazon Linux 2023
- Windows x64

</details> 



## 📊 Arquitecturas y dispositivos compatibles

<details> 
    <summary>⚙️ Ampliar descripción</summary>

Nuestra plataforma ofrece compatibilidad con una amplia gama de arquitecturas y dispositivos, proporcionando flexibilidad en distintos entornos de cálculo. A continuación, se enumeran las principales arquitecturas compatibles:

- **amd64:** Esta arquitectura ampliamente utilizada es el estándar para PCs y servidores, ofreciendo operación fluida con la mayoría de sistemas operativos modernos.

- **x86 / i386:** Común en computadoras de escritorio y portátiles. La arquitectura tiene un soporte amplio de diversos sistemas operativos y aplicaciones, incluido `Windows, macOS y Linux`.

- **armv8 / arm64 / aarch64:** Diseñada para dispositivos móviles y embebidos modernos, como smartphones y tabletas. Ejemplos de dispositivos: `Raspberry Pi 4, Raspberry Pi 3, Raspberry Pi Zero 2/Zero 2 W`, `Orange Pi 3 LTS` y otros.

- **armv7 / arm / arm32:** Arquitectura para dispositivos móviles y embebidos más antiguos. Todavía se utiliza en sistemas como `Orange Pi Zero LTS, Orange Pi PC Plus, Raspberry Pi 2` y otros.

- **armv6 / arm / arm32:** Orientada a dispositivos embebidos muy antiguos. Aunque menos común, todavía empleada en `Raspberry Pi 1, Raspberry Pi Zero/Zero W`.

- **armv5 / arm / arm32:** Arquitectura más antigua, asociada mayormente a sistemas embebidos iniciales. Hoy es rara vez encontrada, pero podría usarse en dispositivos obsoletos como viejas versiones de `Raspberry Pi` y ciertos modelos de smartphones antiguos.

- **s390x:** Esta arquitectura típicamente se emplea en los mainframes de `IBM` y ofrece alta performance y confiabilidad para cargas de trabajo empresariales.

</details> 




## 📊 Idiomas soportados

<details> 
    <summary>⚙️ Ampliar descripción</summary>

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




## 📊 Funciones || Características

<details> 
    <summary>⚙️ Ampliar descripción</summary>

- Monitoreo del estado del sistema
- Búsqueda de todas las conexiones de entrada y clientes
- Tema: `oscuro / claro`
- Soporte para múltiples usuarios y multiprotocolo
- Protocolos soportados: `VMESS, VLESS, Trojan, Shadowsocks, Dokodemo-door, Socks, HTTP, WireGuard`
- Soporte nativo de protocolos XTLS: `RPRX-Direct, Vision, REALITY`
- Estadísticas sobre el tráfico, límite de tráfico, expiración por tiempo
- Plantillas configurables de `Xray Configurations`
- Soporte para acceso panel por `HTTPS (dominio propio + certificado SSL)`
- Soporte para solicitud con un clic de `certificado SSL` y renovación automática
- Para opciones más avanzadas de configuración, ver el panel
- API mejorada con rutas corregidas y configuraciones manejadas desde el `API`
- Soporte para modificar configuraciones utilizando diferentes parámetros disponibles en el panel
- Exportación/importación de base de datos desde el panel

</details> 




<h1 align="center">
⚠️ Descargo de responsabilidad ⚠️
</h1>

<details align="center"> 
    <summary> ⚙️ Ampliar descripción </summary>

Utilice esta imagen bajo su propio riesgo. Al usarla, acepta automáticamente los términos del acuerdo de licencia vinculado a ella.

El autor no brinda ninguna garantía, expresa o implícita, sobre la precisión, integridad o idoneidad de esta imagen para cualquier propósito específico. El autor no se hace responsable de las pérdidas, incluidas, pero no limitadas a, pérdidas directas, indirectas, incidentales, consecuentes o especiales, derivadas del uso o imposibilidad de uso de esta imagen o la documentación adjunta, incluso si se ha informado previamente de la posibilidad de tales daños.

Al usar esta imagen, confirma y acepta todos los riesgos asociados con su aplicación. Además, acepta que el autor no puede ser responsabilizado por ningún problema o consecuencia derivado de su uso.

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h2 align="center">
  <a href="#-contenido">⬆️ Arriba</a> 
</h2>



   
<h1 align="center"> 
Certificado SSL Cloudflare
</h1>

<div align="center">
  <img src="../media/Tutorial/Article_1/cloudflare.jpg" alt=" Cloud flare " width="50%">
</div>

El script de gestión incluye una función incorporada para solicitar un `certificado SSL` a través de `Cloudflare`. Para obtener el certificado con este script necesita:


<details> 
    <summary> ⚙️ Ampliar descripción </summary>

- Correo electrónico registrado en `Cloudflare`
- Global API Key Cloudflare
- El nombre de dominio debe estar dirigido (registrado en DNS) al servidor actual a través de `Cloudflare`



## Cómo obtener la Global API Key de Cloudflare:

1. En el terminal ejecute el comando `x-ui`, luego seleccione `Cloudflare SSL Certificate`.

2. Vaya al enlace: [Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

3. Presione `View Global API Key` (ver imagen a continuación):

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey1.png" alt=" API Key 1 " width="70%">
</div>

4. Es posible que se requiera autentificación nuevamente. Una vez hecho, la clave será mostrada (ver la imagen a continuación):

<div align="center">
  <img src="../media/Tutorial/Article_1/APIKey2.png" alt=" API Key 2 " width="70%">
</div>


Para usar, simplemente introduzca su dominio, `email` y `API KEY`. Ejemplo:

<div align="center">
  <img src="../media/Tutorial/Article_1/DetailEnter.png" alt=" Detail Enter " width="70%">
</div>

</details> 



<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h2 align="center">
  <a href="#-contenido">⬆️ Arriba</a> 
</h2>


<h1 align="center"> 
Instalación de 3X-UI
</h1>


# 1. Instalación rápida de 3X

<details> 
    <summary> ⚙️ Ampliar descripción </summary>


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
    <summary> ⚙️ Ampliar descripción </summary>

# 📊 Instalación de paquetes necesarios

1. Actualización del sistema
Antes de empezar la instalación, asegúrese de que su sistema está actualizado. Ejecute los siguientes comandos:

```sh
sudo apt update && sudo apt upgrade -y &&
```

2. Instalación de paquetes necesarios

Asegúrese de que en su servidor estén instalados los paquetes necesarios:

```sh
apt-get install wget curl openssl qrencode systemd -y
```



## Instalación del panel 3X-UI

Para instalar el panel en el servidor, ejecute el siguiente comando:

```sh
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

Durante la instalación, el script hará la siguiente pregunta:

```sh
Would you like to customize the Panel Port settings? (If not, a random port will be applied) [y/n]:
```

Responda `y` si desea personalizar el puerto, o `n` para que el script asigne uno automáticamente.
No elija puertos estándar como `22, 80, 8080`. Se recomienda elegir cualquier otro, como `8181`.


```sh
Nombre de usuario: 3favnjd8

Contraseña: Msdf823Ll

Puerto: 40608

WebBasePath: vpkPI6ex9ajesDX

URL de acceso: http://192.168.0.149:40608/vpkPI6ex9ajesDX
```

Después de estos pasos, la instalación del panel estará completa y podrá conectarse a él a través del navegador con la ruta:

```sh
http://IP_dirección_de_su_servidor:puerto/WebBasePath(ejemplo: http://192.168.0.10:40608/vpkPI6ex9ajesDX)
```

Introduzca la dirección en su navegador y acceda al panel, donde proporcionará el nombre de usuario y la contraseña generados por el script anteriormente.

<div align="center">
  <img src="../media/Tutorial/Article_3/Login.png" alt="Login" width="70%">
</div>

</details> 


<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
Configuración general
</h1>

## Actualización de GeoSite y GeoIP

<details> 
    <summary> ⚙️ Ampliar descripción </summary>

Abra el panel de selección de versiones y actualizaciones.

<div align="center">
  <img src="../media/Tutorial/Article_3/UISetting.png" alt="UISetting" width="70%">
</div>

Actualice los archivos de datos `GeoSite` y `GeoIP`.

<div align="center">
  <img src="../media/Tutorial/Article_3/UpdateGeo_Site_IP.png" alt="Actualizar GeoSite GeoIP" width="70%">
</div>

</details> 


## Habilitar suscripciones

<details> 
    <summary> ⚙️ Ampliar descripción </summary>

Vaya a `Configuración` y habilite las suscripciones.

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting.png" alt="Configuración" width="70%">
</div>

Cuando termine, haga clic en `Guardar` y luego en `Reiniciar panel`.

# Configuración X-Ray

## Conexiones básicas

Vaya a `Configuraciones X-Ray` -> elija `General` -> abra el submenú `Conexiones básicas`.

Establezca todo siguiendo la imagen:

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Ajuste de Xray DNS" width="70%">
</div>

Cuando termine, haga clic en `Guardar` y luego en `Reiniciar Xray`.

</details> 





## DNS

<details> 
    <summary> ⚙️ Ampliar descripción </summary>


Vaya a `Configuración X-Ray` -> elija `DNS` -> abra el submenú `DNS`.

<div align="center">
  <img src="../media/Tutorial/Article_3/Setting_Xray_DNS.png" alt="Ajuste de Xray DNS" width="70%">
</div>

Haga clic en `Crear DNS` e inserte uno por uno las direcciones `DNS`.

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

Cuando termine, haga clic en `Guardar` y luego en `Reiniciar Xray`.

</details> 






<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
Configuración de la primera conexión
</h1>

## Ahora puede proceder a configurar la primera conexión.

En el menú lateral, vaya a `"Conexiones"` -> Presione el botón `"Agregar conexión"`.

<div align="center">
  <img src="../media/Tutorial/Article_4/UI.png" alt="Interfaz de usuario" width="70%">
</div>




<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>



<h1 align="center"> 📜 Licencia </h1>
<p align="center">
  <strong> Este proyecto está distribuido bajo la </strong> 
  <a href="/LICENSE">Apache License</a> 
</p>

---

<h2 align="center"> 
Consulte la documentación 
</h2>




<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>
