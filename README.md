# Тестирование API PetStore с использованием RestAssured (Java)

Этот проект представляет собой автоматизированное тестирование API для Swagger PetStore — демо-сервиса, часто используемого для обучения QA-инженеров.

## Технологический стек

- **Java 11+**
- **REST Assured** - Отправка HTTP запросов и валидации ответа
- **Maven** - Сборка
- **JUnit 5** - Запуск тестов
- **Lombok** - Сокращение шблонного кода

## В проекте реализованы позитивные и негативные тесты для эндпоинтов раздела Pet

- Добавление питомца (AddPet)
- Обновление данных (UpdatePet)
- Поиск по ID (FindPet)
- Удаление (DeletePet)

## Проверки включают в себя

- Валидацию кодов ответа (200, 404, 400)
- Логирование ответа
- Проверку данных в ответе

# API Testing for PetStore using RestAssured (Java)

This project demonstrates automated API testing for Swagger PetStore, a demo service commonly used for QA training.

## Tech stack:

- Language: Java 11+
- Framework: REST Assured (HTTP requests/assertions)
- Libraries: JUnit 5 (test runner)
- Lombok (POJO simplification)
- Build tool: Maven

## Key features:

- Add a new pet (AddPet),
- Update pet data (UpdatePet),
- Find pet by ID (FindPet),
- Delete pet (DeletePet).

## Validations include:

- HTTP status codes (200, 404, 400)
- Response data checks (e.g., pet name correctness)