# 🚀 API REST con Spring Boot

API RESTful desarrollada con **Spring Boot 3** que implementa operaciones CRUD completas con buenas prácticas: DTOs, mapeo con MapStruct, validaciones, auditoría de cambios con Envers y documentación automática con Swagger. Containerizada con Docker.

## 🛠️ Tecnologías

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![H2](https://img.shields.io/badge/H2-004088?style=for-the-badge&logo=h2&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

**Stack completo:** Spring Boot 3 · Spring Data JPA · H2 · Hibernate Envers · MapStruct · Lombok · Swagger/OpenAPI · Docker · Gradle

## 📋 Funcionalidades

- CRUD completo via endpoints REST
- **DTOs** con mapeo automático usando MapStruct
- **Validaciones** con Spring Boot Validation (`@Valid`, `@NotNull`, etc.)
- **Auditoría** de cambios con Hibernate Envers
- **Documentación interactiva** con Swagger UI
- Base de datos embebida H2 (configurable)
- Containerización con Docker

## 🚀 Cómo ejecutar

### Con Docker
```bash
git clone https://github.com/MannMatias/spring-boot-rest-api
cd TP-5
docker build -t tp5-api .
docker run -p 8080:8080 tp5-api
```

### Sin Docker
**Requisitos:** Java 17, Gradle

```bash
git clone https://github.com/MannMatias/spring-boot-rest-api
cd TP-5
./gradlew bootRun
```

La API estará disponible en `http://localhost:8080`

### 📖 Documentación Swagger
Una vez levantada la aplicación, acceder a:
```
http://localhost:8080/swagger-ui/index.html
```

## 📚 Contexto

Proyecto desarrollado para la materia **Desarrollo de Software** — UTN FRM.
