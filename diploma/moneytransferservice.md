# Курсовой проект "Сервис перевода денег"

## Описание проекта 

Разработать приложение - REST-сервис. Сервис должен предоставить интерфейс для перевода денег с одной карты на другую (или счета) по заранее описанной спецификации. Заранее подготовленное веб-приложение (FRONT) должно подключаться к разработанному сервису без доработок и использовать его функционал для перевода денег.

## Требования к приложению

- Сервис должен предоставлять REST интерфейс для интеграции с FRONT
- Сервис должны реализовывать все методы описанные в протоколе:
-- Перевод с карты на карту другого пользователя банка
-- Вывод списка доступных счетов
-- Вывод остатка на счете
- Все начальные значения должны вычитываться из файла
- Все изменения должны записываться в файл

## Требования в реализации

- Приложение разработано с использованием Spring Boot
- Использован сборщик пакетов gradle/maven
- Для запуска используется docker, docker-compose
- Код размещен на github
- Код покрыт unit тестами с использованием mockito
- Добавлены интеграционные тесты с использованием testcontainers
- Шаги реализации:
- Изучить протокол получения и отправки сообщений
- Нарисовать схему приложений
- Описать архитектуру приложения (где хранятся настройки, описать формат хранения данных о картах)
- Создать репозиторий проекта на github
- Написать приложение с использование Spring Boot
- Протестировать приложение с помощью curl/postman
- Написать dockerfile и создать контейнер
- Написать docker-compose скрипт для запуска FRONT и написанного REST-SERVICE
- Протестировать запуск с помощью docker-compose и интеграцию с FRONT
- Написать README.md к проекту, где описать команду запуска, порт и примеры запросов.
- Отправить на проверку