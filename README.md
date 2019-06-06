# EventService [![Build Status](https://travis-ci.org/ArtemSglv/EventService.svg?branch=master)](https://travis-ci.org/ArtemSglv/EventService)
### Запуск
##### Server Port: 8092
1. Создать БД на сервере PostgreSQL
2. Выполнить `mvn spring-boot:run`
3. Для запуска с dev properties добавить флаг `--spring.profiles.active=dev`
### Swagger
Для доступа к докуметации API запустите сервис и перейдите по: `localhost:port/swagger-ui.html`
