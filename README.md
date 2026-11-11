# CIMA Propulsion · Landing page

Sitio estático listo para GitHub Pages. Incluye `index.html`, `styles.css`, `script.js`, y `assets/` con los logotipos del kit proporcionado, más ilustraciones SVG originales del cohete y un TEUS caricaturizado.

## Publicar en GitHub Pages
1. Crea un repositorio público nuevo en GitHub (por ejemplo `cima-propulsion`).
2. Sube **el contenido de esta carpeta** a la raíz del repositorio (no subas solo el ZIP).
3. En GitHub entra a **Settings → Pages**.
4. Selecciona **Deploy from a branch**, la rama `main` y la carpeta `/ (root)` y guarda.
5. La página quedará en `https://TU-USUARIO.github.io/cima-propulsion/` una vez desplegada.

## Personalizar
- **Equipo:** reemplaza los textos de `Nombre del integrante` y `Área / responsabilidad` en `index.html`.
- **Fotos:** en cada `.crew-avatar`, cambia el icono SVG por una foto (`<img src="assets/mi-foto.jpg" alt="Nombre">`) y ajusta `object-fit:cover` en `styles.css`.
- **Estado real de la misión:** cambia las descripciones de etapas en `index.html` según el avance comprobado del equipo.
- **Paleta:** variables `:root` en `styles.css`.
- **Cuenta regresiva:** personalizable en `script.js` (`for(let i=5;i>=1;i--)`). El despegue es una animación recreativa, no un sistema de telemetría.
- **Archivos:** los SVG del ZIP se encuentran en `assets/logos/`.

## Notas
No necesita backend ni librerías JavaScript externas. Las fuentes Google Fonts requieren conexión; existen fuentes alternativas locales. TEUS es una ilustración recreativa no oficial de la mascota del Tecnológico de Monterrey. No implica patrocinio institucional.

## Tipografía actualizada
Los títulos utilizan **Exo 2 ExtraBold/Black Italic**, mientras el texto y la navegación emplean **Montserrat**. Ambas se cargan desde Google Fonts con alternativas de sistema.


## Ajustes de contraste (v3)
Los títulos y textos sobre fondos oscuros utilizan blanco cálido, plata clara y acentos rojo luminoso. Las tarjetas claras mantienen azul profundo. Se mejoró el contraste de navegación, botones, tarjetas y menú móvil. Se actualizó la referencia de CSS para evitar caché en GitHub Pages.
