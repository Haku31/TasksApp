

Task List Application
Descripción

Esta es una aplicación de gestión de tareas que consta de un backend en Python utilizando Tornado y un frontend en React. La aplicación permite a los usuarios administrar tareas mediante una API que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar). La aplicación está contenedorizada utilizando Docker para facilitar su despliegue y gestión.

Estructura del Proyecto

backend/: Contiene la implementación del backend.

frontend/: Contiene la implementación del frontend.

docker-compose.yml: Archivo de configuración para Docker Compose.

Requisitos

Docker
Docker Compose

INSTALACION

Clonar el Repositorio

git clone git@github.com:Haku31/tasks.git

cd tasks

Construir y Ejecutar los Contenedores

En la raíz del proyecto, ejecuta:

docker-compose up --build

Esto construirá las imágenes para el backend y el frontend y levantará los contenedores. El backend estará disponible en http://localhost:8888 y el frontend en http://localhost:3000.

Estructura de los Contenedores

Backend

Imagen: my-backend

Contexto de Construcción: ./backend

Puerto Expuesto: 8888

Comando de Inicio: python run.py

Frontend

Imagen: my-frontend

Contexto de Construcción: ./frontend

Puerto Expuesto: 3000

Comando de Inicio: npm start

Desarrollo

Para realizar cambios en el backend o el frontend, modifica los archivos correspondientes en las carpetas backend/ o frontend/. Luego, reconstruye y reinicia los contenedores con:

docker-compose up --build

Contribución

Si deseas contribuir al proyecto, por favor sigue estos pasos:


Haz un fork del repositorio.

Crea una rama para tu característica o corrección.

Realiza tus cambios y realiza pruebas.

Envía un pull request con una descripción clara de los cambios.

Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.


Contacto

Si tienes alguna pregunta o comentario, no dudes en contactar a barretojhonalex@gmail.com.

