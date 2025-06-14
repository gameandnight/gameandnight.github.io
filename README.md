# gameandnight.github.io

Portfolio personal de Iker Redondo Serra.

Este repositorio contiene archivos HTML/CSS estáticos para el sitio desplegado en GitHub Pages: https://gameandnight.github.io

**Estructura:**
- `index.html`: página de inicio con secciones “Sobre mí”, “Proyectos” y “Contacto” en un solo scroll.
- `about.html`, `projects.html`, `contact.html`: páginas independientes (opcional si prefieres navegación multi-page).
- `assets/`: contiene `cv/CV.pdf` y `images/` con recursos (avatar, capturas de proyectos).
- `.nojekyll`: archivo vacío para deshabilitar Jekyll y servir HTML puro.

**Cómo actualizar:**
1. Edita los archivos `.html` según necesites (textos, enlaces, nuevos proyectos).
2. Añade recursos en `assets/images/`.
3. Asegúrate de usar enlaces root-relative (`/about.html`, `/assets/cv/CV.pdf`, etc.).
4. `git add`, `git commit -m "Mensaje descriptivo"`, `git push origin main`.
5. GitHub Pages publica automáticamente los cambios en https://gameandnight.github.io.

**Formspree:**
Actualiza el atributo `action` del formulario en `index.html` o `contact.html` con tu ID real de Formspree.

**Notas:**
- Si alguna vez deseas usar Jekyll de nuevo, elimina `.nojekyll` y añade `_config.yml`, `index.md`, layouts, etc.
