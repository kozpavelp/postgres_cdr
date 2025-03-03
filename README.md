# Postgres CDR
Этот Docker Compose для поднятия PostgreSQL базы данных и инициализационный скрипт для
создания таблицы CDR (Call Detail Record) для использования в сервере Asterisk.

0. Файл `.env` в корне проекта:
- `POSTGRES_USER`: Имя пользователя PostgreSQL.
- `POSTGRES_PASSWORD`: Пароль пользователя PostgreSQL.
- `POSTGRES_CDR_DB`: Имя базы данных для CDR.


1. Запустить Docker Compose:
    ```sh
    docker compose up -d
    ```
   
2. База данных будет доступна на порту `5433`.

