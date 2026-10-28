# Construcciones V&G — landing page

Sitio de una página para Construcciones V&G: presentación de la empresa, proyectos, productos (bloques, cemento, áridos) y formulario de cotización.

## Tecnología

HTML estático con Tailwind CSS por CDN. No necesita compilación: basta abrir `index.html` o publicarlo en cualquier hosting estático (GitHub Pages, Netlify, Vercel).

```
index.html   página completa
assets/      logo e imágenes de productos
```

## Formulario de contacto

Al final de `index.html` está la configuración:

- `FORM_ENDPOINT` vacío: el formulario abre el correo del visitante con el mensaje escrito para `contacto@construccionesvyg.com`.
- Para recibir los mensajes directamente, crea un formulario en [Formspree](https://formspree.io) y pega su URL en `FORM_ENDPOINT`.

## Ver en local

```bash
python -m http.server 8000
# abre http://localhost:8000
```
