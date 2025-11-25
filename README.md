Aplicación Web Moderna con Arquitectura Hexagonal, SOLID y Código Limpio
📌 Descripción del Proyecto

Este proyecto consiste en el diseño y desarrollo de una Aplicación Web Moderna utilizando:

Arquitectura Hexagonal (Ports & Adapters)

Principios SOLID

Código Limpio

Buenas prácticas de refactorización

Backend + Frontend

Frameworks seleccionados por el estudiante

Base de datos opcional (relacional o NoSQL)

La aplicación fue construida como ejemplo académico para demostrar cómo una arquitectura desacoplada permite alta mantenibilidad, escalabilidad y facilidad de pruebas.

🧱 Arquitectura Hexagonal

La arquitectura del proyecto está basada en Hexagonal Architecture, que separa la lógica de negocio del resto de la aplicación mediante:

Dominio → Reglas de negocio puras

Aplicación → Casos de uso

Infraestructura → Adaptadores (HTTP, DB, Frameworks)

Esto permite cambiar frameworks, motores de base de datos o interfaces de usuario sin afectar el núcleo del dominio.

🧩 Tecnologías Usadas
Backend

Lenguaje: Java

Framework: Spring Boot

Estilo: Clean Architecture + SOLID

Gestión de dependencias: Maven

Frontend

HTML, CSS y JavaScript

Arquitectura simple basada en componentes

Puede ser reemplazado por React o Angular sin afectar el dominio

Otros

Git y GitHub

Base de datos opcional (H2, MySQL, MongoDB, etc.)

📁 Estructura del Proyecto
aplicacion-web-hexagonal/
│
├── backend/
│   └── src/main/
│       ├── java/com/empresa/app/
│       │   └── Application.java
│       └── resources/application.properties
│
└── frontend/
    ├── index.html
    ├── styles.css
    └── app.js

📌 Principios SOLID aplicados

S — Responsabilidad Única: Cada clase tiene un único propósito.

O — Abierto/Cerrado: Se permite extensión sin modificar código existente.

L — Sustitución de Liskov: Interfaces claras que permiten reemplazo de implementaciones.

I — Segregación de Interfaces: Interfaces pequeñas, específicas.

D — Inversión de Dependencias: El dominio no depende de frameworks.

🧪 Refactorización aplicada

Simplificación de clases

Desacoplamiento de capas

Eliminación de código repetido

Nombres significativos para clases y métodos

Separación clara entre dominio y tecnología

🚀 Cómo Ejecutar el Proyecto
✔ Backend (Spring Boot)
cd backend
mvn spring-boot:run


El backend abrirá en:
➡ http://localhost:8080

✔ Frontend

Simplemente abre el archivo:

frontend/index.html


O usa un servidor local:

npx serve ./frontend

🧾 Repositorio

Sugerencia para subirlo:

git init
git add .
git commit -m "Aplicación web con arquitectura hexagonal y SOLID"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/aplicacion-web-hexagonal.git
git push -u origin main

📚 Objetivo Académico

Este proyecto demuestra:

La capacidad de diseñar software modular y mantenible

El uso de arquitecturas modernas

La integración entre Backend y Frontend

La aplicación de buenas prácticas de ingenie
