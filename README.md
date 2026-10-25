# Integración TI

Repositorio del mural de recuerdos y planificación de eventos del equipo.

## Qué hace esta entrega

- `index.html` abre el mural que ya funciona, mediante una redirección al alojamiento actual.
- `codigo/mural-servidor.mjs` conserva una copia portable de la implementación: interfaz, edición, collages, videos, planificación y servidor.
- `codigo/esquema.sql` documenta la estructura de la base de datos.

GitHub Pages publica únicamente `index.html`. No ejecuta el archivo del servidor ni almacena los álbumes compartidos. Al entrar desde GitHub, la barra de direcciones cambiará al dominio actual del mural. Esto es un acceso al sistema existente, no una migración del alojamiento ni una forma de eliminar el dominio actual.

## Privacidad de esta copia

No incluye la clave de administración, fotos, videos, respaldos ni registros actuales de planificación. Se retiraron las comisiones y tareas iniciales con nombres del equipo de esta copia pública. El mural original, sus datos y su almacenamiento no se han modificado. La clave permanece configurada en el servidor actual.

## Cómo subirlo

1. Descomprime el ZIP en tu PC.
2. Abre https://github.com/Chechitar12/INTEGRACION-TI
3. En Code, selecciona Add file → Upload files.
4. Arrastra `index.html`, `README.md`, `.nojekyll` y la carpeta `codigo` a la zona de carga. Debe verse `index.html` en la raíz, no dentro de otra carpeta. Si Windows oculta `.nojekyll`, puedes omitirlo: esta página no depende de él.
5. Comprueba que aparezca `codigo/mural-servidor.mjs` conservando la carpeta y pulsa Commit changes. El README nuevo puede reemplazar el README inicial del repositorio.
6. En Settings → Pages, conserva Deploy from a branch, main, / (root).
7. Espera a que termine el despliegue en Actions. Pages mostrará el enlace publicado. El enlace esperado es https://chechitar12.github.io/INTEGRACION-TI/ (pendiente de que subas estos archivos y GitHub confirme el despliegue).
8. Abre ese enlace: debe llevar al mural actual y mostrar los mismos recuerdos. Usa Administrar de la misma manera que antes.

## Actualizaciones y límites

Los cambios en el mural alojado se ven al abrirlo; este acceso no requiere reexportar las fotos. La copia de código de este repositorio no se actualiza automáticamente y habrá que reemplazarla cuando se desee guardar otra versión. Subir cambios a `codigo` tampoco modifica el sitio en producción. Si el alojamiento actual deja de estar disponible, el acceso de GitHub dejará de abrir el mural. No se ha contratado otro servicio ni se ha configurado facturación nueva.

La copia del servidor necesita una base de datos, un bucket de archivos y el secreto MURAL_ADMIN_PASSWORD para funcionar en un alojamiento compatible; esos recursos no se incluyen ni deben publicarse en GitHub. Una futura migración será un trabajo separado.
