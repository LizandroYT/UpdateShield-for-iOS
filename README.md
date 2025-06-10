# 🚀 UpdateShield for iOS

**UpdateShield for iOS** es un perfil de configuración (`.mobileconfig`) diseñado para bloquear las actualizaciones automáticas del sistema operativo iOS. Evita que el dispositivo acceda a los servidores de Apple responsables de distribuir nuevas versiones de software.

---

## 🛡️ ¿Para qué sirve?

> Evita que dispositivos iPhone o iPad descarguen o instalen nuevas versiones de iOS automáticamente.  
> Ideal para usuarios que desean mantener una versión específica por razones de compatibilidad, estabilidad o preferencias personales.

---

## ⚙️ ¿Cómo funciona?

- 🔐 **DNS sobre HTTPS (DoH)** para asegurar el tráfico DNS.
- 🚫 **OnDemandRules** para bloquear conexiones a dominios de actualizaciones.
- 📋 Lista extensa de más de 50 dominios utilizados por Apple para actualizaciones y validaciones.

---

## 📦 Instalación

1. Haz clic en el botón para descargar el perfil:

   [![Descargar](https://img.shields.io/badge/Descargar-UpdateShield--iOS.mobileconfig-blue?style=for-the-badge&logo=download)](https://github.com/LizandroYT/UpdateShield-for-iOS/releases/latest)

2. Abre el archivo `.mobileconfig` en tu dispositivo iOS.
3. Sigue las instrucciones para instalar el perfil.
4. Acepta todos los permisos necesarios.
5. Reinicia tu dispositivo para aplicar los cambios.

---

> ⚠️ **Advertencias importantes**
>
> - No bloquea todos los servicios de Apple, pero puede afectar funciones como App Store, iCloud o validaciones de apps.
> - Úsalo bajo tu propio riesgo. Este perfil es para uso personal, educativo o experimental.
> - Requiere conocimientos básicos sobre perfiles de configuración.

---

## 📁 Detalles técnicos

| Característica           | Detalle                                         |
|--------------------------|-------------------------------------------------|
| Tipo de payload          | `com.apple.dnsSettings.managed`                 |
| Dominios bloqueados      | Más de 50 dominios de Apple                     |
| UUID único               | Sí, generado para cada perfil                   |
| Desarrollador            | Lizandro YT                                     |

---

## 📜 Licencia

Este proyecto es de uso libre para fines personales o educativos, pero **no puede ser modificado ni redistribuido sin permiso del autor**.

Consulta el archivo [`LICENSE.md`](./LICENSE.md) para más detalles.

---

## ✍️ Autor

**Lizandro YT**  

---

## 📌 Estado del proyecto

![Funcional](https://img.shields.io/badge/Estado-Funcional-brightgreen)  
![Beta](https://img.shields.io/badge/Versión-Beta-yellow)

---

¡Gracias por usar UpdateShield! 🙌
