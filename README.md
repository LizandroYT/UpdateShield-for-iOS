# UpdateShield for iOS

**UpdateShield for iOS** es un perfil de configuración (`.mobileconfig`) diseñado para bloquear las actualizaciones automáticas del sistema operativo iOS. Lo hace evitando que el dispositivo acceda a los servidores de Apple encargados de distribuir software, mediante reglas DNS específicas.

## 🛡️ ¿Para qué sirve?

Evita que dispositivos iPhone o iPad descarguen o instalen nuevas versiones de iOS automáticamente. Ideal para usuarios que quieren mantener una versión específica por razones de compatibilidad, estabilidad o personalización (como el jailbreak).

## ⚙️ Cómo funciona

Este perfil utiliza:

- **DNS sobre HTTPS (DoH)** para asegurar el tráfico DNS.
- **OnDemandRules** para bloquear conexiones salientes a dominios de actualizaciones.
- Una lista extensa de más de 50 dominios que Apple utiliza para actualizaciones, validaciones y distribución de software.

## 📦 Instalación

1. Abre el archivo `UpdateShield.mobileconfig` en el dispositivo iOS.
2. Sigue las instrucciones del sistema para instalar el perfil.
3. Acepta todos los permisos necesarios.
4. Reinicia el dispositivo para que el bloqueo sea efectivo.

## ⚠️ Advertencias

- No bloquea todos los servicios de Apple, pero puede afectar algunas funciones como la App Store, iCloud o validaciones de apps.
- Úsalo bajo tu propio riesgo. Este perfil está pensado para uso personal, educativo o experimental.
- Requiere conocimientos básicos sobre perfiles de configuración.

## 📁 Detalles técnicos

- **Tipo de payload:** `com.apple.dnsSettings.managed`
- **Bloqueo de más de 50 dominios de Apple**
- **UUID único por payload**
- **Desarrollador:** Lizandro YT

## 📜 Licencia

Este proyecto es de uso libre solo para fines personales o educativos, **pero no puede ser modificado ni redistribuido sin permiso del autor**.

Consulta el archivo [`LICENSE.txt`](./LICENSE.txt) para más detalles.

## ✍️ Autor

- **Lizandro YT**
  

## 📌 Estado

✅ Funcional  
🧪 En pruebas con múltiples versiones de iOS
