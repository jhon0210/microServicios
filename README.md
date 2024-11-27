# Proyecto NestJS con API Gateway y Microservicios

Este proyecto está basado en **NestJS** y utiliza una arquitectura de **microservicios**. Está compuesto por:

- **API Gateway**: Punto de entrada principal para interactuar con los microservicios.
- **Microservicio de Tareas**: Un microservicio que maneja la lógica relacionada con las tareas.
- **Microservicio de Usuarios**: Un microservicio que maneja la lógica relacionada con los usuarios.
- **RabbitMQ**: Utilizado para la comunicación entre los microservicios.
- **MongoDB**: Base de datos para almacenar datos de usuarios y tareas.

## Requisitos Previos

- **Node.js** (versión recomendada: v16 o superior).
- **RabbitMQ**: Necesitas tener un servidor RabbitMQ corriendo.
- **MongoDB**: Necesitas tener una instancia de MongoDB en funcionamiento o usar una base de datos en la nube como MongoDB Atlas.

## Instalación

### 1. Clonar el repositorio

Primero, clona el repositorio desde GitHub:

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
