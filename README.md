# 🚀 SpaceX Launches - Curso Astro Dev

Proyecto realizado siguiendo el curso de Astro de [midudev](https://midu.dev), mostrando los lanzamientos de SpaceX con una interfaz moderna y responsiva.

## 🚀 Demo en producción

Puedes ver el proyecto desplegado en Vercel aquí:  
[https://curso-astro-spacex.vercel.app/](https://curso-astro-spacex.vercel.app/)

## ✨ Descripción

Esta aplicación web permite consultar información sobre los lanzamientos de SpaceX, mostrando detalles, imágenes y el estado de cada misión. Utiliza [Astro](https://astro.build/) como framework principal y [TailwindCSS](https://tailwindcss.com/) para los estilos.

## 📁 Estructura del Proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   ├── services/
│   ├── styles/
│   └── types/
├── .astro/
├── .vscode/
├── package.json
├── astro.config.mjs
├── tsconfig.json
└── README.md
```

## 🛠️ Instalación y uso

1. Instala las dependencias:

   ```sh
   npm install
   ```

2. Inicia el servidor de desarrollo:

   ```sh
   npm run dev
   ```

3. Accede a [http://localhost:4321](http://localhost:4321) en tu navegador.

## 🧩 Principales archivos y carpetas

- **src/components/**: Componentes reutilizables como [`Header.astro`](src/components/Header.astro), [`CardLaunch.astro`](src/components/CardLaunch.astro), [`Launches.astro`](src/components/Launches.astro).
- **src/pages/**: Páginas principales del sitio, incluyendo [`index.astro`](src/pages/index.astro) y rutas dinámicas como [`launch/[id].astro`](src/pages/launch/[id].astro).
- **src/services/**: Lógica para consumir la API de SpaceX, ver [`spacex.ts`](src/services/spacex.ts).
- **src/layouts/**: Layout general del sitio, ver [`Layout.astro`](src/layouts/Layout.astro).
- **src/styles/**: Estilos globales con Tailwind, ver [`global.css`](src/styles/global.css).
- **src/types/**: Tipos TypeScript para la API, ver [`api.ts`](src/types/api.ts).

## 🧑‍💻 Tecnologías utilizadas

- Astro
- TailwindCSS
- TypeScript

## 📝 Créditos

Este proyecto fue realizado siguiendo el curso de [midudev](https://midu.dev) y usando la API pública de [SpaceX](https://github.com/r-spacex/SpaceX-API).

## 📄 Licencia

MIT

---

> Si te gustó el proyecto, puedes seguir a [midudev](https://midu.dev) para más
