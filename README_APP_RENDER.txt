MOON COFFEE — PROTOTIPO APP MÓVIL

Esta carpeta contiene una adaptación del sitio estático para presentarlo como prototipo de app móvil.

CAMBIOS REALIZADOS
- Pantalla inicial de bienvenida con el mensaje “Café bajo otra luz”.
- Botón “Explorar Moon Coffee” para entrar al catálogo.
- Navegación inferior móvil con Inicio, Cafés, Servicios, Carrito y WhatsApp.
- Indicador de cantidad de productos en el carrito.
- Se conservó el catálogo, precios, carrito, almacenamiento local y pedidos por WhatsApp del sitio original.

ARCHIVOS
- index.html: aplicación web.
- Imágenes .jpeg y .png: recursos visuales originales.
- sitemap.xml: se conserva como referencia del sitio web.

IMPORTANTE
- Este es un prototipo web adaptable a móvil, no una app nativa de Android/iOS.
- El carrito se guarda en el navegador del dispositivo mediante localStorage.
- No se ha publicado en Render desde aquí.
- Antes de producción, probar todos los enlaces y el flujo de WhatsApp en celular.

PUBLICACIÓN EN RENDER
Para Render Static Site normalmente se conecta un repositorio Git (por ejemplo, GitHub) que contenga estos archivos. Coloca index.html y todas las imágenes en la raíz del repositorio. Luego, en Render, crea un “Static Site”, conecta el repositorio y deja el campo de build command vacío; usa “.” como publish directory si la interfaz lo requiere. La configuración exacta puede variar según el flujo disponible en tu cuenta.
