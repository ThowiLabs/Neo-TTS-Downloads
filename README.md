# Neo-TTS

Convierte texto en voz sin depender de un servicio en línea. Neo-TTS abre modelos de voz `.neo`, reproduce el audio mientras se genera y permite guardarlo en WAV.

## Descargar 1.0.0

| Sistema | Archivo | Antes de instalar |
| --- | --- | --- |
| Windows x64 | [Descargar ZIP](https://github.com/ThowiLabs/Neo-TTS-Downloads/raw/refs/tags/v1.0.0/downloads/v1.0.0/Neo-TTS-1.0.0-Windows-x64.zip) | Extrae la carpeta completa y abre `Neo-TTS-App.exe`. |
| Linux x86-64 | [Descargar AppImage](https://github.com/ThowiLabs/Neo-TTS-Downloads/raw/refs/tags/v1.0.0/downloads/v1.0.0/Neo-TTS-1.0.0-Linux-x86_64.AppImage) | Compilado con base Ubuntu 22.04. Dale permiso de ejecución al archivo. |
| Android 7.0 o posterior | [Descargar APK beta](https://github.com/ThowiLabs/Neo-TTS-Downloads/raw/refs/tags/v1.0.0/downloads/v1.0.0/Neo-TTS-1.0.0-Android-ARM-beta.apk) | Versión de prueba para ARM32 y ARM64. Se instala manualmente, fuera de Google Play. |

Para ejecutar el AppImage desde una terminal:

```sh
chmod +x Neo-TTS-1.0.0-Linux-x86_64.AppImage
./Neo-TTS-1.0.0-Linux-x86_64.AppImage
```

Los instaladores no incluyen voces. Una vez abierta la aplicación, importa un modelo `.neo` compatible (v1 o v2), escribe el texto y pulsa **Generar voz**.

## Comprobar un archivo

Los SHA-256 están en [SHA256SUMS.txt](SHA256SUMS.txt). Después de clonar el repositorio, puedes verificarlos con:

```sh
sha256sum -c SHA256SUMS.txt
```

ThowiLabs publica aquí los instaladores. El código de desarrollo se mantiene en un repositorio privado.
