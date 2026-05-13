# Sistema de Registro Auth Fullstack
Este proyecto es una aplicación web integral diseñada para gestionar el registro de usuarios, utilizando la base de MongoDB.
Este proyecto integra un frontend dinámico, una API RESTful y una base de datos NoSQL para demostrar el registro dentro de este sistema. 
## Objetivos del Proyecto

- Implementar un sistema de autenticación completo.
- Aplicar arquitectura MERN.
- Conectar frontend y backend mediante API REST.
- Gestionar usuarios en una base de datos MongoDB.
- Implementar flujo de verificación y recuperación de cuentas.
- Aplicar buenas prácticas de organización de proyecto.

###  Estructura del Repositorio
Siguiendo las buenas prácticas de organización, el proyecto se divide en:

°   **Backend**: Servidor desarrollado en Node.js y Express, encargado de la lógica de negocio y la conexión con MongoDB.

°   **Frontend`**: Interfaz de usuario construida en React.js, enfocada en la experiencia del usuario y el consumo de la API.
## Arquitectura

- Frontend: React (Vite)
- Backend: Node + Express
- Base de datos: MongoDB
- Autenticación: JWT
## Tecnologías Utilizadas

## Frontend
- React.js
- Vite
- Axios
- React Router DOM
- CSS

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv
- cors

## Guía de Instalación y Ejecución
Para que el proyecto funcione correctamente , se debe seguir los siguientes pasos:  

## Requisitos Previos
- Node.js
- MongoDB
- npm
  
### 1. Clonar el Proyecto
git clone [https://github.com/mila1213/Backend-Frontend-MongoDB-Registro.git](https://github.com/mila1213/Backend-Frontend-MongoDB-Registro.git)

## Configuración del Backend
### Ingresar a la carpeta 
```bash
cd Frontend
```
### Instalar dependencias 
```bash
npm install
```
### Ejecutar en proyecto
```bash
npm run dev
```

## Variables de entorno
El proyecto requiere un archivo `.env` en la carpeta backend.
### backend/.env
```env
PORT=3000
MONGO_URI=mongodb+srv://ejemplo:<clave>@cluster0.sremjdg.mongodb.net/authdb
JWT_SECRET=clave_super_secreta_para_clase
FRONTEND_URL=http://localhost:5173

EMAIL_USER=ejemplo@gmail.com
EMAIL_PASS=aeioaeioaeioaeio
```

## Configuración del Frontend
### Ingresar a la carpeta 
```bash
cd Frontend
```
### Instalar dependencias 
```bash
npm install
```
### Ejecutar en proyecto
```bash
npm run dev
```

**Es importante que el backend y frontend esten ejecutados simultaneamente**

## Capturas del Sistema 

### **Registro**

<p align="center"><<img width="911" height="527" alt="image" src="https://github.com/user-attachments/assets/a3b2d815-bacb-4200-8ee8-f54f44c64ea4" /></p>

#### **Recuperación de Contraseña**
<p align="center"><img width="953" height="434" alt="image" src="https://github.com/user-attachments/assets/49c567f9-d189-4a5e-9de4-b97a19429a74" /></p>
1. Solicitar la recuperacion de contraseña 
<p align="center"><img width="877" height="502" alt="image" src="https://github.com/user-attachments/assets/34df0855-72a6-4220-88a2-b217308a7847" /></p>
2. Cambiar la contrasea
<img width="914" height="614" alt="image" src="https://github.com/user-attachments/assets/d6a10afd-3310-4292-afea-c820027d775e" /></p>
3. Esperara mensaje de verificacion de la contraseña 
<p align="center"><img width="883" height="525" alt="image" src="https://github.com/user-attachments/assets/e7b623b3-5880-470c-8752-356ddb86df07" /></p>

### **MongoDB**
<p align="center"><img width="1861" height="675" alt="image" src="https://github.com/user-attachments/assets/f3a9482e-2de3-4006-9ac7-dff3118b9ea1" /></p>

### Autor : Camila Bueno
