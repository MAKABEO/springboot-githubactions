# spring-boot-github-actions-demo

Pequeño ejemplo de aplicación Spring Boot + Maven con un workflow de GitHub Actions.

## Requisitos

- Java 17
- Maven 3.8+

## Ejecutar localmente

```bash
mvn spring-boot:run
```

Luego abre: http://localhost:8080/hello

## GitHub Actions

El workflow se encuentra en `.github/workflows/ci-maven.yml` y se ejecuta en cada `push` y `pull_request` a la rama `main`.
