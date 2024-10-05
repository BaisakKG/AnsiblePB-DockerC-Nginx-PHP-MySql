# Используем официальный образ MySQL для Alpine
FROM mysql

# Переменные окружения из .env файла
ENV MYSQL_ROOT_PASSWORD=rootpas \
    MYSQL_DATABASE=crud_db \
    MYSQL_USER=crud_user \
    MYSQL_PASSWORD=crud_pas

COPY db/init.sql /docker-entrypoint-initdb.d/

# Экспозируем порт для подключения
EXPOSE 3306

CMD ["mysqld"]

