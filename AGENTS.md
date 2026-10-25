# Trabajar en Juegos

Responde en español, con explicaciones breves. Antes de modificar archivos, lee este documento, el README y los metadatos de la rama correspondiente desde su revisión actual.

## Organización
- Este repositorio es público. `main` contiene el índice de juegos; la rama `Minecraft` reúne sus series. Cada serie tiene una carpeta propia: `HARDCORE-XTREMOW/` contiene sus mods y su ZIP de descarga.
- El propietario pide por ahora solo los mods para compartir, con sus versiones, licencias y una descarga conjunta. No añadir mundos, mapas, instaladores del juego ni proyectos que no haya solicitado.
- Mantener los archivos de Minecraft en su rama. No fusionarla automáticamente con main ni trasladar datos del repositorio privado de la web.

## Navegación del catálogo
- El README de `main` empieza por una lista de juegos. El nombre de cada juego enlaza a su índice; Minecraft enlaza a la raíz de la rama `Minecraft`.
- El README de la rama `Minecraft` presenta una lista de servidores y series. Cada nombre enlaza a su carpeta; ahora hay una sola entrada: HARDCORE XTREMOW.
- El README de cada servidor reúne su información, sus mods y las descargas, e incluye enlaces para volver al juego y al catálogo general.
- Mantener el recorrido **Juegos → Juego → Servidor o serie → Mods y descargas**. Los accesos principales de los índices deben llevar al nivel siguiente, sin saltarse la elección del juego o del servidor.
- Mantener `catalogo.json` como índice de metadatos de juegos y series. Añadir únicamente juegos y servidores reales cuando lo pida el propietario.

## Actualizar y comprobar
- Leer la revisión remota antes de escribir, conservar cambios ajenos y actualizar la rama con la revisión esperada.
- Conservar los bytes originales de los mods y las licencias incluidas en ellos. Revisar nombres, versiones, tamaño y SHA-256; comprobar la integridad del ZIP y su enlace público antes de anunciar una descarga.
- El ZIP contiene únicamente mods, sus licencias y la información mínima del paquete. No compilar, alterar ni presentar como propio el código de los mods de terceros.
- Conservar una descarga conjunta vigente por serie; al sustituirla, verificar primero el archivo nuevo y actualizar sus metadatos y README. No inventar versiones ni afirmar pruebas de instalación o acceso al juego que no se hayan realizado.
- Los mods instalados en el servidor no son necesariamente requisitos del cliente. Describir la descarga como los archivos compartidos por el propietario, sin afirmar que todos sean necesarios para entrar.

## Privacidad y web
- No subir contraseñas, tokens, claves, IP/puerto privados, server.properties, configuraciones reales, listas de jugadores, registros ni archivos del mundo.
- Publicar aquí no cambia Minecraft ni Pterodactyl, ni autoriza reiniciarlos. No cambiar su RAM ni crear copias de seguridad.
- La web se mantiene en `xycel95/Web-XyceL`. Para actualizar sus botones y enlaces hay que editar allí las fuentes aprobadas y comprobar su recibo de publicación. Un commit en Juegos no modifica por sí solo WordPress.
