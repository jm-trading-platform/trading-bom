# Trading BOM

Bill Of Materials corporativo.

## Objetivo

Centralizar versiones de dependencias utilizadas
por todos los microservicios.

## Tecnologías

- Java 21
- Spring Boot
- PostgreSQL
- Kafka
- Redis
- Flyway
- Lombok
- MapStruct
- Testcontainers

## Uso

```xml
<dependencyManagement>

    <dependencies>

        <dependency>
            <groupId>com.jmtrading</groupId>
            <artifactId>trading-bom</artifactId>
            <version>1.0.0</version>
            <type>pom</type>
            <scope>import</scope>

        </dependency>

    </dependencies>

</dependencyManagement>
