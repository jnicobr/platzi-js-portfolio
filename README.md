# js-portfolio

## Instalación de Webpack y construcción del proyecto

### El proyecto

Será un portafolio, con un set de archivos y códigos ya realizados por el profesor Oscar Barajas <oscar@gndx.dev>. El bojetivo será utilizar Webpack, con sus distintas configuraciones, loaders y plugins para procesar todos estos archivos del portafolio, dejando el portafolio listo para deployment.

<aside>
💡 En Windows, este diagrama puede crearse con `tree /a /f > SITEMAP.md` desde el `cmd` estando dentro de la carpeta raiz.

</aside>

```
.
|   .gitignore
|   LICENSE
|   output.doc
|   package.json
|   README.md
|   
+---public
|       index.html
|       
\---src
    |   index.js
    |   
    +---assets
    |   +---fonts
    |   |       ubuntu-300.woff
    |   |       ubuntu-300.woff2
    |   |       ubuntu-500.woff
    |   |       ubuntu-500.woff2
    |   |       ubuntu-regular.woff
    |   |       ubuntu-regular.woff2
    |   |       
    |   \---images
    |           github.png
    |           instagram.png
    |           twitter.png
    |           
    +---styles
    |       main.css
    |       
    +---templates
    |       Template.js
    |       
    \---utils
            getData.js
```

### Instalando Webpack

Instalamos Webpack y su interfaz de línea de comandos como dependencias de desarrollo.

```bash
# ./
npm i webpack webpack-cli -D
npx webpack --mode production # Podría ser solo npx webpack porque production es el modo por defecto
```