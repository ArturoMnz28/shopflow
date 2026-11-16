# ShopFlow

Tienda online ficticia hecha con microservicios Java que se coordinan por eventos en **Apache Kafka**, con un servicio de pagos que incluye validacion antifraude. Todo el sistema se levanta con Docker Compose.

> Proyecto de aprendizaje y portfolio. Todos los datos son inventados.

## Estado

| Hito | Descripcion | Estado |
| --- | --- | --- |
| 0 | Entorno y repositorio | Hecho |
| 1 | Docker con un primer servicio (`order-service` + MySQL) | Pendiente |
| 2 | Primeros pasos con Kafka | Pendiente |
| 3 | Eventos bien disenados (`common-events`, idempotencia) | Pendiente |
| 4 | Saga de pedido e inventario | Pendiente |
| 5 | Pagos y antifraude | Pendiente |
| 6 | Fiabilidad: outbox, reintentos y DLT | Pendiente |
| 7 | Spring Cloud y Spring Security | Pendiente |
| 8 | Tests y calidad | Pendiente |
| 9 | Observabilidad y CI/CD | Pendiente |
| 10 | Pulido y portfolio | Pendiente |

## Stack previsto

Java 21, Spring Boot 4.1, Maven, Apache Kafka (KRaft), MySQL, Docker y Docker Compose, Spring Security (JWT), Spring Cloud Gateway y Config Server, JUnit, Mockito, Testcontainers, SonarQube, Prometheus y Grafana.

## Requisitos

- JDK 21
- Maven 3.9 o superior (opcional si usas el Maven del IDE)
- Git
- Docker con Docker Compose

Comprueba el entorno:

```bash
java -version
mvn -version
git --version
docker --version
docker compose version
```

## Como arrancarlo

Pendiente: se completara en el hito 1 y siguientes (`docker compose up`).

## Arquitectura

Pendiente: diagrama en `docs/` a partir del hito 4.

## Notas por hito

### Hito 0 · Entorno y repositorio

- Que he aprendido:
- Decisiones que he tomado:
- Problemas que he tenido:
