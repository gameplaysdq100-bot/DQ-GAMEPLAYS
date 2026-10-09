DQ GAMEPLAYS — SITIO WEB
=======================

Sitio estático renovado para descubrir juegos de Android y PC, publicaciones de Minecraft y mods, noticias, guías y tutoriales.

ARCHIVOS PRINCIPALES
- index.html: inicio, navegación, categorías, buscador, catálogo, noticias y guías.
- game.html: plantilla de ficha individual para cada juego, con descripción, versión, características, requisitos orientativos, preguntas frecuentes y enlaces existentes.
- styles.css: identidad visual oscura con detalles azul neón y diseño responsive para móviles.
- app.js: carga del catálogo, búsqueda y filtros.
- games.json: catálogo y enlaces de las publicaciones.
- logo.svg: logotipo vectorial de DQ GAMEPLAYS.

CÓMO AÑADIR UN JUEGO
1. Añade una entrada en games.json dentro del arreglo "games".
2. Cada entrada debe tener un "id" único, "name", "version", "platform", "category", "short", "description", "features", "links" e "image".
3. Copia la imagen de portada en esta carpeta y escribe su nombre en el campo "image".
4. Para enlaces, conserva el formato {"label":"Texto del enlace","url":"https://..."}.

PUBLICACIÓN
Sube el contenido de esta carpeta a un hosting estático (por ejemplo, GitHub Pages o Netlify). Mantén index.html, game.html, app.js, styles.css, games.json, logo.svg y las imágenes en la misma carpeta. Para probar localmente, usa un servidor estático; abrir index.html directamente como archivo puede impedir que el navegador cargue games.json por fetch.

NOTAS
- Se conservaron las publicaciones, imágenes y enlaces que estaban en el proyecto recibido.
- La fecha mostrada en cada ficha es la fecha de revisión de la página, no necesariamente la fecha oficial de lanzamiento del juego.
- Los requisitos en las fichas son orientativos; confirma los requisitos exactos con el desarrollador o distribuidor.
- Los enlaces externos pueden cambiar y su disponibilidad no depende de este sitio.
