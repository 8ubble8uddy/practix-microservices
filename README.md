## PRACTIX

[![movies-admin-panel](https://github.com/8ubble8uddy/movies-admin-panel/workflows/movies-admin-panel/badge.svg
)](https://github.com/8ubble8uddy/movies-admin-panel/actions/workflows/main.yml)
[![sqlite-to-postgres](https://github.com/8ubble8uddy/sqlite-to-postgres/workflows/sqlite-to-postgres/badge.svg
)](https://github.com/8ubble8uddy/sqlite-to-postgres/actions/workflows/main.yml)
[![postgres-to-elastic](https://github.com/8ubble8uddy/postgres-to-elastic/workflows/postgres-to-elastic/badge.svg
)](https://github.com/8ubble8uddy/postgres-to-elastic/actions/workflows/main.yml)
[![movies-async-api](https://github.com/8ubble8uddy/movies-async-api/workflows/movies-async-api/badge.svg
)](https://github.com/8ubble8uddy/movies-async-api/actions/workflows/main.yml)
[![movies-auth](https://github.com/8ubble8uddy/movies-auth/workflows/movies-auth/badge.svg
)](https://github.com/8ubble8uddy/movies-auth/actions/workflows/main.yml)
[![kafka-to-clickhouse](https://github.com/8ubble8uddy/kafka-to-clickhouse/workflows/kafka-to-clickhouse/badge.svg
)](https://github.com/8ubble8uddy/kafka-to-clickhouse/actions/workflows/main.yml)
[![movies-ugc](https://github.com/8ubble8uddy/movies-ugc/workflows/movies-ugc/badge.svg
)](https://github.com/8ubble8uddy/movies-ugc/actions/workflows/main.yml)
[![movies-notifications](https://github.com/8ubble8uddy/movies-notifications/workflows/movies-notifications/badge.svg
)](https://github.com/8ubble8uddy/movies-notifications/actions/workflows/main.yml)

<kbd><img width="400" src="https://pictures.s3.yandex.net/resources/00_welcome_content_images_S1_1_Practix_1603713438.jpg"></kbd>
<kbd><img width="400" src="https://pictures.s3.yandex.net/resources/00_welcome_content_images_S1_3_Practix_1603713448.jpg"></kbd>

### **Описание**

[PRACTIX](https://github.com/8ubble8uddy/practix-microservices) — это микросервисы для сайта с онлайн-кинотеатром:
- [Панель администратора](https://github.com/8ubble8uddy/movies-admin-panel) на фреймворке Django
- [Загрузка данных](https://github.com/8ubble8uddy/sqlite-to-postgres) в базу данных PostgreSQL
- [Полнотекстовый поиск](https://github.com/8ubble8uddy/postgres-to-elastic) с поисковым движком Elasticsearch
- [Асинхронный API](https://github.com/8ubble8uddy/movies-async-api) на фреймворке FastAPI
- [Авторизация пользователей](https://github.com/8ubble8uddy/movies-auth) на фреймворке Flask
- [ETL-система для аналитиков](https://github.com/8ubble8uddy/kafka-to-clickhouse) через брокер сообщений Kafka
- [Пользовательский контент](https://github.com/8ubble8uddy/movies-ugc) c помощью NoSQL базы данных MongoDB
- [Система нотификаций](https://github.com/8ubble8uddy/movies-notifications) в связке Django + FastAPI + Faust

### **Технологии**

```Python``` ```FastAPI``` ```Django``` ```Flask``` ```PostgreSQL``` ```Elasticsearch``` ```Redis``` ```SQLite``` ```MongoDB``` ```Kafka``` ```PySpark``` ```Clickhouse``` ```Logstash``` ```NGINX``` ```Docker```

### **Как запустить проект:**

Клонировать репозиторий и перейти внутри него в директорию ```/infra```:
```
git clone https://github.com/8ubble8uddy/practix-microservices.git
```
```
cd practix-microservices/infra/
```

Развернуть и запустить проект в контейнерах:
```
docker-compose up
```

Ознакомиться с проектом можно по следующим ссылкам:

| Адрес | Описание |
| :------ | :------ |
| [/admin](http://127.0.0.1/admin) | _Панель управления фильмами_ |
| [/movies](http://127.0.0.1/movies) | _Документация API поиска фильмов_ |
| [/auth](http://127.0.0.1/auth) | _Документация API авторизации пользователей_ |
| [/ugc](http://127.0.0.1/ugc) | _Документация API пользовательского контента_  |
| [/notifications](http://127.0.0.1/notifications) | _Панель управления уведомлениями_ |

### Автор: Герман Сизов