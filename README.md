# Full Stack Application - Programación II

## Información del Estudiante

- **Nombre:** Agustín Benavidez
- **Legajo:** 62344

## Descripción del Proyecto

Este proyecto implementa una aplicación full-stack con arquitectura hexagonal en el backend.

### Backend

El backend está desarrollado con Spring Boot utilizando arquitectura hexagonal (también conocida como arquitectura de puertos y adaptadores).

**Estructura del proyecto:**

```
back/hexagonal/
├── src/
│   ├── main/
│   │   ├── java/com/example/hexagonal/
│   │   │   ├── product/
│   │   │   │   ├── domain/           # Capa de dominio
│   │   │   │   │   ├── model/        # Entidades de dominio
│   │   │   │   │   └── ports/        # Interfaces (puertos)
│   │   │   │   ├── application/      # Casos de uso
│   │   │   │   │   └── service/
│   │   │   │   └── infrastructure/   # Adaptadores
│   │   │   │       ├── persistence/  # Persistencia (JPA)
│   │   │   │       └── web/          # Controladores REST
│   │   └── resources/
│   └── test/
└── pom.xml
```

### Tecnologías Utilizadas

- **Java** con Spring Boot
- **Maven** como gestor de dependencias
- **JPA/Hibernate** para persistencia
- **REST API** para la capa web

## Instalación y Ejecución

### Backend

```bash
cd back/hexagonal
./mvnw spring-boot:run
```

## Licencia

Proyecto académico para la materia Programación II.

