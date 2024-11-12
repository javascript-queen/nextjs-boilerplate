# postgres/Dockerfile
FROM postgres:latest

# Копируем скрипт инициализации для создания пользователя и базы данных
COPY init.sql /docker-entrypoint-initdb.d/