# Каталог Моих Репозиториев

## Содержание
- [Fullstack-проекты](#fullstack-проекты)
- [Backend-проекты](#backend-проекты)
- [Другое](#другое)

## Fullstack-проекты
### [BookingWebService](https://github.com/pabloeclair/BookingWebService) 
Сайт для бронирования аудиторий. Реализованы два REST API: на `Go` для авторизации и управления пользователями и на `Java` для управления аудиториями и бронированиями. Создан SPA с помощью React. **В процессе разработки.**

**Стек**: Go (REST, net/http, JWT), Java (REST, Spring, ORM), PostgreSQL, React, Docker

## Backend-проекты
### [rest-subscription](https://github.com/pabloeclair/rest-subscription)
REST-сервис для управления онлайн-подписками. Был сделан с целью изучить использование ORM с помощью пакета `gorm`.

**Стек**: Go (REST, net/http, ORM, gorm), PostgreSQL, Docker

### [DockerImageAnalysisService](https://github.com/pabloeclair/DockerImageAnalysisService)
Небольшой REST-сервис на `Go` для получения основной информации об указанном образе на базе `linux/amd`. Для этого взаимодействует с DockerHubAPI.

**Стек**: Go, REST, net/http

### [NoteServiceProtoBuff](https://github.com/pabloeclair/NoteServiceProtoBuff) 
Реализация gRPC-сервера на `Go` для управления заметками с помощью in-memory хранилища и класс gRPC-клиента на `Java`.

**Стек**: Go, gRPC, ProtoBuff, Java

### [FtbQuests-LocalizationKeysGenerator](https://github.com/pabloeclair/FtbQuests-LocalizationKeysGenerator)
В процессе перевода [сборки "Homestead"](#homestead-ru-translation), появилась необходимость изменить изначальный файлы, внедрив в них так называемые "ключи", для удобства перевода, а также для возможности включить квесты на оригинальном языке. Для решения этой проблемы мною был написана программа на `Go`, которая генерирует все необходимые файлы для перевода. **В процессе разработки.**

**Стек**: Go (os, bufio)

## Другое
### [Hackathon_T1_GR](https://github.com/pabloeclair/Hackathon_T1_GR)
Проект на Python хакатона [Импульс Т1](https://impulse.t1.ru/) 2024 по извлечению золотой записи, с помощью которого командой заняли 3-е место. Мое участие заключалось в курировании работы всех участников, код-ревью и в помощи реализации подготовки входных данных.

**Стек**: Python, pandas, argparse

### [homestead-ru-translation](https://github.com/pabloeclair/homestead-ru-translation)
Перевод Homestead - майнкрафт сборки модов. На данный момент основной акцент идет на перевод квестов из мода `ftbquests`.


