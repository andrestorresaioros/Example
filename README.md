# Parqueadero Público — Landing con Bootstrap y Sass

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat&logo=sass&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5.2-7952B3?style=flat&logo=bootstrap&logoColor=white)
[![Demo](https://img.shields.io/badge/demo-en%20línea-2ea44f?style=flat)](https://andrestorresaioros.github.io/Example/)

Página informativa de un parqueadero público (tarifas, señalización y servicios) maquetada con **Bootstrap 5**, personalizada con **Sass** y compilada con un flujo de npm.

**Demo:** https://andrestorresaioros.github.io/Example/

## Características

- Maquetación con el sistema de grillas de Bootstrap.
- Estilos de Bootstrap personalizados desde Sass (`scss/styles.scss`) y compilados a `css/styles.css`.
- Autoprefixer para compatibilidad entre navegadores y Stylelint para la calidad del código Sass.
- JavaScript de Bootstrap cargado como módulo desde CDN.

## Requisitos

- Node.js 18 o superior (solo para modificar los estilos).

## Desarrollo

```bash
npm install     # instala Bootstrap, Sass y herramientas
npm start       # compila Sass en modo observador y sirve el sitio en http://localhost:3000
```

Otros scripts disponibles:

| Script | Descripción |
|---|---|
| `npm run css` | Compila Sass y aplica Autoprefixer. |
| `npm test` | Ejecuta Stylelint y compila los estilos. |

El CSS compilado (`css/styles.css`) se incluye en el repositorio, así que para solo ver la página basta con abrir `index.html`.

## Estructura

```
.
├── index.html
├── scss/          # Código fuente Sass
├── css/           # CSS compilado
├── js/main.js     # Carga del bundle de Bootstrap
└── images/        # Imágenes de la página
```

## Créditos

Configuración inicial basada en el ejemplo [sass-js](https://github.com/twbs/examples/tree/main/sass-js) del equipo de Bootstrap.

## Autor

**César Andrés Torres Bernal** · [GitHub](https://github.com/andrestorresaioros) · [LinkedIn](https://www.linkedin.com/in/andr%C3%A9s-torres10)

## Licencia

Distribuido bajo la licencia MIT. Consulta [LICENSE](LICENSE).
