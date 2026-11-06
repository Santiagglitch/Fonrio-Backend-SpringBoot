# 📦 Fonrio — Backend del Sistema de Gestión de Inventarios

**Fonrio** es un sistema de gestión de inventarios orientado a negocios de tecnología, especialmente a la venta de celulares y accesorios. Fue desarrollado como proyecto de grado del programa de **Análisis y Desarrollo de Software (ADSO) del SENA**.

Este repositorio contiene el **backend desarrollado con Java y Spring Boot**. Su función es ofrecer una **API REST** que recibe las solicitudes de la aplicación web, aplica la lógica del sistema e interactúa con la base de datos.

> 💻 **¿Buscas la interfaz web?** Consulta el [frontend de Fonrio (Laravel y Blade)](https://github.com/Santiagglitch/Sistema-Gestion-Inventario).

## 🚀 Funcionalidades del sistema

La API permite dar soporte a los módulos de:

- **Productos y categorías:** registro, consulta, actualización y organización del inventario de celulares y accesorios.
- **Empleados y roles:** administración de usuarios, roles y estados.
- **Clientes y proveedores:** gestión de la información necesaria para las operaciones comerciales.
- **Compras y ventas:** registro y consulta de movimientos del negocio.
- **Devoluciones:** gestión de devoluciones y sus detalles.
- **Autenticación:** componentes para inicio de sesión y validación de tokens JWT.

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso en el proyecto |
| --- | --- |
| **Java** | Lenguaje principal del backend. |
| **Spring Boot** | Desarrollo y organización de la API REST. |
| **Spring JDBC Template** | Acceso a datos y ejecución de consultas SQL. |
| **MySQL / SQL** | Persistencia de la información del sistema. |
| **JWT** | Autenticación y validación de solicitudes. |
| **Swagger** | Configuración para documentación de la API. |
| **Maven** | Gestión de dependencias y construcción del proyecto. |
| **Git y GitHub** | Control de versiones y trabajo colaborativo. |

## 🏗️ Arquitectura

El backend organiza las responsabilidades en componentes como:

- **Controllers:** reciben y responden solicitudes HTTP.
- **Services:** gestionan las operaciones y reglas de negocio.
- **DTOs:** estructuran la información intercambiada.
- **Autenticación y configuración:** gestionan el acceso y la integración de la aplicación.

El código del backend se encuentra principalmente en `demo/src/main/java/com/example/demo/`.

### Relación entre los repositorios

```text
Usuario
  ↓
Frontend web — PHP / Laravel / Blade
  ↓ solicitudes HTTP
API REST — Java / Spring Boot (este repositorio)
  ↓ consultas SQL
Base de datos — MySQL
```

## 👥 Trabajo colaborativo

Fonrio fue desarrollado por un **equipo de cuatro integrantes** como proyecto académico. Participé en el diseño de la arquitectura de software, la organización de tareas, el desarrollo del proyecto y el uso de Git/GitHub para el control de versiones.

## 🎯 Propósito

Facilitar la administración de productos, inventarios y operaciones comerciales en pequeños negocios de tecnología mediante una solución web organizada y conectada a una API REST.

## 🔗 Repositorios del proyecto

- **Backend (Java + Spring Boot):** [Sistema-Inventario](https://github.com/Santiagglitch/Sistema-Inventario) — este repositorio.
- **Frontend (PHP + Laravel + Blade):** [Sistema-Gestion-Inventario](https://github.com/Santiagglitch/Sistema-Gestion-Inventario).

---

*Proyecto académico del SENA. Este repositorio presenta la parte backend de una solución Full Stack desarrollada en equipo.*
