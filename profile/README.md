# AcerrinLab

## Proyecto: Plataforma de Modelado y Gestión de Muebles

Este repositorio contiene el código y la documentación del proyecto desarrollado por la organización AcerrinLab para la Solar Train Hackathon de jujuy.dev.

## Descripción del Proyecto

Desarrollamos una aplicación orientada a democratizar y facilitar el diseño y construcción de muebles. La plataforma permite a los usuarios modelar muebles (inicialmente en madera), evaluar medidas precisas y visualizar el resultado en sus propios espacios físicos. 

A partir del diseño, el sistema genera automáticamente un cálculo exacto de materiales (cantidad de madera, clavos, tornillos y litros de pintura/barniz) y ofrece dos vías de resolución:
1. Hazlo tú mismo: El usuario puede exportar los planos y la lista de materiales para ejecutar el proyecto por su cuenta.
2. Servicio de terceros: La plataforma conecta el proyecto validado con el ecosistema local de carpinterías para que lleven a cabo la realización del mueble.

## Arquitectura y Stack Tecnológico

Para garantizar una entrega rápida que permita priorizar la tracción del producto antes de la fecha límite (13 de noviembre), optamos por una arquitectura de Monolito Modular. Esta decisión técnica nos permite mantener la simplicidad de despliegue sin sacrificar la separación de dominios (clientes, cálculo, proveedores).

* Backend: Java 25, Spring Boot 3.x, Spring Modulith.
* Base de Datos y ORM: MySQL, JPA/Hibernate.
* Infraestructura Local: Docker y Docker Compose.
* Frontend (Proyectado): Framework web moderno con integración 3D/AR (React Three Fiber, Google model-viewer).

## Organización y Equipo

AcerrinLab está compuesto por:
* Maximo Acosta Gloss
* José Manuel Fernández

## Licencia y Estado

Proyecto en fase de desarrollo intensivo (MVP).
