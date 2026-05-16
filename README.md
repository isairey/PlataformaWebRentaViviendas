<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/1046/1046857.png" />

# 🏠 Online House Renting System

### Plataforma web de renta y administración de viviendas 🚀

<p align="center">
  <b>Online House Renting System</b> es una plataforma desarrollada para conectar propietarios, clientes y usuarios interesados en alquilar viviendas mediante un sistema moderno, dinámico y centralizado.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HouseRental-WebPlatform-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-FullStack-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Academic-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Online House Renting System** es un sistema web orientado a la administración y búsqueda de viviendas en renta, permitiendo a propietarios publicar inmuebles y a clientes encontrar propiedades de acuerdo con sus necesidades.

El sistema fue diseñado para:

- 🏠 Gestionar propiedades
- 👥 Administrar usuarios
- 📍 Publicar viviendas
- 📅 Controlar rentas
- 🔍 Buscar propiedades
- 📊 Gestionar información inmobiliaria
- 🔐 Administrar accesos
- 🌐 Facilitar el proceso de alquiler

---

# ✨ Características

## 🏘️ Gestión de propiedades

- 🏠 Registro de viviendas
- 📍 Gestión de ubicación
- 🖼️ Carga de imágenes
- 💰 Administración de precios
- 📋 Información detallada

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- ⚡ Activación y desactivación
- 📊 Administración centralizada

---

## 🔍 Sistema de búsqueda

- 📍 Búsqueda por ubicación
- 💰 Filtrado por precio
- 🏘️ Clasificación de propiedades
- ⚡ Resultados dinámicos
- 📋 Información detallada

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 👥 Gestión de usuarios
- 🏠 Administración de propiedades
- 📅 Supervisión del sistema
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 🏠 Owner Module

Este módulo es utilizado por los propietarios de inmuebles que desean publicar propiedades para renta.

### Funcionalidades:

- ➕ Registro de propietarios
- 🏠 Publicación de viviendas
- 🖼️ Subida de imágenes
- 📍 Gestión de ubicación
- 💰 Configuración de precios
- 📋 Administración de propiedades

---

## 🛠️ Client Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🔐 Activar y desactivar cuentas
- 🏠 Supervisar propiedades
- 📊 Control administrativo
- ⚡ Moderación del sistema

---

## 👤 Customer Module

Este módulo es utilizado por usuarios que buscan propiedades en renta.

### Funcionalidades:

- 🔍 Buscar viviendas
- 📋 Consultar detalles
- 📅 Ver disponibilidad
- 📞 Contactar propietarios
- 🏘️ Explorar inmuebles

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js" />
</p>

- HTML5
- CSS3
- Bootstrap
- JavaScript

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP
- CRUD System
- Gestión de sesiones
- Arquitectura web

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia de datos
- Gestión inmobiliaria

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- XAMPP / WAMP

---

# 📂 Estructura del proyecto

```bash
OnlineHouseRentingSystem/
│
├── admin/                    # Panel administrativo
├── owner/                    # Módulo propietario
├── customer/                 # Módulo cliente
├── assets/                   # Recursos frontend
├── database/                 # Scripts SQL
├── uploads/                  # Imágenes de propiedades
├── includes/                 # Configuración y conexión
├── index.php                 # Página principal
├── login.php                 # Inicio de sesión
├── register.php              # Registro de usuarios
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 7+
- MySQL
- Apache
- XAMPP / WAMP
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/OnlineHouseRentingSystem.git
```

---

## 2️⃣ Mover archivos

Copiar proyecto hacia:

```bash
xampp/htdocs/OnlineHouseRentingSystem/
```

---

## 3️⃣ Crear base de datos

Crear base:

```bash
house_rental_system
```

---

## 4️⃣ Importar SQL

Importar:

```bash
database/house_rental_system.sql
```

---

## 5️⃣ Configurar conexión

Editar:

```bash
includes/config.php
```

Agregar:

```php
define('DB_HOST','localhost');
define('DB_USER','root');
define('DB_PASS','');
define('DB_NAME','house_rental_system');
```

---

## 6️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/OnlineHouseRentingSystem/
```

---

# 📊 Funcionalidades principales

## 🏠 Gestión inmobiliaria

- Publicación de propiedades
- Administración de inmuebles
- Gestión de imágenes
- Control de disponibilidad

---

## 👥 Administración de usuarios

- Registro y autenticación
- Activación de cuentas
- Gestión de perfiles
- Roles administrativos

---

## 🔍 Búsqueda avanzada

- Filtros dinámicos
- Resultados rápidos
- Información detallada
- Navegación intuitiva

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 🏠 Página principal
![Home](https://user-images.githubusercontent.com/56467741/93248761-4e3f9e00-f75e-11ea-8cbf-055d849df806.png)

### 🔐 Inicio de sesión
![Login](https://user-images.githubusercontent.com/56467741/93248558-fef96d80-f75d-11ea-855b-8460e9083e59.png)

### 🏘️ Listado de propiedades
![Properties](https://user-images.githubusercontent.com/56467741/93248697-3536ed00-f75e-11ea-87aa-40ad40a658a3.png)

### 📋 Detalles de vivienda
![Details](https://user-images.githubusercontent.com/56467741/93248638-1c2e3c00-f75e-11ea-81e0-bec24e00fdf9.png)

### 👥 Gestión administrativa
![Admin](https://user-images.githubusercontent.com/56467741/93248662-2819fe00-f75e-11ea-88a3-862bfce5bbb8.png)

### 📊 Dashboard del sistema
![Dashboard](https://user-images.githubusercontent.com/56467741/93248602-0fa9e380-f75e-11ea-890b-d636b25e6b45.png)

### 🏠 Publicación de propiedades
![Publish](https://user-images.githubusercontent.com/56467741/93248632-18021e80-f75e-11ea-948e-05d7ab5462b6.png)

### 🔍 Búsqueda avanzada
![Search](https://user-images.githubusercontent.com/56467741/93248682-2fd9a280-f75e-11ea-99de-f98087d0e29c.png)

### 📅 Gestión de rentas
![Rent](https://user-images.githubusercontent.com/56467741/93248729-4253dc00-f75e-11ea-9f5a-42a9ba90602b.png)

### 📄 Información del cliente
![Customer](https://user-images.githubusercontent.com/56467741/93248778-5566ac00-f75e-11ea-953d-927b88d2c887.png)

### ⚙️ Configuración del sistema
![Settings](https://user-images.githubusercontent.com/56467741/93248795-5a2b6000-f75e-11ea-91cb-67f1e152be10.png)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web full stack
- Gestión inmobiliaria
- Bases de datos relacionales
- CRUD administrativos
- Sistemas de autenticación
- Arquitectura web
- Automatización de procesos

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Pagos electrónicos
- 📊 Dashboard avanzado
- 🤖 Recomendaciones inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por plataformas inmobiliarias, sistemas administrativos y arquitectura web moderna 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT orientado al aprendizaje y administración de sistemas inmobiliarios.

---

<div align="center">

### 🏠 Online House Renting System — administración inteligente de propiedades y alquileres 🚀

</div>
