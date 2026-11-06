## 💥 Trabajo Práctico Épico y Final
### 🧠 Fullstack MERN

### 🎯 Objetivo General
Desarrollar una aplicación web fullstack que combine autenticación, administración de perfiles, consumo de APIs externas y un flujo de uso realista. El enfoque debe estar en la **calidad del código, la coherencia del diseño, la experiencia del usuario y la cobertura de funcionalidades básicas y avanzadas**.

---

## 🧱 Requisitos Generales

### ✅ Tecnologías obligatorias
- **Frontend:** React + Vite + TailwindCSS v4
- **Backend:** Node.js + Express + MongoDB
- **Comunicación entre front y back:** Axios/Fetch + Auth Token (JWT)
<!-- - **Herramientas extra:** react-hook-form, SweetAlert2, Toastify, React Router, LocalStorage, etc. -->

> 🔑 **El `.env` NO se sube al repositorio.** A diferencia de los TPs anteriores, ahora sí hay datos sensibles (la conexión a la base de datos y el `JWT_SECRET`), y los repos son públicos. Va en el `.gitignore`, y se deja un `.env.example` sin valores reales (o vacíos). El `node_modules` tampoco se sube, como siempre.

> 📦 **React Router:** se usa el paquete **`react-router`**, no `react-router-dom`. Si en algún tutorial o en la clase grabada de Auth ven `react-router-dom`, es de una versión anterior: los imports se hacen desde `react-router`.

### 🎬 Proyecto sugerido: Nodo Cine (sugerimos... pero se **valora su creatividad** al elegir **otra temática** ✨)
Una plataforma tipo "mini Netflix" donde un usuario puede:
- Crear perfiles (como Netflix: perfil adulto, niño, etc.).
- Ver un catálogo de películas.
- Agregar películas a su lista personal ("Watchlist").
- Filtrar o restringir películas según edad del perfil.

---

## 🧑‍💻 Funcionalidades obligatorias — Backend

### 🔧 Estructura
- CRUD completo de al menos 3 entidades
- Uso de Mongoose
- Autenticación con JWT
- Roles con distintas capacidades
- Validaciones en los endpoints
- Endpoints seguros y protegidos según permisos del usuario
- Al menos dos búsquedas o filtros avanzados
- Paginado desde servidor en al menos una entidad **(Opcional ✨)**
- Consumo de una API externa (puede ser para obtener ratings, trailers, datos de películas...)

---

## 💻 Funcionalidades obligatorias — Frontend

### 👨‍🎤 Funcionalidad
- Login (guardar token)
- Vista principal con selector de perfiles
- Componente para ver catálogo de películas
- Componente de administración de perfiles
- CRUD completo de entidades conectadas al backend
- Watchlist persistente por perfil *(ojo 👁️)*
- Visualización y funcionamiento condicional según el tipo de perfil (ejemplo: niño solo ve contenido apto)
- Rutas protegidas
- Ruteo dinámico
- Formularios (ejemplo: de edición de perfil)
- Páginas controladas por React Router (`react-router`)

### ⚙️ Técnica
- Peticiones con Axios
- Manejo de Hooks: `useState`, `useEffect`, `useContext` **(mínimo 💀)**, custom hooks si desean
- Formularios validados con `react-hook-form` y validaciones **(mejor si son con Zod, opcional ✨)**
- Manejo de errores del backend
- Toastify o SweetAlert2 para notificaciones **(Opcional ✨)**
- Paginado desde el servidor en alguna vista **(Opcional ✨)**
- Theme claro / oscuro en toda la app, para cada componente

---

## 🎨 Diseño
- Interfaz clara, coherente y responsive
- Navegación intuitiva
- Estética cuidada (pueden usar bibliotecas visuales y/o diseñar con Google Stuch si lo desean ✨)
- Consistencia visual entre componentes
- Respetar Leyes de UX

---

## 🎯 Requisitos de Evaluación

### ✅ Obligatorios para aprobar
- Proyecto completo en GitHub (frontend y backend **separados**)
- El backend debe correr correctamente (instrucciones claras en el README)
- El frontend debe ser funcional y demostrar al menos:
  - CRUD funcional
  - Uso real de tokens
  - Rutas protegidas
  - Interfaz visual coherente
- Review individual:
  1. **Presentación del proyecto, como si lo estuvieras vendiendo.** Antes de abrir el código, contame:
     - **De qué se trata y para qué sirve:** qué problema resuelve y para quién.
     - **Cómo llegaste a esa idea y cómo la diseñaste:** qué decisiones tomaste y por qué (los flujos, los endpoints, el modelo de datos).
     - **La app funcionando:** una demo en vivo del recorrido principal, mostrando el producto como lo vería un usuario.

     Se trata de contar tu proyecto con claridad y honestidad, incluyendo lo que quedó afuera del MVP y por qué.
  2. **Defensa técnica.** El estudiante debe poder **explicar y defender cada parte del código que escribió**.
- Aplicación deployada

### ⭐ Bonus
- Exportar reporte de uso (por ejemplo, cuántas veces se vio una película)
- Filtros avanzados
- Integración continua con GitHub Actions
- Diagramas de flujo

---

## 🔓 Libertad creativa
Los alumnos **pueden (✨y se recomienda que lo hagan✨)** proponer su propio proyecto, siempre que cumpla con:
- Las tecnologías obligatorias
- Los requisitos funcionales mencionados
- Un flujo de uso realista con autenticación y distintos tipos de usuario

Ejemplos alternativos posibles:
- Plataforma de cursos online  
- Agenda de turnos con múltiples perfiles  
- Red social básica con perfiles personalizados  
- App para administrar torneos deportivos

---

✨ Que la fuerza los acompañe ✨
