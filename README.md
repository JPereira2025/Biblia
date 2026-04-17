# App Móvil de la Santa Biblia

Esta es una aplicación móvil híbrida creada con Apache Cordova que empaqueta la aplicación web de la Biblia para Android.

## Estructura del Proyecto

- `mobile/BibleApp/`: Proyecto Cordova
  - `www/`: Archivos web (HTML, JS, JSON)
  - `platforms/android/`: Código nativo para Android
  - `plugins/`: Plugins de Cordova

## Requisitos para Build

- Node.js (instalado)
- Cordova CLI (instalado)
- Java JDK 11+
- Android SDK con cmdline-tools
- Gradle

## Instalación de Dependencias

1. Instala Android Studio (incluye SDK y Gradle) desde https://developer.android.com/studio
2. Configura ANDROID_HOME y añade a PATH.

## Build y Run

```bash
cd mobile/BibleApp
cordova build android
cordova run android  # Para dispositivo conectado
```

## Funcionalidades

- Leer capítulos completos de la Biblia
- Guardar capítulos y versículos en favoritos
- Exportar favoritos como JSON para backup

## Desarrollo

Los archivos fuente están en `www/`. Edita ahí y rebuild.