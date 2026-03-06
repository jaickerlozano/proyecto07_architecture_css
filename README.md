# Proyecto 07 - Architecture

Este proyecto es una landing page sobre arquitectura desarrollada utilizando el enfoque **Mobile-First** con **Vite** y **SASS**, aplicando la arquitectura **7-1**.

## Estructura del Proyecto

El proyecto está organizado siguiendo la arquitectura 7-1 de SASS para mantener el código modular, mantenible y escalable:

- `sass/abstracts/`: Contiene herramientas como variables y mixins (ej. variables de colores, fuentes, mixins para breakpoints).
- `sass/base/`: Contiene los estilos base, reset de CSS, tipografía base y animaciones.
- `sass/components/`: Contiene estilos para componentes específicos y reutilizables como botones.
- `sass/layout/`: Define la estructura general de la página (ej. container, header, main, footer).
- `sass/pages/`: Estilos específicos de página (ej. home).
- `sass/themes/`: (Opcional) Estilos para temas específicos si aplica.
- `sass/vendors/`: Archivos CSS externos y dependencias.

## Tecnologías Utilizadas

- **HTML5**
- **SASS (SCSS)**
- **Vite**
- **JavaScript (ES Modules)**

## Instalación y Uso

Para ejecutar este proyecto en tu entorno local, sigue estos pasos:

1. **Clonar el repositorio** o descargar el código.
2. **Instalar dependencias**:
   ```bash
   npm install
   ```
3. **Iniciar el servidor de desarrollo**:
   ```bash
   npm run dev
   ```
4. **Construir para producción**:
   ```bash
   npm run build
   ```
5. **Previsualizar la build**:
   ```bash
   npm run preview
   ```

## Correcciones y Mejoras Implementadas

- **Responsividad:** Se adaptó el diseño a dispositivos móviles usando el paradigma Mobile-First y mixins de media queries en SASS para resoluciones mayores.
- **Scripts:** Se corrigió el comando `copy-dist-to-docs` en el `package.json` para asegurar que copie el directorio `dist` correctamente a `docs`.

## Licencia

Este proyecto es de libre uso.