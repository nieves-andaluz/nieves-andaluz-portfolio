# Portafolio web — edición y publicación

## Archivos

- `index.html`: web bilingüe editable con trayectoria, formación, herramientas y casos de trabajo.
- `linkedin-launch.md`: borrador de lanzamiento en inglés y español.
- `samples/*.html`: páginas visuales bilingües para tres muestras reconstruidas: auditoría de calidad de IA, auditoría de cumplimiento y flujo de operaciones de atención.
- `samples/*.md`: fuentes editables de las mismas muestras.

## Integridad de las muestras

Las responsabilidades y los puestos del portafolio se basan en la experiencia indicada en el CV y el perfil. Las muestras son demostraciones reconstruidas para enseñar el método de trabajo: los escenarios y hallazgos son ficticios, no informes reales ni entregables de empleadores o clientes. No contienen datos confidenciales ni resultados atribuidos a empresas.

Si más adelante se comparten artefactos reales, anonimiza clientes, empleadores, sistemas internos, capturas, identificadores y cualquier dato que no tengas permiso para publicar.

## Antes de publicar

1. Revisa el nombre, el titular, la ubicación en Madrid, el correo y el enlace a LinkedIn. No he añadido el teléfono del CV.
2. Comprueba fechas, empresas, descripciones, formación, herramientas e idiomas frente a tu CV actualizado. Edita directamente los archivos HTML o Markdown.
3. La web no necesita herramientas de compilación ni librerías externas. Abre `index.html` en un navegador para previsualizarla. El botón `ES / EN` cambia el idioma y recuerda la preferencia en ese navegador.

## Publicar con GitHub Pages

1. Crea un repositorio de GitHub y sube todo el contenido de `outputs` a la raíz, manteniendo la carpeta `samples/` junto a `index.html`.
2. En **Settings → Pages**, selecciona la rama principal y la carpeta raíz como origen, y guarda.
3. GitHub Pages mostrará la dirección pública cuando termine la publicación. Si tienes un dominio propio, puedes conectarlo desde esa misma sección.
4. Sustituye `[PORTFOLIO URL]` en `linkedin-launch.md` por la dirección publicada, revisa el texto y compártelo en LinkedIn.

También puedes subir la carpeta completa a cualquier alojamiento estático. Mantén `samples/` junto a `index.html` para que los enlaces internos funcionen.
