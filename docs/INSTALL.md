# 📖 Guía de Instalación y Primeros Pasos — CamAr Studio

Esta guía te ayudará a instalar y configurar CamAr Studio en tu sistema Windows 10 u 11.

---

## 📥 Opciones de Descarga

Puedes elegir entre dos formatos de distribución según tu preferencia:

### 1. 🚀 Instalador Oficial (`.exe`) — *Recomendado*
* Instala CamAr Studio en tu sistema con acceso directo en el Menú Inicio y Escritorio.
* Detecta automáticamente tus controladores de video y dependencias de DirectX.
* Incluye un desinstalador limpio en el Panel de Control.

**Pasos:**
1. Descarga el archivo `CamAr_Studio_vX.Y.Z_Setup.exe` desde las [Releases Oficiales](https://github.com/juacar01/CamArStudio/releases).
2. Ejecuta el archivo descargado. Si Windows SmartScreen muestra una advertencia, pulsa en **"Más información"** y luego en **"Ejecutar de todas formas"**.
3. Sigue las instrucciones del asistente de instalación.
4. Inicia CamAr Studio desde el acceso directo.

---

### 2. 📦 Versión Portable (`.zip`)
* No requiere instalación en el sistema operativo.
* Ideal para ejecutar desde unidades externas, pendrives o si no dispones de privilegios de administrador.

**Pasos:**
1. Descarga el archivo `CamAr_Studio_vX.Y.Z_Portable.zip` desde las [Releases Oficiales](https://github.com/juacar01/CamArStudio/releases).
2. Haz clic derecho sobre el archivo `.zip` y selecciona **"Extraer todo..."**.
3. Abre la carpeta extraída y ejecuta el archivo `Iniciar_CamAr_Studio.bat` o `camar-engine.exe`.

---

## 🎥 Configuración en OBS Studio y Aplicaciones de Streaming

1. Abre **CamAr Studio** y enciende tu cámara seleccionada en el menú superior.
2. Activa el botón verde **"ACTIVAR CÁMARA VIRTUAL"** en la esquina superior derecha.
3. Abre **OBS Studio**:
   - En la sección **Fuentes**, pulsa en el botón `+` y selecciona **Dispositivo de captura de video**.
   - En la lista desplegable de dispositivos, selecciona **"CamAr Virtual Camera"** (u **"OBS Virtual Camera"** si estás redirigiendo el stream).
   - Configura la resolución en `1920x1080` o `2560x1440` y 30/60 FPS.
4. ¡Listo! Todo el procesamiento facial, iluminación y efectos AR se transmitirán en vivo sin latencia perceptible.

---

## 💬 Soporte y Reporte de Problemas
Si experimentas algún fallo o tienes sugerencias de nuevas funciones, abre un reporte en la pestaña [Issues](https://github.com/juacar01/CamArStudio/issues).
