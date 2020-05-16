# UOC TFM

El objetivo principal del proyecto es la producción de un Tema listo para usar enWordpress facilitando el cumplimiento de todos los requisitos de accesibilidad a los gestoresde contenidos.

## PEC4
Producción de prototipos en HTML, CSS y JS que se usarán para la creación del Tema.

## TECNOLOGÍA

Desde el punto de vista de la solución tecnológica se propone utilizar las siguientesplataformas, framework y complemento de terceros:
* [WordPress](https://wordpress.org/) como herramienta de mercado para el diseño web, cuyo lenguaje deprogramación es PHP y base de datos MySQL.
* [Bootstrap](https://github.com/twbs/bootstrap) como framework para la maquetación de las páginas en HTML5, CSS yjQuery adaptando las limitaciones que puedan tener algunos componentes.
* [UOC Boilerlate](https://github.com/uoc-advanced-html-css/uoc-boilerplate) como plantilla base para el desarrollo de los prototipos incluyendo variables personalizadas de Bootstrap.

## GUÍA DE ESTILO


# FLUJO DE DESARROLLO | UOC Boilerplate

UOC Boilerplate es un conjunto de herramientas y una plantilla de inicio para el curso de Herramientas avanzadas de HTML y CSS de la Asignatura [Herramientas Avanzadas de HTML y CSS](https://estudis.uoc.edu/ca/masters-universitaris/aplicacions-multimedia/presentacio) y el [Máster universitario de Desarrollo de Sitios y Aplicaciones Web](https://estudios.uoc.edu/es/masters-universitarios/desarrollo-sitios-aplicaciones-web/presentacion) en la [Universitat Oberta de Catalunya](https: // www. uoc.edu). Su objetivo es proporcionar un paquete de desarrollo web front-end básico y moderno basado en Parcel e incluye un compilador Sass, un transpilador ES6, minificadores, un optimizador de imagen y herramientas de desarrollo.

Esta es la versión 2.0 de UOC Boilerplate, disponible desde el semestre UOC 2018-2.


## Características

* Uso de [Parcel](https://parceljs.org) como empaquetador de módulos.
* Scripts de NPM para desarrollo rápido y compilación de código en producción.

### Hojas de estilo

* [Sass/SCSS](https://sass-lang.com) para compilación CSS.
* [PostCSS](https://postcss.org/):
    * Transpilación de CSS moderno con [`postcss-preset-env`](https://preset-env.cssdb.org/features).
    * Inclusión automática de prefijos CSS para soporte de propiedades en la mayoría de los navegadores [`autoprefixer`](https://autoprefixer.github.io/).
    * Minificación automática y optmización del código CSS en producción con [`postcss-clean`](https://github.com/leodido/postcss-clean).

### Scripts

* Habilitación de JavaScript moderno (ES201x / ES8 / ES7 / ES6 ...) que se transpila automáticamente a ES5 y se minimiza en las compilaciones de producción, con [Babel](https://babeljs.io/).

### Imágenes

* Optimización de imagen con [`parcel-plugin-imagemin`](https://github.com/DeMoorJasper/parcel-plugin-imagemin), basado en [` imagemin`](https://github.com/imagemin/imagemin) , en producción.

### Development

* Lanzamiento del servidor de desarrollo y recarga en vivo en los cambios de archivos.
* Informe de errores legible.
