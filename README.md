# SOAP Hello World Project

This project demonstrates a simple SOAP web service implemented in PHP. It consists of a server (`soap-server.php`) and a client (`test-soap.php`) that interacts with the server to perform basic SOAP operations. The project is Dockerized to easily deploy and run the application.

## Requirements

- PHP 8.1 or higher
- Docker (for containerization)
- Docker Compose (if using multi-container setup)

## Project Description

This is a basic example of a SOAP web service. The server exposes a `sayHello` function which takes a name and returns a greeting message. The client sends a request to the server and receives a response.

## Technologies Used

- PHP 8.1 (CLI)
- Docker

## Steps to Clone and Run the Project

### 1. Clone the repository

To clone this project, run the following command:

```bash
git clone https://your-repository-url.git
```
2. Run the Project
To run the project, follow these steps:

Without Docker:

Navigate to the project directory:
bash
```bash
cd soap-hello-world
```
Start the PHP embedded server:

```bash
php -S localhost:8000
```
With Docker (Recommended):

Build the Docker image:

```bash
docker build -t soap-server .
```
Run the Docker container:

```bash
docker run -p 8000:8000 soap-server
```
The server will be accessible at http://localhost:8000/soap-server.php.

Docker Hub
For pre-built Docker images, visit the Docker Hub link to pull and run the image.

License
This project is licensed under the MIT License - see the LICENSE file for details.

shell
Copiar código

### **README.md (Español)**

```markdown
# Proyecto SOAP Hello World
```
Este proyecto demuestra un simple servicio web SOAP implementado en PHP. Consiste en un servidor (`soap-server.php`) y un cliente (`test-soap.php`) que interactúa con el servidor para realizar operaciones básicas SOAP. El proyecto está dockerizado para facilitar su despliegue y ejecución.

## Requisitos

- PHP 8.1 o superior
- Docker (para la contenedorización)
- Docker Compose (si usas una configuración con múltiples contenedores)

## Descripción del Proyecto

Este es un ejemplo básico de un servicio web SOAP. El servidor expone una función `sayHello` que toma un nombre y devuelve un mensaje de saludo. El cliente envía una solicitud al servidor y recibe una respuesta.

## Tecnologías Utilizadas

- PHP 8.1 (CLI)
- Docker

## Pasos para Clonar y Ejecutar el Proyecto

### 1. Clonar el repositorio

Para clonar este proyecto, ejecuta el siguiente comando:

```bash
git clone https://your-repository-url.git
```
2. Ejecutar el Proyecto
Para ejecutar el proyecto, sigue estos pasos:

Sin Docker:

Navega al directorio del proyecto:
```bash
cd soap-hello-world

Inicia el servidor PHP embebido:
```bash
php -S localhost:8000
```
Con Docker (Recomendado):

Construye la imagen de Docker:
```bash
docker build -t soap-server .
```
Ejecuta el contenedor de Docker:
```bash
docker run -p 8000:8000 soap-server
```
El servidor será accesible en http://localhost:8000/soap-server.php.

Docker Hub
Para obtener imágenes de Docker preconstruidas, visita el enlace de Docker Hub para descargar y ejecutar la imagen.

Licencia
Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.


### **Descripción de las secciones:**

1. **Project Title & Description**: Explica brevemente de qué trata el proyecto.
2. **Requirements**: Enumera los requisitos principales como PHP, Docker, etc.
3. **Technologies Used**: Menciona las tecnologías utilizadas (en este caso PHP y Docker).
4. **Steps to Clone and Run the Project**: Proporciona instrucciones claras para clonar y ejecutar el proyecto tanto sin Docker como con Docker.
5. **Docker Hub**: Añade un enlace a Docker Hub para descargar imágenes preconstruidas (si corresponde).
6. **License**: Incluye información sobre la licencia del proyecto (si aplica).


