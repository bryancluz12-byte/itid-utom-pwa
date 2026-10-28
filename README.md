# Ruta ITID · UTOM (PWA)

Guía para nuevos estudiantes de Ingeniería en Tecnologías de la Información e Innovación Digital (UTOM).

## Estructura
- index.html: la aplicación
- manifest.json: datos de instalación
- sw.js: service worker (modo sin internet)
- icons/: íconos 192, 512 y maskable
- .htaccess: tipos MIME para Apache

## Correr en XAMPP
1. Copia la carpeta `itid-utom-pwa` dentro de `C:\xampp\htdocs\`
2. Abre el Panel de XAMPP y presiona Start en Apache
3. Entra a http://localhost/itid-utom-pwa/

`localhost` cuenta como conexión segura, por lo que el service worker y la instalación funcionan sin HTTPS.

## Instalar en la computadora
Con la app abierta en Chrome o Edge:
- Haz clic en el botón "Instalar app" de la página, o
- en el ícono de instalar (monitor con flecha) al final de la barra de direcciones, o
- Menú ⋮ > Guardar y compartir > Instalar página como aplicación (Chrome) / Aplicaciones > Instalar este sitio como una aplicación (Edge).

## Publicar en internet
Sube la carpeta a un hosting con HTTPS (GitHub Pages, Netlify, el servidor de la universidad). Así los alumnos podrán instalarla desde su celular y computadora.

## Actualizar
Si cambias archivos, sube el número de versión en sw.js (`itid-v2` a `itid-v3`).
