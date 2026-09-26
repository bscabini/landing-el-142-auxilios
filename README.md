# El 142 Auxilios — Landing

Landing page de una sola página para El 142 Auxilios, servicio de auxilio vial y remolque con base en Barracas, CABA.

Sitio 100% estático (HTML + CSS + JS vanilla), sin build ni dependencias — se puede abrir directo (`index.html`) o publicar en GitHub Pages.

## Estructura

```
index.html            página completa
assets/logo.png        logo de la empresa
assets/gallery/         fotos reales de los móviles en servicio
```

## Editar contenido

Todo el texto, teléfonos y el link de WhatsApp están directamente en `index.html`. El número de WhatsApp se arma con el formato `https://wa.me/5491132708968?text=...` — cambiar el número ahí (y en el `href="tel:..."` de los botones de llamada) si cambia el contacto.

## Publicar en GitHub Pages

1. Subí este repo a GitHub.
2. En **Settings → Pages**, elegí la rama `main` y la carpeta `/ (root)`.
3. El sitio queda publicado en `https://<usuario>.github.io/<repo>/`.

## Dominio propio (opcional)

Si más adelante querés un dominio propio (ej. `el142auxilios.com.ar`), se configura agregando un archivo `CNAME` con el dominio y apuntando los DNS al hosting de GitHub Pages.
