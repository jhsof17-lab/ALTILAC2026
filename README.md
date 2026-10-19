# ALTILAC — sitio web estático

## Publicar en GitHub Pages
1. Extrae este ZIP en tu computadora.
2. En GitHub, crea un repositorio nuevo.
3. Sube el contenido de la carpeta `ALTILAC_WEB_GITHUB` al nivel principal del repositorio (debe quedar `index.html` en la raíz).
4. En el repositorio, abre **Settings → Pages**.
5. En **Build and deployment**, elige **Deploy from a branch**, selecciona `main` y `/ (root)`, y guarda.
6. Espera a que GitHub Pages publique el sitio.

## Contenido
- `index.html`: página y funcionalidades del sitio.
- `assets/`: imágenes, logos e iconos.
- `docs/`: manual, políticas y documentos PDF.

Se eliminaron copias de imágenes idénticas dentro de subcarpetas cuando ya existía una copia en `assets/`, y se optimizaron imágenes sin cambiar sus dimensiones. Se corrigió además la referencia al logo para que coincida con el nombre del archivo, importante en servidores que distinguen mayúsculas y minúsculas.

Nota: esta web es estática. Si se añaden posteriormente funciones que requieran backend o base de datos, deberán alojarse por separado.
