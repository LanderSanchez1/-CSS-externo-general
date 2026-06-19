# MediCitas Web

## Descripción

**MediCitas Web** es un proyecto web de carácter educativo que simula una plataforma de gestión de citas médicas. El sitio permite a un usuario explorar las especialidades y servicios de una clínica, conocer a su equipo médico, agendar una cita, consultar información de contacto y acceder mediante formularios de inicio de sesión y registro. El proyecto está desarrollado con HTML5, CSS3 externo y Bootstrap 5, siguiendo un enfoque mobile-first, e incluye además una representación simulada de sus datos en formatos JSON y XML.

## Objetivo

Integrar estilos CSS externos, componentes de Bootstrap personalizados, un diseño responsivo basado en el enfoque mobile-first y la representación de datos en formatos JSON y XML dentro de un proyecto web, con el fin de mejorar su presentación visual y demostrar la correcta organización de la información que gestionaría la plataforma.

## Tecnologías utilizadas

- HTML5 (semántico)
- CSS3 (archivos externos)
- Bootstrap 5.3
- Font Awesome 6.5
- JSON
- XML

## Estructura de carpetas
Proyecto_SánchezLánder_FW/

│

├── index.html

├── about.html

├── services.html

├── specialists.html

├── citas.html

├── contact.html

├── login.html

├── register.html

│

├── page/

│   └── specialists.html

│

├── css/

│   ├── general.css        # Estilos compartidos por todo el sitio

│   ├── index.css

│   ├── about.css

│   ├── services.css

│   ├── specialists.css

│   ├── citas.css

│   ├── contact.css

│   └── auth.css

│

├── images/

│   └── (logotipo, íconos y fotografías del sitio)

│

└── data/

├── datos.json

└── datos.xml

## Componentes Bootstrap utilizados

- Navbar (con menú colapsable para móviles)
- Grid system (container / row / col)
- Cards
- Carousel
- Accordion
- Badge
- Alert
- Tables
- Form controls

Todos los componentes fueron personalizados mediante `css/general.css` (colores, bordes, sombras y estados hover/focus) para adaptarse a la identidad visual del proyecto.

## Archivos JSON y XML

Dentro de la carpeta `data/` se incluyen los archivos `datos.json` y `datos.xml`, que representan de forma estructurada la información simulada de la clínica: datos generales (`clinica`), especialidades médicas, servicios ofrecidos, médicos disponibles, citas próximas y horarios de atención. Estos archivos no se encuentran conectados dinámicamente a las páginas HTML; su propósito es ilustrar cómo podría organizarse esta misma información si, en una etapa posterior, el proyecto se conectara a un servidor o a una API real. `datos.json` representa los datos mediante objetos y arreglos en notación JavaScript, mientras que `datos.xml` representa la misma información mediante una jerarquía de etiquetas anidadas.

## Instrucciones para ejecutar el proyecto

1. Descargar o clonar el repositorio del proyecto.
2. Descomprimir el archivo, si aplica.
3. Abrir la carpeta del proyecto y ejecutar el archivo `index.html` con cualquier navegador web moderno (Google Chrome, Firefox, Edge, etc.), haciendo doble clic sobre él o usando la extensión **Live Server** de Visual Studio Code.
4. No se requiere instalar dependencias, servidor local ni base de datos, ya que el proyecto funciona completamente del lado del cliente. Bootstrap y Font Awesome se cargan mediante CDN, por lo que se recomienda contar con conexión a internet al visualizar el sitio.
5. Navegar entre las distintas páginas utilizando el menú superior (navbar).

## Autor

**Lánder Sánchez**
