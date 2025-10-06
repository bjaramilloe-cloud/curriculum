# CV Web – Bryan A. Jaramillo (HTML/CSS/JS)

Sitio de portafolio/hoja de vida con **HTML semántico**, **CSS puro** y **JavaScript vanilla**. Diseño navy/dorado, foco en **claridad**, **accesibilidad** y **rendimiento**. Ideal para evaluación académica y despliegue en **GitHub Pages** (sin build).

## Objetivo
Presentar antecedentes académicos, experiencia y competencias técnicas en un formato estático, reproducible y fácil de mantener.

## Stack y criterios
- **Tech:** HTML5, CSS (variables, grid), JS (render dinámico desde `app.js`).
- **Iconos:** Remix Icon (CDN).
- **A11y:** jerarquía de encabezados, contraste adecuado, `prefers-reduced-motion`.

## Estructura
/ (root)
index.html # estructura semántica y secciones
styles.css # estilos globales y componentes
app.js # objeto CV + render
hero.jpg # fondo
hero-headshot.jpg
cv.pdf # descarga del CV

## Contenido
Editar el objeto **`CV`** en `app.js` (datos personales, experiencia, educación, skills, certificaciones e idiomas). Reemplazar imágenes y `cv.pdf` según corresponda.

## Despliegue (GitHub Pages)
1) Subir a GitHub (rama `main`).  
2) Settings → Pages → *Deploy from a branch* → `main` → `/root`.  
3) Acceder a `https://<usuario>.github.io/<repo>/`.

## Evaluación sugerida
Validar HTML (W3C), ejecutar Lighthouse (performance/a11y), prueba visual en escritorio y móvil.

