# SBOM support in Spring Boot and GraalVM Native Image

This repository showcases SBOM support in Oracle GraalVM Native Image and Spring Boot.

Build:

``shell
mvn -Pnative native:compile
```
Run:

```shell
./target/demo
```

Curl the Actuator SBOM endpoint to retrieve the SBOM:

```shell
curl http://localhost:8080/actuator/sbom/native-image
```