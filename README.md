# Microservices-Spring

Este proyecto consiste en un sistema de e-commerce compuesto por microservicios y una interfaz frontend, utilizando Docker Compose para su despliegue.

## Componentes del sistema

- **test-db**: Contenedor MySQL para la base de datos
- **c-api-categories**: Microservicio para gestión de categorías (puerto 8082)
- **c-api-products**: Microservicio para gestión de productos (puerto 8081)
- **c-front-api**: Frontend de la aplicación (puerto 8085)

## Componentes del sistema

 ```bash
 docker-compose up -d
 ```
Esperar algun tiempo en que se levante todo


###Acceso a la aplicación

Al levantar la aplicación, se podrá evidenciar su funcionalidad a través de las siguientes rutas:
    Frontend: http://localhost:8085
    API Productos: http://localhost:8081/api/products
    API Categorías: http://localhost:8082/api/categories

