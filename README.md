# Aplicación Web para la gestión de libros de la biblioteca del IES Celia Viñas by Yeray

![Licencia](https://img.shields.io/badge/licencia-MIT-blue.svg)
![Estado](https://img.shields.io/badge/estado-en%20desarrollo-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

Aplicación web interactiva para la gestión de catálogos y préstamos de libros, desarrollada dentro del módulo de **Lenguajes de Marcas** (1º DAW).
##  ***Tabla de Contenidos***
- [Descripción General](#-descripción-general)
- [Características Principales](#-características-principales)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Instalación y Despliegue](#-instalación-y-despliegue)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Uso y Capturas](#-uso-y-capturas)
- [Licencia y Autoría](#-licencia-y-autoría)
### Descripción General y Problema que Resuelve
La gestión tradicional de la biblioteca del **IES Celia Viñas** se realizaba mediante registros manuales en papel u hojas de cálculo, lo que generaba varios problemas: dificultad para conocer en tiempo real la disponibilidad de los ejemplares, errores en el registro de préstamos y devoluciones, y pérdida de tiempo tanto para el personal de biblioteca como para el alumnado que deseaba consultar el catálogo.

Este proyecto nace como una ***solución digital sencilla*** que centraliza el catálogo de libros en una interfaz web accesible desde cualquier dispositivo, permitiendo consultar, filtrar y visualizar el fondo bibliográfico de forma rápida e intuitiva, sin necesidad de revisar registros físicos.

La aplicación va dirigida principalmente a:
- El **personal de la biblioteca** del centro, que necesita gestionar el catálogo de forma más ágil.
- El **alumnado y profesorado** del IES Celia Viñas, que pueden consultar la disponibilidad de un libro antes de acercarse a solicitarlo.

Además, este proyecto sirve como trabajo práctico para el módulo de **Lenguajes de Marcas** (1º DAW), aplicando los conocimientos de maquetación semántica y estilos CSS.
## Características Principales
- **Diseño Responsivo**: Adaptado a móviles, tablets y monitores.
- **Filtro dinámico**: Búsqueda en tiempo real de títulos y autores.
- **Modo Oscuro**: Alternancia de tema claro/oscuro mediante variables CSS.
## Tecnologías Utilizadas
- **HTML5**: Estructuración semántica de las páginas.
- **CSS3**: Estilos con Flexbox y CSS Grid.

### Requisitos Previos
- Navegador web moderno (Google Chrome, Firefox o Edge).
- Editor de código recomendado: [Visual Studio Code](https://code.visualstudio.com/).
## Instalación y Despliegue

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/gestor-biblioteca.git](https://github.com/tu-usuario/gestor-biblioteca.git)

2. Acceder a la carpeta del proyecto:
Bash
cd gestor-biblioteca
3. Abrir la aplicación: Abre el archivo index.html en tu navegador o inicia el servidor con la extensión Live Server de VS Code.
## Estructura del Proyecto

```text
mi-proyecto/
├── css/
│   └── styles.css
├── assets/
│   └── images/
├── index.html
└──README.md
```
## Uso y Capturas

A continuación se muestran algunas capturas de la aplicación en funcionamiento.
### Vista principal
<img width="1280" height="980" alt="live_server" src="https://github.com/user-attachments/assets/f196198e-cfbd-441d-9a53-42a5fe6ea739" />

## Hoja de Ruta (Roadmap)
- [x] Maquetación HTML5 semántica y accesible.
- [x] Estilos responsive con CSS Grid.
- [ ] Validación de formularios en cliente con JS.
- [ ] Persistencia de datos en `LocalStorage`

## Autoría y Licencia
- **Yeray** - *Estudiante de 1º DAW* - [@Pepe20844](https://github.com/Pepe20844)
- Proyecto desarrollado para el módulo de **Lenguajes de Marcas** (IES Celia Viñas).

Este proyecto está distribuido bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.
