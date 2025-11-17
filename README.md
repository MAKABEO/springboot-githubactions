# spring-boot-github-actions-demo

Ejemplo de aplicación Spring Boot + Maven + JaCoCo + GitHub Actions.

## Requisitos

- Java 17
- Maven 3.8+

## Ejecutar localmente

```bash
mvn spring-boot:run
```

Luego abre: http://localhost:8080/hello

## Tests y cobertura

```bash
mvn clean test
```

El reporte de JaCoCo se genera en: `target/site/jacoco/index.html`.

## GitHub Actions

Workflows:

- `.github/workflows/ci-maven.yml`: build/test básico.
- `.github/workflows/ci-coverage.yml`: build/test + reporte de cobertura como artifact.
