# Sistema de Autoevaluación Docente

Aplicación web desarrollada para gestionar el proceso de autoevaluación docente del programa de Ingeniería de Sistemas de la Universidad del Cauca.

El sistema permite centralizar información relacionada con docentes, usuarios, formularios y procesos de evaluación, facilitando la administración de datos y el seguimiento del proceso desde una plataforma web.

---

## Objetivo del proyecto

Construir una aplicación web fullstack para apoyar la gestión del proceso de autoevaluación docente, integrando frontend, backend, autenticación, consumo de APIs REST y persistencia de datos relacionales.

---

## Características principales

* Gestión de usuarios y autenticación.
* Interfaz web responsive para la administración del proceso.
* Consumo de APIs REST desde el frontend.
* Backend estructurado en capas.
* Gestión de datos mediante Sequelize ORM.
* Uso de TypeScript en frontend y backend.
* Pruebas unitarias en frontend con Karma y Jasmine.

---

## Tecnologías utilizadas

### Frontend

* Angular 17
* TypeScript
* Angular Material
* HTML
* CSS
* Karma
* Jasmine

### Backend

* Node.js
* Express.js
* TypeScript
* Sequelize
* MySQL
* JWT
* bcrypt
* dotenv
* Nodemon

---

## Arquitectura general

```txt
Sistema de Autoevaluación Docente
│
├── frontend/
│   └── Aplicación web en Angular
│
└── backend/
    └── API REST con Express, TypeScript y Sequelize
```

### Componentes principales

| Componente    | Descripción                                                                            |
| ------------- | -------------------------------------------------------------------------------------- |
| Frontend      | Aplicación web desarrollada en Angular para la interacción de usuarios con el sistema. |
| Backend       | API REST desarrollada con Node.js, Express y TypeScript.                               |
| Base de datos | Persistencia relacional gestionada mediante Sequelize ORM.                             |
| Autenticación | Protección de rutas y manejo de acceso mediante JWT.                                   |
| Pruebas       | Pruebas unitarias del frontend mediante Karma y Jasmine.                               |

---

## Mi rol en el proyecto

Participé como desarrollador fullstack en el diseño, construcción y documentación del sistema.

Entre mis principales aportes se encuentran:

* Implementación del frontend en Angular 17.
* Organización modular de componentes y servicios.
* Diseño responsive de la interfaz.
* Desarrollo del backend con Express y TypeScript.
* Estructuración del backend en capas.
* Integración de Sequelize ORM para la gestión de datos relacionales.
* Implementación de autenticación mediante JWT.
* Consumo de APIs REST desde el frontend.
* Uso de TypeScript Compiler y Nodemon para el flujo de desarrollo.
* Ejecución de pruebas unitarias con Karma y Jasmine.

---

## Estructura del repositorio

```txt
Sistema-autoevaluacion-docente/
│
├── backend/
│   ├── src/
│   ├── package.json
│   ├── package-lock.json
│   ├── tsconfig.json
│   └── .env.example
│
├── frontend/
│   ├── src/
│   ├── angular.json
│   ├── package.json
│   ├── package-lock.json
│   └── README.md
│
├── README.md
└── .gitignore
```

---

## Instalación y ejecución

### Requisitos previos

Antes de ejecutar el proyecto, asegúrate de tener instalado:

* Node.js
* npm
* Angular CLI
* MySQL

---

## Backend

Ingresar a la carpeta del backend:

```bash
cd backend
```

Instalar dependencias:

```bash
npm install
```

Crear el archivo de variables de entorno a partir del ejemplo:

```bash
cp .env.example .env
```

El archivo `.env` debe contener al menos:

```env
PORT=3000
```

Compilar TypeScript en modo observación:

```bash
npx tsc --watch
```

En otra terminal, ejecutar el servidor con Nodemon:

```bash
npx nodemon ./dist/index.js
```

El backend se ejecuta por defecto en:

```txt
http://localhost:3000
```

---

## Frontend

Desde la raíz del proyecto, ingresar a la carpeta del frontend:

```bash
cd frontend
```

Instalar dependencias:

```bash
npm install
```

Ejecutar servidor de desarrollo:

```bash
npm start
```

El frontend se ejecuta por defecto en:

```txt
http://localhost:4200
```

---

## Comandos útiles

### Backend

```bash
cd backend
npm install
npx tsc --watch
npx nodemon ./dist/index.js
```

### Frontend

```bash
cd frontend
npm install
npm start
npm run build
npm test
```

---

## Estado del proyecto

El proyecto cuenta con una estructura funcional de frontend y backend, integración mediante APIs REST, autenticación y gestión de datos mediante ORM.

---

## Mejoras futuras

* Mejorar la documentación de endpoints.
* Agregar capturas de pantalla del sistema.
* Incluir diagrama de arquitectura.
* Documentar el modelo de datos.
* Crear archivo `docker-compose.yml` para facilitar la ejecución.
* Agregar pruebas automatizadas del backend.
* Separar variables de entorno por ambiente.
* Mejorar la cobertura de pruebas unitarias.

---

## Autor

**Juan Camilo Sarabino Alegría**
Estudiante de Ingeniería de Sistemas | Software Developer | Fullstack Developer

* GitHub: JSarabino
* LinkedIn: linkedin.com/in/jsarabino
