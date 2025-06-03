# 📦 Achievement Service

## 📄 Описание

Микросервис отвечает за сбор, хранение, а также распределение достижений по пользователям.

## ⚙️ Технологии

### Основа:

- Java 17
- Spring Boot 3.0.6

### Базы:

- PostgreSQL
- Redis
- Liquibase

### Общение микросервисов:

- Kafka
- OpenFeign

### Тестирование:

- JUnit 5
- Mockito
- AssertJ
- Testcontainers

### Прочее:

- Lombok
- MapStruct
- Springdoc OpenAPI
- CI Pipeline (GitHub Actions)
- JaCoCo
- Slf4j
- Docker
- WebClient

## 🔗 Связанные сервисы

- Notification Service – для отправки email/sms/telegram уведомлений о получении достижений
- Analytics Service - для сбора и анализа данных о достижениях
