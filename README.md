# PUCEmedor

Sitio web del **Comedor Universitario PUCEmedor**: permite revisar el menú de la semana, ver los horarios de atención y dejar un pedido para retirarlo sin hacer fila.

Proyecto de la materia **Desarrollo Web Front End (UX/UI)**, PUCE TEC.

- **Autor:** Carlos Zambrano
- **Proyecto de grupo:** Grupo 3 (Carlos Zambrano, Jonathan Toscano y Bryan Carranza)
- **Docente:** Eduardo Xavier Conrado Zapata
- **Sitio publicado:** [pegar aquí la URL de GitHub Pages]

## Para quién está pensado

Mateo Andrade, estudiante de 20 años que usa el celular con una sola mano, a veces bajo el sol, y quiere ver el menú y pedir en menos de un minuto. El diseño parte de su User Persona, de un Card Sorting y de una auditoría de accesibilidad.

## Páginas

| Archivo | Contenido |
|---|---|
| `index.html` | Portada, menú de la semana por días, desayuno y horarios |
| `pedidos.html` | Formulario de pedido con 4 campos y observaciones opcionales |
| `gracias.html` | Confirmación del pedido |
| `css/styles.css` | Estilos (mobile-first) |

## Tecnologías

HTML5 y CSS3. No usa JavaScript ni librerías externas.

## Estructura semántica

Cada página usa `<header>` con `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`. El formulario usa `<form>`, `<fieldset>`, `<legend>`, `<label>`, `<details>` y `<button>`. Los títulos siguen el orden `h1` a `h4`.

## Accesibilidad

- Idioma declarado (`lang="es"`) y enlace "Saltar al contenido".
- Menú con `aria-current="page"` en la página actual.
- Contraste: texto blanco sobre `#b85510` (4.83:1) y bordes de campos en `#767676` (4.54:1).
- Botones, enlaces, pestañas y campos de 48 px de alto como mínimo (medido a 360 px de ancho).
- Foco visible al navegar con teclado.
- Campos obligatorios marcados con texto y `autocomplete` en el nombre.
- Las pestañas de días quedan fijas arriba; si el navegador no soporta `:has()`, se muestran los cinco días.
- En celular, el menú principal queda fijo abajo, al alcance del pulgar.

## Cómo verlo en tu computadora

1. Descarga o clona el repositorio.
2. Abre `index.html` en el navegador.

## Cómo publicarlo en GitHub Pages

1. Sube el contenido del proyecto a un repositorio público, con `index.html` en la raíz.
2. Entra a **Settings → Pages**.
3. En **Branch**, elige `main` y la carpeta `/ (root)`.
4. Guarda y espera unos minutos hasta que aparezca la URL.

## Limitaciones

El sitio es estático, así que el formulario **no guarda ni envía pedidos**: al presionar "Enviar pedido" solo se abre la página de confirmación. Para recibir pedidos reales habría que conectar el formulario a un servicio externo (por ejemplo, Formspree).

## Licencia

Proyecto académico, sin fines comerciales.
