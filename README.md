# Gestión Constructora

Aplicación web para la gestión de una empresa de construcción.

Permite administrar clientes, equipos, movimientos, operarios y estados mediante una API REST y una interfaz web.

## Funcionalidades

* Gestión de clientes
* Gestión de equipos
* Gestión de operarios
* Gestión de movimientos
* Gestión de estados
* Autenticación de usuarios
* API REST

## Tecnologías

* C# / .NET 8
* ASP.NET Core
* Entity Framework Core
* SQL Server
* Blazor
* HTML / CSS / JavaScript
* Swagger
* Git / GitHub

## Arquitectura

El proyecto está organizado en capas:

* **Empresa.Domain**: entidades y reglas del dominio.
* **Empresa.Application**: lógica de aplicación y casos de uso.
* **Empresa.Infrastructure**: acceso a datos y servicios de infraestructura.
* **Empresa.API**: API REST.
* **Empresa.Web**: aplicación web.

## Requisitos

* .NET 8 SDK
* SQL Server
* Visual Studio 2022 o compatible

## Configuración

1. Clonar el repositorio.
2. Configurar la cadena de conexión a SQL Server en la configuración de la aplicación.
3. Ejecutar el proyecto.
4. La documentación de la API está disponible mediante Swagger.

## Estado del proyecto

Proyecto en desarrollo, utilizado como aplicación de gestión para una empresa constructora.
