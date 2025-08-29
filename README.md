# Opiron - SaaS Landing Page

Una landing page moderna y elegante construida con Astro para Opiron, una plataforma SaaS de integración y automatización.

## 🚀 Características

- **Diseño Moderno**: Interfaz limpia y profesional con animaciones suaves
- **Responsive**: Totalmente adaptable a dispositivos móviles y desktop
- **Optimizado**: Construido con Astro para máximo rendimiento
- **Componentes Reutilizables**: Arquitectura modular y mantenible
- **Integración Lista**: Botones "Get Started" conectados a la aplicación de registro

## 🛠️ Tecnologías Utilizadas

- [Astro](https://astro.build/) - Framework web moderno
- [Tailwind CSS](https://tailwindcss.com/) - Framework de CSS utilitario
- [TypeScript](https://www.typescriptlang.org/) - Tipado estático
- HTML5 & CSS3

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone <url-del-repositorio>
cd saas-landing
```

2. Instala las dependencias:
```bash
npm install
# o
pnpm install
```

3. Inicia el servidor de desarrollo:
```bash
npm run dev
# o
pnpm dev
```

4. Abre tu navegador en `http://localhost:4321`

## 🏗️ Estructura del Proyecto

```
src/
├── layouts/          # Layouts principales
├── pages/           # Páginas de la aplicación
├── presentation/    # Componentes de presentación
│   ├── components/  # Componentes reutilizables
│   └── layouts/     # Layouts específicos
├── styles/          # Estilos globales y animaciones
└── utils/           # Utilidades y constantes

public/              # Archivos estáticos (imágenes, iconos)
```

## 🎨 Secciones Principales

- **Hero**: Sección principal con llamada a la acción
- **Features**: Características principales del producto
- **Integration**: Herramientas de integración disponibles
- **Pricing**: Planes y precios
- **Testimonials**: Testimonios de clientes
- **Core Values**: Valores fundamentales de la empresa

## 🔗 Enlaces de Integración

Los botones "Get Started" están configurados para redirigir a:
- **Registro**: `https://login-5v5qqaire-angelpro17s-projects.vercel.app/signup`
- **Login**: `https://login-5v5qqaire-angelpro17s-projects.vercel.app/login`

## 📱 Comandos Disponibles

| Comando | Descripción |
|---------|-------------|
| `npm install` | Instala las dependencias |
| `npm run dev` | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build` | Construye la aplicación para producción en `./dist/` |
| `npm run preview` | Vista previa de la build de producción |
| `npm run astro` | Ejecuta comandos de Astro CLI |

## 🎯 Optimizaciones Implementadas

- **Imágenes**: Formato WebP para mejor compresión
- **Favicon**: Logo personalizado de Opiron (opironLogo.svg)
- **Animaciones**: CSS optimizado para transiciones suaves
- **Código Limpio**: Eliminación de archivos no utilizados
- **Performance**: Carga optimizada de recursos

## 🚀 Despliegue

Para desplegar en producción:

1. Construye la aplicación:
```bash
npm run build
```

2. Los archivos generados estarán en la carpeta `dist/`

3. Despliega en tu plataforma preferida (Vercel, Netlify, etc.)

## 🔧 Personalización

- **Colores**: Modifica los colores en `tailwind.config.mjs`
- **Contenido**: Actualiza el contenido en los componentes de `src/presentation/components/`
- **Imágenes**: Reemplaza las imágenes en la carpeta `public/`
- **Enlaces**: Actualiza los enlaces de los botones en los componentes correspondientes

## 📄 Licencia

Este proyecto está bajo la licencia MIT.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o pull request para sugerencias y mejoras.

---

**Desarrollado con ❤️ para Opiron**
