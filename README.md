# 💀 La URL más larga del mundo

Proyecto experimental de GitHub Pages para generar direcciones web absurdamente largas y explorar páginas inspiradas en los estados HTTP.

🌐 **Sitio web:** https://anyelo888ra-ux.github.io/AAAAAAAAAAAAA.laurlmasgrandedelmundo.estaeslaurlmaslargaquepuedescrearcongithubpageslong.duckdns.org/

## 🚀 ¿Qué puedes hacer?

- Generar una URL muy larga con segmentos repetidos como `AAAAAAAAAAAAA.html/`.
- Probar la navegación con rutas que existan realmente en el repositorio.
- Explorar páginas informativas con el estilo oscuro/neón del proyecto.
- Aprender qué significan algunos códigos de estado HTTP.

## 🧪 Museo de estados HTTP

Los estados HTTP estándar se agrupan en cinco familias:

| Familia | Significado |
| --- | --- |
| **1xx** | Respuestas informativas |
| **2xx** | Solicitudes satisfactorias |
| **3xx** | Redirecciones |
| **4xx** | Errores del cliente |
| **5xx** | Errores del servidor |

Algunas páginas de ejemplo:

- [400 — Bad Request](./400.html)
- [401 — Unauthorized](./401.html)
- [403 — Forbidden](./403.html)
- [404 — Not Found](./404.html)
- [414 — URI Too Long](./414.html)

No todos los números entre 100 y 599 están asignados a un estado HTTP. La colección puede incluir estados registrados, históricos o no utilizados, siempre identificándolos como corresponda.

## ⚠️ Importante

- El generador crea una dirección como texto; **no crea automáticamente carpetas o rutas nuevas** en GitHub Pages.
- Las páginas `400.html`, `404.html` y similares son páginas informativas. Abrirlas no hace que el servidor devuelva ese código HTTP real.
- Una URL demasiado larga puede fallar con `414 Request-URI Too Large` u otro límite del servidor o de la infraestructura que recibe la solicitud.
- La longitud máxima que funcione depende del servidor y del camino de red; este proyecto no garantiza un récord universal.

## 🛠️ Tecnología

- HTML
- CSS
- JavaScript
- GitHub Pages

## 📜 Estado del proyecto

Experimento web en desarrollo. Algunas rutas anidadas deben existir físicamente en el repositorio para poder abrirse.

---

Hecho para probar hasta dónde puede llegar una URL… antes de que el servidor diga «basta» 💀
