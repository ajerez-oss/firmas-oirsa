# Plantillas de firma OIRSA (GitHub Pages)

Este paquete parte de los dos archivos HTML proporcionados por el usuario. **Los originales sin editar están en `originales/`.**

- `Firma_OIRSA_Laptop.html`: diseño de laptop aprobado; sin cambios visuales.
- `Firma_OIRSA_Celular.html`: diseño de celular aprobado; sin cambios visuales.
- `index.html`: selector de las dos versiones.
- `assets/`: PNG idénticos a los que ya están incrustados en las firmas.

La única adaptación de las firmas publicables es el mecanismo de copiar desde una página HTTPS (`navigator.clipboard.write` con HTML y texto y un respaldo). Al copiar se usan URL absolutas a los mismos íconos e imágenes para ayudar a Outlook. **Outlook para iOS puede limitar el pegado de HTML, por lo que debe probarse con un iPhone real.**

## Publicación

1. El repositorio `ajerez-oss/firmas-oirsa` ya está creado como **privado**. En GitHub Free, para habilitar GitHub Pages de forma convencional se requiere un repositorio público; en algunos planes de pago se permiten repositorios privados, aunque el sitio publicado puede ser visible públicamente.
2. Los archivos están en la raíz de la rama `main`. Antes de publicar, decidir si corresponde hacer público el contenido, dado que contiene datos personales de ejemplo.
3. Una vez habilitado Pages para este repositorio, ir a **Settings → Pages → Build and deployment → Deploy from a branch**. Elegir **main** y **/(root)**, y guardar.
4. Abrir el enlace HTTPS que GitHub Pages anuncie en Settings → Pages y probar el botón Copiar desde Safari. Para la ruta de ejemplo: `https://ajerez-oss.github.io/firmas-oirsa/` (solo es válida cuando la publicación se confirme).

**Aviso:** GitHub Pages sirve estos archivos públicamente. Los nombres y teléfonos que aparecen por defecto en las plantillas podrán ser vistos por cualquiera con el enlace; la página no requiere credenciales.