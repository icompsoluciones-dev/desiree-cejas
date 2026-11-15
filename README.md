# Desiree · Tu mirada perfecta

Sitio web estático para promocionar los servicios de cejas y pestañas de Desiree en La Victoria, estado Aragua, Venezuela. La página está en español y facilita las reservas y consultas por WhatsApp.

## Contenido

- `index.html`: página completa, con estilos y datos estructurados integrados.
- `cejas.jpeg`: imagen principal del sitio.
- `logo.svg`: logotipo vectorial de Desiree.
- `favicon.svg`: icono del sitio para las pestañas del navegador.

## Ver el sitio localmente

No se necesitan dependencias ni un proceso de compilación. Puedes abrir `index.html` directamente en un navegador o iniciar un servidor local desde la carpeta del proyecto:

```powershell
python -m http.server 8000
```

Luego visita <http://localhost:8000>.

## Actualizar el sitio

Edita `index.html` para cambiar los servicios, precios, promociones, ubicación o información de contacto. Los enlaces de reserva y consulta usan el número de WhatsApp `+58 412 039 5212`; actualiza también los enlaces `wa.me` y los datos estructurados JSON-LD si cambia.

Para reemplazar la imagen principal, cambia `cejas.jpeg` y conserva ese nombre, o actualiza el atributo `src` de la imagen en `index.html`. El logotipo usado en la navegación y el pie de página está en `logo.svg`.

Confirma que los precios, promociones y datos de contacto estén vigentes antes de publicar cambios.

## Publicación

El proyecto no requiere servidor de aplicación: publica `index.html`, `cejas.jpeg`, `logo.svg` y `favicon.svg` en cualquier alojamiento de sitios estáticos.
