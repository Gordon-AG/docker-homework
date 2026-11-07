# Домашнее задание: Запуск Java-приложения с PostgreSQL в Docker

## Описание проекта
Проект представляет собой связку Java-приложения (`db-api.jar`) и реляционной СУБД PostgreSQL, развернутой через Docker Compose.

## Инструкция по запуску

1. Запустите контейнер с базой данных PostgreSQL:
   ```bash
   docker compose up -d
   ```

2. Убедитесь, что база данных готова к работе (статус `Up` в `docker ps`).

3. Запустите Java-приложение:
   ```bash
   java -jar db-api.jar
   ```

## Скриншот работы приложения
Ниже представлен скриншоты успешного ответа приложения при обращении к базе данных:
1. Скриншот запуска приложения:
<img width="631" height="261" alt="image" src="https://github.com/user-attachments/assets/5d695352-b48f-4a17-bc4e-ec745f27d873" />



2. Скриншот ответа:
<img width="605" height="460" alt="image" src="https://github.com/user-attachments/assets/d2c367df-1d7c-4e64-b4b7-a7e092046643" />

