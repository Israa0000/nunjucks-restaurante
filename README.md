# Nunjucks Restaurante

Este proyecto es una aplicación web para la gestión y visualización de menús de restaurante, utilizando Nunjucks como motor de plantillas. Incluye scripts para la generación de HTML, pruebas unitarias y estilos personalizados.

## Estructura del proyecto

- **build.js**: Script principal para construir/generar archivos del proyecto.
- **menu.js**: Lógica relacionada con la gestión del menú.
- **package.json**: Dependencias y scripts del proyecto.
- **style.css**: Estilos principales de la aplicación.
- **coverage/**: Reportes de cobertura de pruebas.
- **imgs/**: Imágenes utilizadas en la web (por ejemplo, logo).
- **scripts/**: Scripts auxiliares para generación de HTML y utilidades.
- **test/**: Pruebas unitarias para los diferentes módulos.
- **views/**: Plantillas Nunjucks para las diferentes páginas (base, menú, navbar, about, etc).

## Instalación

1. Clona el repositorio:
   ```bash
   git clone <url-del-repo>
   cd nunjucks-restaurante
   ```
2. Instala las dependencias:
   ```bash
   npm install
   ```

## Uso

- Para generar los archivos HTML:
  ```bash
  node build.js
  ```
- Para ejecutar pruebas:
  ```bash
  npm test
  ```

## Scripts principales

- `scripts/generateHtml.js`: Genera archivos HTML a partir de las plantillas y datos.
- `scripts/utils.js`: Funciones utilitarias usadas en la generación y manejo de datos.
- `scripts/test.js`: Pruebas automatizadas para los scripts.

## Pruebas

Las pruebas están ubicadas en la carpeta `test/` y cubren los módulos principales del proyecto. Se recomienda ejecutarlas después de cada cambio importante.

## Plantillas Nunjucks

Las plantillas se encuentran en la carpeta `views/` y permiten separar la lógica de presentación del resto de la aplicación. Ejemplos:
- `base.njk`: Plantilla base para heredar estructura común.
- `menu.njk`: Plantilla para mostrar el menú del restaurante.
- `navbar.njk`: Barra de navegación reutilizable.
- `about.njk`: Página de información.

## Estilos

El archivo `style.css` contiene los estilos principales. Se pueden agregar más archivos CSS en la carpeta correspondiente si es necesario.

## Cobertura

La carpeta `coverage/` contiene los reportes generados tras ejecutar las pruebas, permitiendo visualizar el porcentaje de código cubierto.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.
