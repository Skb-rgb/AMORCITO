# 📁 JESSICA SUÁREZ — PORTFOLIO
## Guía para personalizar y subir a GitHub

---

## 📂 Estructura de archivos

```
tu-repo/
│
├── index.html          ← Portafolio principal (parallax + galería)
├── rcn.html            ← Proyecto RCN Total
├── hyatt.html          ← Proyecto Hyatt Storytelling
├── roku.html           ← Proyecto Roku Ads Manager
│
├── imagenes/           ← 📸 CARPETA PARA TUS IMÁGENES
│   ├── jessica-foto.jpg         (tu foto en el About)
│   ├── rcn-cover.jpg            (cover de RCN en la galería)
│   ├── rcn-hero.jpg             (banner hero de rcn.html)
│   ├── rcn-contexto1.jpg        (imagen contexto en rcn.html)
│   ├── rcn-video-thumb.jpg      (thumbnail del video RCN)
│   ├── hyatt-cover.jpg          (cover de Hyatt en la galería)
│   ├── hyatt-jamaica.jpg        (cápsula Jamaica)
│   ├── hyatt-costarica.jpg      (cápsula Costa Rica)
│   ├── hyatt-alchemy.jpg        (sección alchemy)
│   ├── roku-cover.jpg           (cover de Roku en la galería)
│   ├── roku-hero.jpg            (banner hero de roku.html)
│   ├── roku-tv.jpg              (imagen TV/pantalla)
│   ├── roku-detalle.jpg         (detalle bento)
│   ├── roku-bento.jpg           (imagen bento grande)
│   └── roku-video-thumb.jpg     (thumbnail del video Roku)
│
└── videos/             ← 🎥 CARPETA PARA TUS VIDEOS (mp4)
    ├── rcn-reel.mp4
    ├── hyatt-jamaica.mp4
    ├── hyatt-costarica.mp4
    └── roku-reel.mp4
```

---

## ✏️ Cambios que debes hacer ANTES de subir

### 1. Tu email (en index.html)
Busca `hello@jessicasuarez.com` y reemplázalo por tu email real.

### 2. Tus redes sociales (en index.html footer)
```html
<!-- Busca estas líneas y cambia el href: -->
<a href="https://www.linkedin.com/in/jessica-suárez-carrillo-607973129?utm_source=share_via&utm_content=profile&utm_medium=member_android">LINKEDIN</a>
```

### 3. Tus imágenes
Crea la carpeta `imagenes/` en tu repo y agrega tus archivos con los nombres exactos de la lista de arriba.

### 4. Tus videos
**Opción A — Video mp4 propio:**
Crea la carpeta `videos/` y agrega tus archivos.
Luego en el HTML, busca el comentario `OPCIÓN A` y descomenta ese bloque.

**Opción B — YouTube o Vimeo:**
Busca el comentario `OPCIÓN B` en cada archivo HTML y descomenta ese bloque.
Reemplaza `TU_ID_DE_VIDEO` por el ID de tu video.

---

## 🚀 Cómo publicar en GitHub Pages

1. Ve a tu repositorio en GitHub
2. Click en **Settings** → **Pages**
3. En "Source" selecciona **main branch** → **/ (root)**
4. Click **Save**
5. En ~2 minutos tu sitio estará en: `https://TU_USUARIO.github.io/TU_REPO/`

---

## 🆘 Preguntas frecuentes

**¿No se ve mi imagen?**
Verifica que el nombre del archivo coincida exactamente (mayúsculas/minúsculas importan).

**¿El video no carga?**
Los mp4 muy pesados (>50MB) tardan. Comprime el video o usa YouTube/Vimeo.

**¿Cómo cambio un texto?**
Busca el texto en el HTML y cámbialo directamente. Todo está en español y bien comentado.
