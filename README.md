# API REST - GESTIÓN DE USUARIOS - Práctica 6.3

Esto es una API REST que sirve para gestionar usuarios mediante operaciones: CRUD

## Características de la app

Se trata de un proyecto sencillo que implementa un API de gestión de usuarios. El API constará de dos partes bien diferenciadas.

# Frontend
- Servidor Nginx, que es muy eficiente sirviendo páginas estáticas. Ejecutará todo el código HTML, CSS y JS del proyecto, con las validaciones oportunas

# Backend
- Entorno de ejecución Node.Js, que controlará la lógica de negocio, recibiendo la información desde el formulario del frontal y actualizando la base de datos simulada (fichero JSON).

# Fichero docker-compose.yml
- Backend: Se indica que se va a construir (hará el build) desde el directorio “backend”, que contiene un archivo Dockerfile con las sentencias necesarias para descargar la imagen de Node desde DockerHub.

- Frontend: Se indica que se descargará una imagen de DockerHub con la última versión de Nginx, que es quien servirá la parte estática de la aplicación.