# María Camila · Portafolio profesional

Página web personal de María Camila, ingeniera en formación en inteligencia artificial, computación en la nube y robótica.

## Estructura

- `index.html`: la página completa (HTML, CSS y JavaScript en un solo archivo)
- `assets/logo.png`: logo con fondo transparente
- `assets/foto.jpg`: foto de perfil
- `assets/Hoja_de_vida_Maria_Camila_Rodriguez.pdf`: hoja de vida descargable

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `portafolio`).
2. Sube todos los archivos de esta carpeta, manteniendo la carpeta `assets`.
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. En uno o dos minutos la página estará en `https://TU-USUARIO.github.io/portafolio/`.

## Agregar LinkedIn y GitHub

En `index.html`, busca la línea que empieza con `var LOGO=` y completa los enlaces:

```js
LINKS={linkedin:'https://www.linkedin.com/in/tu-perfil',github:'https://github.com/tu-usuario'}
```

Los botones aparecen solos junto al de descarga de la hoja de vida.
