<div align="center">

  <img src="assets/logo_banner.png" alt="CamAR Studio Logo" width="550" />

  # CamAR Studio
  ### Motor de Video en Vivo, Cámara Virtual & Retoque Facial con IA Acelerado por GPU

  [![Canal](https://img.shields.io/badge/Canal-Beta%20P%C3%BAblica-00E5FF?style=for-the-badge&logo=electron)](https://github.com/juacar01/CamArStudio/releases)
  [![Versión Actual](https://img.shields.io/badge/Versi%C3%B3n-v0.1.10--beta-purple?style=for-the-badge&logo=rust)](https://github.com/juacar01/CamArStudio/releases/tag/v0.1.10-beta)
  [![Plataforma](https://img.shields.io/badge/SO-Windows%2010%20%2F%2011%2064--bit-blue?style=for-the-badge&logo=windows)](https://github.com/juacar01/CamArStudio/releases)
  [![Aceleración](https://img.shields.io/badge/GPU-Direct3D%2011%20%7C%20HLSL-green?style=for-the-badge&logo=nvidia)](https://github.com/juacar01/CamArStudio)

  <br />

  <p align="center">
    <b>CamAr Studio</b> es una suite profesional de procesamiento de video en tiempo real y cámara virtual de ultra baja latencia (< 3 ms) diseñada para streamers, creadores de contenido, profesionales de videollamadas y podcasters.
  </p>

  <p align="center">
    <a href="https://github.com/juacar01/CamArStudio/releases/latest"><b>🚀 Descargar Última Versión</b></a> •
    <a href="docs/INSTALL.md"><b>📖 Guía de Instalación</b></a> •
    <a href="CHANGELOG.md"><b>📜 Notas de la Versión</b></a> •
    <a href="https://github.com/juacar01/CamArStudio/issues"><b>🐛 Reportar Problema</b></a>
  </p>

</div>

---

## 📸 Previsualización

<div align="center">
  <img src="assets/app_preview.png" alt="CamAr Studio Interface Preview" width="850" style="border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);" />
</div>

---

## ⚡ Enlaces Rápidos de Descarga

| Formato | Enlace Directo | Descripción |
| :--- | :--- | :--- |
| **🚀 Instalador Oficial (`.exe`)** | [**Descargar Instalador v0.1.10-beta**](https://github.com/juacar01/CamArStudio/releases/download/v0.1.10-beta/CamAr_Studio_v0.1.10-beta_Setup.exe) | Recomendado. Asistente con acceso directo y autodetección de GPU. |
| **📦 Paquete Portable (`.zip`)** | [**Descargar Portable v0.1.10-beta**](https://github.com/juacar01/CamArStudio/releases/download/v0.1.10-beta/CamAr_Studio_v0.1.10-beta_Portable.zip) | No requiere instalación. Extraer y usar de inmediato. |

> [!TIP]
> Puedes consultar el archivo [`latest.json`](latest.json) para integraciones automáticas, bots o verificaciones de versión.

---

## ✨ Características Principales

* **🚀 Arquitectura Híbrida de Ultra Alto Rendimiento:**
  - Motor base escrito en **Rust nativo** con tuberías de cómputo en **Direct3D 11 HLSL**.
  - Latencia fotograma a fotograma ultra reducida (**inferior a 3.0 ms**) y consumo mínimo de CPU.
  - Soporte para cámaras de alta resolución a 60 FPS estables (Full HD 1080p, 2K 1440p y 4K UHD).

* **✨ Retoque Facial & Escultura Anatómica Persistente:**
  - Suavizado de piel bilateral guiado (preserva textura natural de poros sin efecto borroso artificial).
  - Corrector de ojeras, manchas e imperfecciones.
  - Efecto porcelana, unificación de tono y selector de base de maquillaje anatómica.
  - Blanqueamiento dental y visagismo facial.

* **🎭 Efectos AR y Maquillaje Virtual 3D:**
  - Lentes de contacto de iris multicapa con refracción esférica y oclusión palpebral.
  - Sombras de ojos procedimentales con paletas estéticas (*Bronze*, *Sunset Glow*, *Smoky Glam*, *Foxy Glam*).
  - Contorno, rubor y simulación de barba/definición mandibular.

* **🎨 Iluminación Fotométrica y LUTs de Color Grading:**
  - Modos cromáticos estilizados: **Vívido**, **Onírico** (*Fairy Tale*, *Champagne*, *Rose Dream*, *Oni Mist*), **Editorial** y **Clásico**.
  - Aceleración de gama de colores completa (*Full Range 0-255* vs *Limited Range 16-235*) y curvas tonales.

* **🎥 Compatibilidad Universal de Cámara Virtual:**
  - Emite directamente a cualquier programa que acepte webcam:
    - **Streaming:** OBS Studio, Streamlabs OBS, vMix, XSplit.
    - **Videollamadas:** Zoom, Discord, Google Meet, Microsoft Teams, Skype.

---

## 🖥️ Requisitos del Sistema

### Mínimos:
* **Sistema Operativo:** Windows 10 (64-bit) versión 1909 o superior / Windows 11.
* **Procesador:** Intel Core i5 de 7.ª gen o AMD Ryzen 5 equivalente.
* **Memoria RAM:** 8 GB.
* **Tarjeta Gráfica:** GPU compatible con DirectX 11 (Intel Iris Xe / AMD Radeon Vega / NVIDIA GeForce GTX 960 o superior).
* **Cámara:** Cualquier cámara web USB, captura HDMI o cámara integrada.

### Recomendados:
* **Procesador:** Intel Core i7 / AMD Ryzen 7 o superior.
* **Memoria RAM:** 16 GB.
* **Tarjeta Gráfica:** NVIDIA GeForce RTX 2060 / 3060 / 4060 o AMD Radeon RX 6600 o superior.

---

## 🛡️ Verificación de Integridad (SHA-256)

Para comprobar la autenticidad de los archivos descargados:

| Archivo | Hash SHA-256 |
| :--- | :--- |
| `CamAr_Studio_v0.1.10-beta_Setup.exe` | *(Ver release oficial en GitHub)* |
| `CamAr_Studio_v0.1.10-beta_Portable.zip` | *(Ver release oficial en GitHub)* |

---

## 📄 Licencia y Derechos

© 2026 **CamAr Studio**. Todos los derechos reservados.  
Desarrollado para la comunidad de creadores, streamers y profesionales del video en vivo.
