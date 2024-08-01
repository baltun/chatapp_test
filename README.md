
## О проекте
Тестовое задание от команды ChatApp
Текст задания находится в файле [Задания](./public/PHP_a.pdf)


## Развертывание проекта
- перейти в папку с проектами
- создать проект: 
  - git clone https://github.com/baltun/chatapp_test.git
- создать .env, копированием из .env.example
  - поменять необходимые значения переменных, чтобы контейнеры из файла docker-compose.yml не конфликтовали
- поднять контейнеры: ./vendor/bin/sail up -d
- загрузить зависимости: ./vendor/bin/sail composer install
- выполнить миграции: ./vendor/bin/sail artisan migrate


## Описание функционала (Инструкция по использованию)



## Описание особенностей реализации приложения
