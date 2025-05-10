# 📚 React Courses App

Esta es una aplicación de ejemplo desarrollada en **React** que muestra una lista de cursos usando **React Query**, **React Lazy**, y **paginación** con soporte para carga diferida (`<Suspense />`). Los datos se obtienen desde un archivo local JSON simulado.

## 🚀 Características

- Visualización de cursos
- Paginación simple
- Carga de componentes con `React.lazy` y `Suspense`
- Manejo de estados de carga y error con `@tanstack/react-query`
- Código modular y tipado con TypeScript

## 📁 Estructura de Carpetas

```plaintext
/public
└── api
    └── course.json         # Fuente de datos simulada

/src
├── components
│   └── CourseList.tsx      # Componente para renderizar 

cursos
├── hooks
│   └── useCourses.ts       # 

Hook personalizado que usa React Query
├── App.tsx                 # 

Componente principal
└── main.tsx                # Punto de entrada

```

## 🧩 Tecnologías Usadas
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/React-3178C6?style=flat&logo=react&logoColor=white">

## 🛠️ Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/deivispuertas/react-tanstack-query.git

# 2. Entrar al directorio
cd react-tanstack-query

# 3. Instalar dependencias
npm install

# 4. Ejecutar el servidor local
npm run dev
