# EventHubDataRest

API REST desarrollada con **Spring Boot** y **Maven** para gestionar información de eventos.  
El proyecto incluye entidades principales (`Event`, `Location`, `TicketType`), repositorios de acceso a datos y recursos de configuración/carga inicial.

## Funcionalidades
- Gestión de eventos.
- Gestión de ubicaciones (locations).
- Gestión de tipos de entrada (ticket types).
- Carga de datos inicial mediante `data.sql`.
- Archivo `endpoints.http` para probar peticiones desde el propio IDE (por ejemplo, IntelliJ o VS Code con extensiones).

## Tecnologías
- Java
- Spring Boot
- Maven (wrapper incluido: `mvnw`, `mvnw.cmd`)
- Persistencia con repositorios (Spring Data)

## Requisitos
- Java 17 (recomendado) o compatible con tu configuración del proyecto.
- Maven (opcional, porque el proyecto incluye Maven Wrapper).

## Cómo ejecutar el proyecto

### Opción A: usando Maven Wrapper (recomendada)
En la raíz del proyecto:

**Windows**
```bash
mvnw.cmd spring-boot:run
