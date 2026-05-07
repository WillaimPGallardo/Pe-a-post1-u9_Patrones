Productos Service - Laboratorio de Pruebas Unitarias
Descripción

Este proyecto implementa un servicio básico de gestión de productos utilizando Spring Boot. El objetivo principal del laboratorio es aplicar pruebas unitarias con JUnit 5 y Mockito para validar correctamente la lógica de negocio del sistema.

El sistema permite:

Crear productos
Buscar productos por ID
Actualizar stock
Eliminar productos

Además, se implementan validaciones sobre nombre, precio y stock para garantizar integridad de datos.

Estructura del Proyecto
src
 ├── main
 │   └── java
 │       └── com.universidad.productos_service
 │           ├── controller
 │           ├── domain
 │           ├── repository
 │           └── service
 │
 └── test
     └── java
         └── com.universidad.productos_service.service
Funcionalidades
Crear producto

Permite registrar un producto validando:

nombre no vacío
precio mayor a cero
stock no negativo
Buscar producto

Permite consultar un producto utilizando su ID.

Actualizar stock

Permite modificar la cantidad disponible de un producto.

Eliminar producto

Permite eliminar productos existentes del sistema.

Ejecución del Proyecto
Compilar
mvn clean install
Ejecutar aplicación
mvn spring-boot:run
Ejecutar pruebas unitarias
mvn test
Resultados Esperados

Al ejecutar las pruebas correctamente debe aparecer:

BUILD SUCCESS

y:

Failures: 0
Errors: 0
Pruebas Implementadas

El proyecto incluye pruebas para:

creación válida de productos
validación de nombre vacío
validación de precio inválido
validación de stock negativo
búsqueda de productos existentes
búsqueda de productos inexistentes
actualización de stock
eliminación de productos
Principios Aplicados
Separación de responsabilidades
Validación de lógica de negocio
Aislamiento mediante mocks
Testing automatizado
Cobertura de escenarios positivos y negativos
Dependencias Principales
Spring Boot Test

Permite integrar JUnit 5 y herramientas de testing de Spring.

Mockito

Utilizado para crear mocks y aislar dependencias durante las pruebas unitarias.

H2 Database

Base de datos en memoria para pruebas rápidas y aisladas.

<img width="1911" height="1045" alt="image" src="https://github.com/user-attachments/assets/68246d43-35c3-412f-912b-fa71a2d878e9" />
<img width="1104" height="197" alt="image" src="https://github.com/user-attachments/assets/7d6b26eb-b228-483d-b3e9-e054932a1b0c" />
<img width="1089" height="374" alt="image" src="https://github.com/user-attachments/assets/928d81af-4736-4033-bd42-00cc6c8d99b9" />


