# 🚀 RAA Mirror X

![Version](https://img.shields.io/github/v/release/iscrodolfoalvarez/raa-mirror-x-releases)
![Downloads](https://img.shields.io/github/downloads/iscrodolfoalvarez/raa-mirror-x-releases/total)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows-blue)

**Interfaz gráfica profesional para Scrcpy** - Control total de dispositivos Android desde Windows

<p align="center">
  <img src="https://img.shields.io/badge/Electron-2C2E3B?style=for-the-badge&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

---

## 📥 Descargar

### 👉 [**DESCARGAR ÚLTIMA VERSIÓN**](https://github.com/iscrodolfoalvarez/raa-mirror-x-releases/releases/latest) 👈

> **Versión actual:** v1.0.0 | **Tamaño:** ~15 MB | **Idioma:** 🇪🇸 Español

---

## ✨ Características Principales

| Característica | Descripción |
|---------------|-------------|
| 🔌 **Conexión USB y WiFi** | Controla tu Android por cable o de forma inalámbrica |
| 🖥️ **Virtual Display** | Ejecuta apps en segundo plano sin afectar la pantalla principal |
| 🎬 **Grabación de Sesiones** | Graba todo lo que haces en formatos MP4 o MKV |
| 🎨 **Temas Claro/Oscuro** | Interfaz personalizable según tu preferencia |
| 🎛️ **Control ADB Integrado** | Iniciar, reiniciar o detener el servidor ADB con un clic |
| ⚙️ **Configuración Avanzada** | Control total de video, audio, resolución, bitrate y más |
| 📱 **Multi-dispositivo** | Conecta y maneja múltiples dispositivos Android |
| 🌐 **100% en Español** | Interfaz completamente traducida |

---

## 🔧 Requisitos del Sistema

### Mínimos:
- **Sistema Operativo:** Windows 10 (64-bit) o superior
- **RAM:** 4 GB
- **Procesador:** Intel Core i3 o equivalente
- **Espacio en disco:** 100 MB

### Para Android:
- **Android 5.0 (Lollipop)** o superior
- **Depuración USB habilitada**
- Cable USB (para primera conexión) o red WiFi

---

## 🚀 Instalación

### Método 1: Instalador (Recomendado)

1. **Descarga** el archivo `RAA-Mirror-X-Setup-1.0.0.exe` desde [**Releases**](https://github.com/iscrodolfoalvarez/raa-mirror-x-releases/releases/latest)
2. **Ejecuta** el instalador
3. **Sigue** las instrucciones en pantalla
4. **¡Listo!** ADB y Scrcpy ya están incluidos

### Método 2: Portable (ZIP)

1. **Descarga** el archivo `RAA-Mirror-X-v1.0.0.zip`
2. **Extrae** el contenido en una carpeta
3. **Ejecuta** `RAA-Mirror-X.exe`
4. No requiere instalación

---

## 📖 Guía de Uso

### 🔌 Primera Conexión (USB)

1. **Habilita la Depuración USB** en tu Android:
   - Ve a **Ajustes** → **Acerca del teléfono**
   - Toca **7 veces** en "Número de compilación"
   - Regresa y entra en **Opciones de desarrollo**
   - Activa **Depuración USB**

2. **Conecta** tu dispositivo por USB

3. **Abre RAA Mirror X**

4. Haz clic en **"Escanear USB"**

5. **Selecciona** tu dispositivo de la lista

6. En tu teléfono, acepta el mensaje **"¿Permitir depuración USB?"**

7. Haz clic en **"EJECUTAR SCRCPY"**

8. **¡Listo!** Verás la pantalla de tu Android en tu PC

---

### 📡 Conexión WiFi (Sin cables)

**Requisitos:** Tu PC y Android deben estar en la **misma red WiFi**

#### Opción 1: Automática (Recomendada)

1. **Conecta** primero por USB (pasos anteriores)
2. Haz clic en **"Obtener IP del Teléfono"**
3. La IP se llenará automáticamente
4. Haz clic en **"Conectar por IP"**
5. **Desconecta** el cable USB
6. Haz clic en **"Escanear TCP/IP"**
7. Selecciona tu dispositivo
8. **¡Listo!** Ahora estás conectado por WiFi

#### Opción 2: Manual

1. **Obtén la IP** de tu Android:
   - Ve a **Ajustes** → **WiFi** → Toca tu red conectada
   - Anota la dirección IP (ej: 192.168.1.100)

2. En RAA Mirror X:
   - Pega la IP en **"IP del Dispositivo"**
   - Puerto: `5555` (por defecto)
   - Haz clic en **"Conectar por IP"**

3. Haz clic en **"Escanear TCP/IP"**

4. Selecciona tu dispositivo y **"EJECUTAR SCRCPY"**

---

## 🎛️ Funciones Avanzadas

### 📹 Grabación de Sesiones

1. Ve a la pestaña **"Grabación"**
2. Haz clic en **"Examinar"** y elige dónde guardar
3. Selecciona formato: **MP4** o **MKV**
4. Ejecuta Scrcpy
5. La grabación se guardará automáticamente

### 🖥️ Virtual Display

Útil para jugar o ejecutar apps sin mostrar en la pantalla del teléfono:

1. Ve a la pestaña **"Virtual Display"**
2. Activa **"Crear nuevo display virtual"**
3. (Opcional) Especifica resolución: `1280x720/320`
4. Haz clic en **"Listar Apps Instaladas"**
5. Selecciona la app que quieres ejecutar
6. Ejecuta Scrcpy

### ⚙️ Configuración de Video

- **Resolución:** Ajusta el ancho máximo (ej: 1920, 1280, 720)
- **Bitrate:** Calidad de video (8M = alta, 4M = media, 2M = baja)
- **FPS:** Cuadros por segundo (60, 30, 24)
- **Codec:** H.264, H.265 o AV1

### 🔊 Configuración de Audio

- **Fuente:** Micrófono o audio interno del dispositivo
- **Bitrate:** 64K, 128K o 256K
- **Buffer:** Ajusta latencia vs estabilidad

---

## 🎮 Atajos de Teclado en Scrcpy

| Atajo | Acción |
|-------|--------|
| `Ctrl + F` | Pantalla completa |
| `Ctrl + G` | Redimensionar ventana 1:1 |
| `Ctrl + C` | Copiar al portapapeles |
| `Ctrl + V` | Pegar desde portapapeles |
| `Ctrl + S` | Screenshot (guarda en PC) |
| `Ctrl + O` | Apagar pantalla del dispositivo |
| `Ctrl + Shift + O` | Encender pantalla |
| `Ctrl + R` | Rotar pantalla |
| `Ctrl + N` | Expandir panel de notificaciones |
| `Ctrl + Shift + N` | Contraer panel de notificaciones |
| `Ctrl + B` o `Ctrl + ←` | Botón Atrás |
| `Ctrl + H` | Botón Home |
| `Ctrl + M` | Botón Menú |
| `MOD + P` | Encender/Apagar |

---

## ❓ Preguntas Frecuentes (FAQ)

### ❓ ¿Es gratis?
**Sí**, RAA Mirror X es completamente gratuito y de código abierto (MIT License).

### ❓ ¿Funciona en Mac o Linux?
Por ahora **solo Windows**. Versiones para Mac/Linux en desarrollo.

### ❓ ¿Necesito root?
**No**, no requiere root en el dispositivo Android.

### ❓ ¿Funciona con cualquier marca de Android?
**Sí**, funciona con Samsung, Xiaomi, Huawei, Motorola, OnePlus, etc.

### ❓ ¿Puedo controlar el teléfono desde la PC?
**Sí**, puedes usar mouse y teclado para controlar el dispositivo.

### ❓ ¿La conexión WiFi consume muchos datos?
**No**, usa tu red WiFi local, no consume datos móviles.

### ❓ ¿Por qué no detecta mi dispositivo?
Asegúrate de:
- Tener **Depuración USB** habilitada
- Usar un **cable USB de datos** (no solo carga)
- Haber aceptado el mensaje de depuración en el teléfono
- Probar con **otro puerto USB**

### ❓ ¿Puedo usar múltiples dispositivos?
**Sí**, puedes conectar varios dispositivos y elegir cuál controlar.

---

## 🛠️ Tecnologías Utilizadas

- **[Electron](https://www.electronjs.org/)** - Framework para aplicaciones de escritorio
- **[Bootstrap 5](https://getbootstrap.com/)** - Framework CSS moderno
- **[Scrcpy](https://github.com/Genymobile/scrcpy)** - Motor de screen mirroring (by Genymobile)
- **[ADB](https://developer.android.com/studio/command-line/adb)** - Android Debug Bridge
- **JavaScript** - Lógica de la aplicación

---

## 📝 Changelog

### v1.0.0 (19 Enero 2026)
- 🎉 **Primera versión estable**
- ✅ Conexión USB y TCP/IP (WiFi)
- ✅ Control ADB mejorado (Iniciar/Reiniciar/Parar)
- ✅ Virtual Display para apps en segundo plano
- ✅ Grabación de sesiones (MP4/MKV)
- ✅ Interfaz moderna con Bootstrap 5
- ✅ Temas claro y oscuro
- ✅ Configuración completa de video, audio y control
- ✅ Interfaz 100% en español
- ✅ Listado de apps instaladas con buscador
- ✅ Detección automática de IP del dispositivo

---

## 🤝 Contribuciones

¿Encontraste un bug? ¿Tienes una sugerencia?

1. Abre un **[Issue](https://github.com/iscrodolfoalvarez/raa-mirror-x-releases/issues)**
2. Describe detalladamente el problema o sugerencia
3. Incluye capturas de pantalla si es posible

---

## 📄 Licencia

Este proyecto está licenciado bajo la **Licencia MIT** - mira el archivo [LICENSE](LICENSE) para más detalles.

### Componentes de terceros:
- **Scrcpy**: [GPL-3.0 License](https://github.com/Genymobile/scrcpy/blob/master/LICENSE)
- **ADB**: [Apache License 2.0](https://source.android.com/setup/start/licenses)

---

## 🙏 Créditos y Agradecimientos

- **[Genymobile](https://github.com/Genymobile)** por crear [Scrcpy](https://github.com/Genymobile/scrcpy)
- **[Electron](https://www.electronjs.org/)** por el framework
- **[Bootstrap](https://getbootstrap.com/)** por el diseño UI
- Todos los usuarios que reportan bugs y sugieren mejoras

---

## 📧 Contacto

- 🐙 **GitHub:** [@iscrodolfoalvarez](https://github.com/iscrodolfoalvarez)
- 🎥 **YouTube:** [RodolfoAlvarez](https://youtube.com/@RodolfoAlvarez)
- 📧 **Email:** [Tu email si quieres compartirlo]

---

## 🌟 Dale una Estrella

Si este proyecto te fue útil, **¡dale una estrella!** ⭐

[![Star History Chart](https://api.star-history.com/svg?repos=iscrodolfoalvarez/raa-mirror-x-releases&type=Date)](https://star-history.com/#iscrodolfoalvarez/raa-mirror-x-releases&Date)

---

<p align="center">
  Hecho con ❤️ por <a href="https://github.com/iscrodolfoalvarez">Rodolfo Alvarez</a>
</p>

<p align="center">
  © 2026 RAA-Tech. Todos los derechos reservados.
</p>
