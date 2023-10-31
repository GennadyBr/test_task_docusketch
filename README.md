# Тестовое задание
ссылка на код ()

## Написать python скрипт, который будет контролировать потребление памяти и генерировать alarm путем отправки http запроса на API.
 
## Создать docker-compose.yml разворачивающий приложение на python с простой реализацией REST API. Решение должно состоять из двух контейнеров:
а) Любая NoSQL DB.

б) Приложение на python, с использованием Flask, которое слушает на порту 8080 и принимает только методы GET, POST, PUT.

в) Создаем значение ключ=значение, изменяем ключ=новое_значение, читаем значение ключа.

г) Вновь созданные объекты должны создаваться, изменяться и читаться из NoSQL DB.


## Запустить проект:
docker compose up --build

запускается ТРИ контейнера
1) MongoDB
2) Flask 
3) приложение для контроля памяти
4) так как не было такого требования, то не стал выносить порты и т.п. в переменные окружения
5) для удобства сделал небольшую HTML страницу

HTML доступна по адресу API 
http://127.0.0.1:8080/
