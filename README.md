# AMAU Project

Bienvenido al proyecto AMAU. Este sistema integra un frontend de React con un backend de Node.js y Express para gestionar reservas de turnos para distintos horarios de desayuno.

## Tabla de Contenidos

- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Características](#características)
- [Contribuir](#contribuir)
- [Licencia](#licencia)

## Instalación

### Instalar dependencias del backend:

`cd AMAU
npm install`

### Instalar dependencias del frontend:

`cd client
npm install`

## Uso

### Iniciar el Backend

`cd AMAU
node server.js`

### Iniciar el Frontend

En otro terminal:
`cd client
npm start`

### Acceso al Panel de Administración y Formulario de reserva

Dirígete a > http://localhost:3001/admin para acceder al panel de administración.

Dirígete a > http://localhost:3001/ para acceder al formulario de reserva.

## Estructura del Proyecto

AMAU/
├── client/                 # Aplicación frontend de React
├── server/                 # Aplicación backend de Node.js y Express
├── README.md               # Documentación del proyecto
└── .gitignore              # Archivos y directorios ignorados por Git

## Características

**Frontend:** React, SweetAlert2 para alertas.

**Backend**: Node.js, Express, MongoDB.

**Autenticación**: Passport.js(a implementar).

**Validación** de Usuarios: Nombres y apellidos normalizados.

**Reportes**: Reportes diarios y por turnos.

## Contribuir

- Haz un fork del repositorio.

- Crea una nueva rama (git checkout -b feature/nueva-caracteristica).

- Realiza los cambios necesarios y haz commit (git commit -m 'Agregar nueva característica').

- Sube tus cambios (git push origin feature/nueva-caracteristica).

- Abre un Pull Request.

## Licencia

Este proyecto está bajo la licencia MIT.

### Prerrequisitos

- Node.js (versión X.X.X)
- npm (versión X.X.X)

### Clonar el Repositorio

```powershell
git clone https://github.com/JuanGelabert/AMAU-Desayuno.git
cd AMAU
