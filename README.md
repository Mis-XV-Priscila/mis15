# Invitación de 15 años de Priscila Martinez

Ya dejé cargados los datos que me pasaste:

- **Nombre:** Priscila Martinez
- **Fecha y hora:** sábado 11 de julio de 2026, de 21:00 a 04:00
- **Lugar:** Salón Nueva Luna, La Paz (Canelones) — el botón "¿Cómo llegar?"
  abre el mapa con la ubicación exacta que me pasaste
  (https://maps.app.goo.gl/4B3YsVqL4EYVVf7i8), y también queda como link de
  respaldo por si el mapa embebido no carga.
- **Vestimenta:** Semi formal (texto del modal "Dress Code").
- **Confirmaciones y sugerencias de canciones:** saqué los formularios. Los
  botones "Confirmar asistencia" y "Sugerir canción" (tanto el de la sección
  principal como el del pie de página) ahora abren WhatsApp directo al
  +598 91 842 501, con un mensaje pre-cargado para que la persona sólo tenga
  que tocar "Enviar".

## Lo único que falta — fotos

No me pasaste fotos, así que estas siguen siendo las de la demo de fixdate.io
y conviene reemplazarlas antes de mandar la invitación:

- `modelo-invitacion/138/img/galeria/1.jpg` a `4.jpg` — galería de fotos.
- `recursos-variantes-modelos/138/snow/variantes/night/portadas/portada.webp`
  y `portada-m.webp` (foto de fondo de la portada, escritorio y celular).

Si me pasás las fotos las puedo dejar puestas yo directamente, o si preferís
hacerlo vos: basta con reemplazar esos archivos por imágenes con el mismo
nombre y formato (o cambiar el nombre del archivo en `index.html` donde se
referencian).

## Cómo subirlo a GitHub Pages

1. Descomprimí el zip en tu computadora.
2. Creá un repositorio nuevo en GitHub.
3. Subí el **contenido** de esta carpeta (el `index.html` y todas las
   subcarpetas) directamente a la raíz del repositorio — no subas la carpeta
   contenedora ni el zip.
4. En el repo: **Settings → Pages**, elegí la rama `main` y la carpeta
   `/ (root)`, guardá.
5. En unos minutos el sitio queda publicado en
   `https://tu-usuario.github.io/nombre-del-repo/`.

## Detalles técnicos menores (no afectan el uso normal)

- El selector de "Cambiar país" del template original se quitó (era
  navegación interna de fixdate.io).
- Los íconos de favicon se completaron con el mismo archivo
  (`favicon-32x32.png`) por si faltaba algún tamaño — es cosmético.
- El reproductor de YouTube de fondo y el botón "Agregar al calendario"
  siguen funcionando porque dependen de servicios públicos externos
  (YouTube, AddEvent), no del backend de fixdate.io.
