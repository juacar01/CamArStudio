# 📜 Historial de Versiones — CamAr Studio

Todas las versiones notables, mejoras de rendimiento y correcciones de este proyecto se documentan en este archivo.

---

## [v0.1.19] — 2026-11-26

### Mejoras
- **Menor consumo de CPU y GPU durante el retoque.** Se ha optimizado el seguimiento facial y la protección del cabello al suavizar la piel para que la aplicación utilice mucha menos tarjeta gráfica y procesador, especialmente con cámaras a 60 FPS o al transmitir junto a OBS Studio.

### Instalación
Descarga `CamAr-Studio-v0.1.19-Setup.exe` y ábrelo. Windows puede mostrar «Windows protegió tu PC» porque el instalador aún no lleva firma digital: pulsa **Más información** y luego **Ejecutar de todas formas**.

Requisitos: Windows 10 u 11 de 64 bits y GPU compatible con DirectX 11.

---

## [v0.1.18] — 2026-11-25

### Correcciones
- **El retoque y el maquillaje ya no se pierden al inclinar la cabeza.** Si apoyabas la cabeza de lado unos segundos, la app dejaba de ver tu cara y a veces giraba la imagen por error. Ahora sigue tu cara aunque la inclines mucho, y la orientación de la cámara solo se vuelve a comprobar si sales de la imagen un rato.

### Instalación
Descarga `CamAr-Studio-v0.1.18-Setup.exe` y ábrelo. Windows puede mostrar «Windows protegió tu PC» porque el instalador aún no lleva firma digital: pulsa **Más información** y luego **Ejecutar de todas formas**.

Requisitos: Windows 10 u 11 de 64 bits y GPU compatible con DirectX 11.

---

## [v0.1.17] — 2026-11-25

### Novedades
- **Quitar brillo:** apaga los reflejos de la frente y la nariz sin dejar la piel mate. En Mejorar → Apariencia.
- **Claridad de imagen:** da definición a cejas, ojos, labios, pelo y ropa sin endurecer la piel ni dejar halos en los bordes. En Mejorar → Apariencia.
- **60 fps:** si tu cámara los ofrece, ya puedes elegirlos en la lista de formatos (antes solo aparecía 30).
- **Desenfoque en movimiento como el de una cámara:** cuando te mueves rápido, solo tú te desenfocas, en la dirección del movimiento; el fondo y los objetos quietos siguen nítidos. Viene apagado.

### Mejoras
- **Imagen más nítida:** la reducción de ruido ya solo actúa cuando tu cámara tiene grano (con poca luz). Con buena luz conserva todo el detalle de barba, pelo y ropa.
- **Ruido de color:** si tu cámara hace manchas de color con poca luz, se limpian sin perder detalle.
- **Luz IA más natural:** aclara las sombras sin lavar la imagen ni quitar nitidez.
- **Más definición en ojos, cejas y barba.**
- **Suavizar arrugas** actúa ahora también bajo los ojos y en las patas de gallo; **Reducir bolsas** y **Reducir ojeras** cubren toda la zona de debajo del ojo.
- **Corrector:** quita también manchas y rojeces más grandes que un grano, sin borrar la textura de la piel.
- **Redondear ojos** funciona con cualquier forma de ojo (antes solo con «Doe»).
- Menor uso del procesador con cámaras YUY2 y MJPEG, y seguimiento de la cara más rápido.

### Correcciones
- Con algunas cámaras (por ejemplo, Elgato Facecam en vertical) el retoque y el maquillaje se dibujaban fuera de la cara.
- La imagen salía más clara y lavada que la de la cámara.
- El surco entre la nariz y la boca ya no aclara la sombra de la nariz.
- Se retira el «Ajuste automático del color», que estropeaba la imagen.

### Instalación
Descarga `CamAr-Studio-v0.1.17-Setup.exe` y ábrelo. Windows puede mostrar «Windows protegió tu PC» porque el instalador aún no lleva firma digital: pulsa **Más información** y luego **Ejecutar de todas formas**.

Requisitos: Windows 10 u 11 de 64 bits y GPU compatible con DirectX 11.

---

## [v0.1.16] — 2026-11-24

### Novedades
- **Desenfoque en movimiento rápido (opcional):** en Ajustes puedes activar un desenfoque suave de toda la imagen cuando te mueves muy rápido, para que no se note el seguimiento de la cara. Viene apagado; ajusta la sensibilidad y la fuerza a tu gusto.

### Mejoras
- El retoque ya no alisa el vello de la barba y conserva un mínimo de textura natural en la piel.
- La nitidez se aplica solo al detalle (ojos, cejas, pelo) y no a la piel retocada.
- El color de piel se mide en la frente y las mejillas, sin la barba, para que la base quede más natural.
- Mejor detección de la cara con poca luz y a contraluz.
- Menor uso de procesador en el seguimiento facial.
- La orientación automática de la cámara es más fiable y ya no se confunde con giros de cabeza.
- El blanqueo de dientes es más estable al hablar.
- Mejor tratamiento de la piel oscura en zonas de sombra.
- Si el seguimiento se pierde un instante, el retoque no se queda desplazado sobre la imagen.

### Instalación
Descarga `CamAr-Studio-v0.1.16-Setup.exe` y ábrelo. Windows puede mostrar «Windows protegió tu PC» porque el instalador aún no lleva firma digital: pulsa **Más información** y luego **Ejecutar de todas formas**.

Requisitos: Windows 10 u 11 de 64 bits y GPU compatible con DirectX 11.

---

## [v0.1.15] — 2026-11-24

### Novedades
- **Retoque automático:** un solo deslizador ajusta el retoque por ti. Si mueves cualquier ajuste a mano, pasa a «Personalizado».
- **Tono de piel:** elige piel clara, media u oscura y CamAR te sugiere la base adecuada.
- **Croma y pantalla verde:** quita el fondo de una tela verde o azul, con transparencia hacia OBS.
- **Aviso de luz:** CamAR te avisa si hay poca luz o contraluz y puede dar una luz suave a tu cara.
- **Rendimiento a tu medida:** la primera vez que abres la app mide tu equipo y elige el perfil de calidad. Puedes cambiar entre Calidad máxima, Equilibrado y Fluidez sin reiniciar, y la app te avisa cuando baja la calidad para no perder fluidez.
- **Orientación automática de la cámara:** si tienes la cámara girada o en vertical, CamAR detecta tu cara y pone la imagen derecha sola.

### Mejoras
- El retoque respeta el pelo, las cejas y la barba, y ya no deja rastro al moverte.
- El maquillaje sigue mejor la cara en movimientos rápidos.
- Puedes ajustar la intensidad y el color de cada capa del look que tengas puesto.
- Los filtros de color se ven más fieles, y el contraste y la saturación ya no queman las luces ni las sombras.
- Mejor reducción de ruido con poca luz, sobre todo en los tonos medios y en las manchas de color.
- La vista previa es más fluida y se apaga sola al minimizar la ventana, para ahorrar recursos.
- El recorte del fondo es más estable y no se retrasa respecto a ti.
- Los colores coinciden en todos los formatos de cámara.

### Instalación
Descarga `CamAr-Studio-v0.1.15-Setup.exe` y ábrelo. Windows puede mostrar «Windows protegió tu PC» porque el instalador aún no lleva firma digital: pulsa **Más información** y luego **Ejecutar de todas formas**.

Requisitos: Windows 10 u 11 de 64 bits y GPU compatible con DirectX 11.

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
