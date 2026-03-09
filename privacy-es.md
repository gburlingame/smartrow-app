---
layout: default
title: Política de privacidad
---

<div style="text-align: right; margin-bottom: 16px;">
  <a href="privacy">English</a> · <a href="privacy-de">Deutsch</a> · <a href="privacy-fr">Français</a> · <strong>Español</strong>
</div>

# Política de privacidad

**Última actualización: 28 de febrero de 2026**

SmartRow Companion ("la aplicación") es desarrollada por Greg Burlingame. Esta política de privacidad describe cómo la aplicación gestiona sus datos.

## Recopilación de datos

SmartRow Companion **no** recopila, transmite ni vende datos personales a terceros. La aplicación no contiene herramientas de análisis, publicidad ni seguimiento de ningún tipo.

## Datos almacenados en su dispositivo

La aplicación almacena los siguientes datos localmente en su dispositivo:

* **Sesiones de entrenamiento** — Las métricas de remo de cada sesión (distancia, ritmo, potencia, cadencia, frecuencia cardíaca, curvas de fuerza, calorías y marcas de tiempo) se guardan en su dispositivo utilizando el framework SwiftData de Apple.
* **Ajustes de la aplicación** — Sus preferencias (opciones de exportación, ajustes de visualización, opciones de retroalimentación) se almacenan localmente mediante UserDefaults.
* **Información de dispositivos Bluetooth** — El identificador de su dispositivo SmartRow emparejado y monitor de frecuencia cardíaca se almacena localmente para que la aplicación pueda reconectarse automáticamente.
* **Token de autenticación de Strava** — Si conecta su cuenta de Strava, un token OAuth se almacena de forma segura en el llavero de iOS en su dispositivo. Este token se utiliza únicamente para subir datos de entrenamiento a su cuenta de Strava.

## Sincronización con iCloud

Si ha iniciado sesión en iCloud en su dispositivo, las sesiones de entrenamiento se sincronizan automáticamente entre sus dispositivos mediante CloudKit de Apple. Estos datos se almacenan en su cuenta privada de iCloud y no son accesibles para el desarrollador ni para terceros. Puede gestionar o eliminar estos datos a través de sus ajustes de iCloud. Si no ha iniciado sesión en iCloud, todos los datos permanecen en su dispositivo.

## Apple Salud

Si activa la exportación a Apple Salud, la aplicación escribe datos de entrenamiento (duración, distancia, calorías y muestras de frecuencia cardíaca) en Apple Salud mediante HealthKit. Si activa las zonas de frecuencia cardíaca con el ajuste "Desde la edad", la aplicación lee su fecha de nacimiento de Apple Salud para calcular su frecuencia cardíaca máxima basada en la edad. Su fecha de nacimiento se utiliza únicamente para este cálculo y nunca se almacena, transmite ni comparte. El uso compartido de datos de salud es controlado enteramente por usted a través de los permisos de la aplicación Salud.

## Strava

Si activa la exportación a Strava, la aplicación sube datos de entrenamiento (potencia, distancia, frecuencia cardíaca, ritmo y marcas de tiempo) a su cuenta de Strava como archivo FIT. Esta subida utiliza la API de Strava y requiere su autorización a través del flujo OAuth de Strava. Puede revocar este acceso en cualquier momento a través de los ajustes de su cuenta de Strava. La aplicación no lee ningún dato de su cuenta de Strava.

## Datos de frecuencia cardíaca

Si empareja un monitor de frecuencia cardíaca Bluetooth, los datos de frecuencia cardíaca se reciben mediante Bluetooth LE durante su sesión de entrenamiento. Estos datos se muestran en tiempo real, se guardan con su sesión de entrenamiento y se incluyen en las exportaciones a Apple Salud y Strava si esas funciones están activadas. Los datos de frecuencia cardíaca nunca se transmiten a ningún otro lugar.

## Bluetooth

La aplicación se comunica con su sensor SmartRow y monitor de frecuencia cardíaca opcional mediante Bluetooth Low Energy (BLE). Toda la comunicación Bluetooth se produce directamente entre su dispositivo y los sensores. No se transmiten datos Bluetooth a ningún servidor ni a terceros.

## Retención de datos

Todos los datos de entrenamiento se almacenan en su dispositivo (y en su cuenta privada de iCloud si iCloud está activado). Puede eliminar sesiones individuales desde la aplicación. Desinstalar la aplicación elimina todos los datos almacenados localmente.

## Privacidad de los niños

La aplicación no recopila conscientemente datos de niños menores de 13 años.

## Cambios en esta política

Si esta política de privacidad se actualiza, la versión revisada se publicará en esta página con una fecha actualizada.

## Contacto

Si tiene preguntas sobre esta política de privacidad, por favor [abra una issue](https://github.com/gburlingame/smartrow-app/issues) en GitHub.
