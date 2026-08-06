# para-ti.html

Página sorpresa para Marina. Un solo archivo HTML, sin dependencias que instalar — solo súbelo y listo.

## Subirlo a GitHub

1. Crea un repositorio nuevo en GitHub (puede ser público o privado, pero si quieres usar GitHub Pages gratis necesita ser público).
2. Sube `para-ti.html` al repositorio. Puedes arrastrarlo directo desde la web de GitHub ("Add file" → "Upload files") o por terminal:

```bash
git init
git add para-ti.html
git commit -m "sorpresa para Marina"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main
```

## Publicarlo con GitHub Pages (para tener un link)

1. En el repositorio, ve a **Settings → Pages**.
2. En "Source", elige la rama `main` y la carpeta `/ (root)`.
3. Guarda. GitHub te da un link parecido a:

```
https://TU_USUARIO.github.io/TU_REPO/para-ti.html
```

Tarda uno o dos minutos en activarse la primera vez.

## Si quieres esconder el nombre del repo

GitHub Pages no te deja poner un dominio random gratis, pero puedes:
- Nombrar el repo algo neutral (no "sorpresa-marina" ni nada que dé pistas si se lo vas a mandar por sorpresa).
- Renombrar el archivo a `index.html` — así el link queda directo en `https://TU_USUARIO.github.io/TU_REPO/` sin el `/para-ti.html` al final, se ve más limpio.

## Nota

El repo va a quedar público si usas GitHub Pages gratis, lo que significa que cualquiera con el link (o buscando en tu perfil) podría verlo. Si te importa la privacidad, otra opción rápida es Netlify Drop (netlify.com/drop) — arrastras el HTML y te da un link al instante, sin necesidad de crear un repo.
