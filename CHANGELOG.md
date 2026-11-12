# 📜 Historial de Versiones — CamAr Studio

Todas las versiones notables, mejoras de rendimiento y correcciones de este proyecto se documentan en este archivo.

---

## [v0.1.14] — 2026-11-12

### Correcciones
- Corregido un error al abrir la app instalada en «Archivos de programa»: ya no aparece «Acceso denegado» al arrancar. Los datos de la ventana ahora se guardan en tu carpeta de usuario.

### Instalación
Descarga `CamAr-Studio-v0.1.14-Setup.exe` y ábrelo. Windows puede mostrar «Windows protegió tu PC» porque el instalador aún no lleva firma digital: pulsa **Más información** y luego **Ejecutar de todas formas**.

Requisitos: Windows 10 u 11 de 64 bits y GPU compatible con DirectX 11.

---

## [v0.1.13] — 2026-11-12

* La marca de agua solo aparece sin licencia. La prueba gratis incluye todo lo del plan Básico.
* Looks, efectos y ambiente son del plan Streamer, que llegará pronto: por ahora se ven con candado pero no se pueden usar.

---

## [v0.1.12] — 2026-11-12

### Planes
* Planes **Básico** y **Streamer**, con licencia de Lemon Squeezy. La clave de tu plan se activa desde la ventana de licencia.
* La prueba gratis incluye todo lo del plan Básico, con marca de agua. El plan Streamer (looks y efectos) llegará pronto.

### Interfaz
* Diseño renovado con la paleta de la marca: cabecera más limpia, secciones plegables con reinicio y textos sin jerga técnica.
* La configuración muestra los datos reales de tu equipo.

### Maquillaje
* Looks instalables con doble clic (`.camarlook`) y biblioteca para verlos y borrarlos.
* Pestañas 3D y delineado sobre el borde real del párpado, adaptados a la nitidez y el grano de tu cámara.

### Salidas
* Cámara virtual propia («CamAr Studio Virtual Camera»), Spout2 y formato vertical 9:16.

---

## [v0.1.10-beta] — 2026-10-31

### 🚀 Novedades y Características Principales
* **Pipeline de Seguridad y Watermark Pro:**
  - Integración de marca de agua translúcida oficial con aceleración por hardware en HLSL Direct3D 11 (`u_watermarkActive`, `u_watermarkOpacity`).
  - Sombra suave difusa perimetral y preservación de aspecto en resoluciones 1080p, 1440p (2K) y 4K UHD.
* **Licencias:**
  - Activación de la versión completa desde la interfaz.
* **Calibración y Filtros Oníricos:**
  - Nuevos LUTs fotométricos procedimentales: *Oni Mist*, *Fairy Tale*, *Champagne*, *Rose Dream* y *Angelic Glow*.

---

## [v0.1.9-beta] — 2026-10-25

### ⚙️ Mejoras de Captura y Hardware
* **Rotación y Espacios de Color NV12:**
  - Corrección de flujos verticales a 90° y 270° en streams NV12 crudos con paso directo a shaders HLSL.
  - Soporte de fallback inteligente para MediaFoundation en cámaras de alta tasa de cuadros (Elgato Facecam, Logitech Brio).
  - Selector de rango cromático (Full Range 0-255 vs Limited Range 16-235).

---

## [v0.1.8-beta] — 2026-10-20

### 🎨 Efectos AR y Maquillaje 3D
* **Sombras de Ojos Procedimentales (Eyeshadow Filter):**
  - Texturas deformables con blending alfa y paletas tintadas (*Bronze*, *Sunset Glow*, *Smoky Glam*, *Foxy Glam*).
* **Presets de Belleza Integrados:**
  - Añadido preset temático *Foxy Latina Glam* con ajuste facial persistente.
  - Renderizado multicapa de lentes de iris procedimentales con refracción esférica y oclusión palpebral.

---

## [v0.1.7-beta] — 2026-10-15

### ⚡ Rendimiento y Cámara Virtual
* **Optimización de Previsualización:**
  - Descarte inteligente de fotogramas retrasados en WebView2 para mantener previsualizaciones fluidas a 60 FPS estables.
  - Emisión directa a través de Virtual Camera compatible con OBS Studio, Discord y software de videollamadas.

---

## [v0.1.0-beta] — 2026-10-10

### 🏁 Lanzamiento Inicial (Baseline)
* Motor híbrido de ultra alto rendimiento en Rust + Direct3D 11.
* Interfaz reactiva en React, Vite y TailwindCSS.
* Suavizado de piel bilateral guiado, escultura facial anatómica y base de tez.
* Soporte nativo para cámaras DirectShow y MediaFoundation.
