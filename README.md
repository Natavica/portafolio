# Portafolio Web Profesional

Este portafolio fue construido con React y diseñado para condensar  la experiencia, proyectos y datos de contacto de forma elegante y dinámica, obtenidos en el curso de especialización Front End.

## Descripción

En este proyecto, el contenido se carga dinámicamente a través de archivos JSON. Está diseñado para mostrar el trabajo de forma profesional.

![Web](public/web.jpeg)

## Características Principales

- **Diseño Responsivo**: Se adapta a cualquier dispositivo (móvil, tablet, escritorio)
- **Carga Dinámica**: Toda la información se carga desde archivos JSON fácilmente editables
- **Secciones Completas**: Inicio, Sobre Mí, Proyectos y Contacto
- **Personalizable**: Fácil de adaptar a tus necesidades cambiando solo los archivos JSON
- **Moderno**: Construido con React y Tailwind CSS para un diseño limpio y actual

## Tecnologías Utilizadas 🛠️

- [React](https://reactjs.org/) - Biblioteca JavaScript para construir interfaces de usuario
- [Vite](https://vitejs.dev/) - Herramienta de desarrollo rápida para React
- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS de utilidad para el diseño
- [shadcn/ui](https://ui.shadcn.com/) - Componentes de UI reutilizables y accesibles


### Prerrequisitos 📋

Para ejecutar este proyecto necesitas tener instalado:

- [Node.js](https://nodejs.org/) (v14.0.0 o superior)
- [npm](https://www.npmjs.com/) (v6.0.0 o superior)

### Instalación 🔧

1. Clona el repositorio:

```bash
git clone git clone https://github.com/adalid-cl/portafolio-web-react.git
cd portafolio-web-react
```

2. Instala las dependencias:

```bash
npm install
```

3. Inicia el servidor de desarrollo:

```bash
npm run dev
```

4. Abre tu navegador en `http://localhost:8080`

## Estructura del Proyecto 📁

```
src/
├── components/       # Componentes reutilizables
│   ├── Navbar.jsx    # Barra de navegación
│   ├── Hero.jsx      # Sección principal (inicio)
│   ├── About.jsx     # Sección Sobre Mí
│   ├── Projects.jsx  # Sección de Proyectos
│   ├── Contact.jsx   # Sección de Contacto
│   └── Footer.jsx    # Pie de página
├── data/             # Archivos JSON con la información del portafolio
│   ├── personal.json # Información personal (nombre, bio, etc.)
│   ├── projects.json # Lista de proyectos
│   └── contact.json  # Información de contacto y redes sociales
└── pages/            # Páginas de la aplicación
    └── Index.tsx     # Página principal que muestra todas las secciones
```




  