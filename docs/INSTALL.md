# 📖 Guía de Instalación y Primeros Pasos — CamAr Studio

Esta guía te ayudará a descargar, instalar y configurar CamAr Studio en tu sistema Windows 10 u 11.

---

## 📥 Enlaces Oficiales de Descarga

Puedes elegir entre dos formatos de distribución según tu preferencia:

### 1. 🚀 Instalador Oficial (`.exe`) — *Recomendado*
* Instala CamAr Studio en tu sistema con acceso directo en el Menú Inicio y Escritorio.
* Detecta automáticamente tus controladores de video y dependencias de DirectX.
* Incluye el registro del driver de Cámara Virtual y un desinstalador limpio en el Panel de Control.

* **Enlace de Descarga:** 👉 [**Descargar Instalador desde Mega**](https://mega.nz/file/edw20DAK#Hel9sZI2ronaLTrwm7VHq4hXUoH7kYvznh_2CcBsyRg)  
  *(Archivo: `CamAr-Studio-v0.1.10-beta-Setup.exe`)*

**Pasos:**
1. Descarga el archivo ejecutable del instalador desde el enlace superior.
2. Ejecuta el archivo descargado. Si Windows SmartScreen muestra una advertencia preventiva, pulsa en **"Más información"** y luego en **"Ejecutar de todas formas"**.
3. Sigue las instrucciones del asistente de instalación.
4. Inicia CamAr Studio desde el acceso directo.

---

### 2. 📦 Versión Portable (`.zip`)
* No requiere instalación en el sistema operativo ni permisos de administrador.
* Ideal para ejecutar desde unidades externas, pendrives o si deseas mantener una versión aislada.

* **Enlace de Descarga:** 👉 [**Descargar Versión Portable desde Mega**](https://mega.nz/file/mE5GVJwZ#fsqJ4LCwYs7g7mh6bqYq2UeYGFrUxgn3BqUQwKUzhxg)  
  *(Archivo: `CamAr-Studio-v0.1.10-beta-Portable.zip`)*

**Pasos:**
1. Descarga el archivo `.zip` desde el enlace superior.
2. Haz clic derecho sobre el archivo `.zip` y selecciona **"Extraer todo..."**.
3. Abre la carpeta extraída y ejecuta el archivo `Iniciar_CamAr_Studio.bat` o `CamAr-Studio.exe`.

---

## 🎥 Configuración en OBS Studio y Aplicaciones de Streaming

1. Abre **CamAr Studio** y selecciona tu cámara en el menú superior.
2. Activa el botón verde **"ACTIVAR CÁMARA VIRTUAL"** en la esquina superior derecha.
3. Abre **OBS Studio**:
   - En la sección **Fuentes**, pulsa en el botón `+` y selecciona **Dispositivo de captura de video**.
   - En la lista desplegable de dispositivos, selecciona **"CamAr Studio Virtual Camera"** (u **"OBS Virtual Camera"**).
   - Configura la resolución en `1920x1080` o `2560x1440` a 30/60 FPS.
4. ¡Listo! Todo el procesamiento facial, iluminación y efectos AR se transmitirán en vivo sin latencia perceptible.
