Тестовое задание №2 Int-4 для стажировки PT-START-2024.2

Сборка и запуск контейнера:
docker build -t pt34_2 .
docker run -d -p 8080:8080 pt34_2

Обращение на адрес http://<ip_сервера>:8080/healthz вызывает GET запрос, который возращает строку с кодом "200 OK"
