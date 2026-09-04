# MISAEL - Catálogo Demo

Frontend público del catálogo MISAEL, ejecutado directamente desde GitHub Pages.

## Arquitectura

- GitHub Pages aloja y ejecuta el frontend completo.
- Google Apps Script funciona únicamente como backend y no se presenta como destino visible para el usuario.
- Los productos públicos se cargan mediante JSONP.
- Los pedidos se envían al backend mediante una solicitud POST con contenido `text/plain`.
- El flujo de pedidos incorpora claves de idempotencia para evitar duplicaciones, consulta posterior de estado y límites de frecuencia.

## Sitio público

[https://misaeldemo.github.io/misael-catalogo-demo/](https://misaeldemo.github.io/misael-catalogo-demo/)

La configuración privada, los datos personales, los tokens y las credenciales no forman parte de esta documentación.
