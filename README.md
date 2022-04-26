[![Tests](https://github.com/SilentVampR/express-mesto-gha/actions/workflows/tests-13-sprint.yml/badge.svg)](https://github.com/SilentVampR/express-mesto-gha/actions/workflows/tests-13-sprint.yml) [![Tests](https://github.com/SilentVampR/express-mesto-gha/actions/workflows/tests-14-sprint.yml/badge.svg)](https://github.com/SilentVampR/express-mesto-gha/actions/workflows/tests-14-sprint.yml)
# Проект Mesto фронтенд + бэкенд

В этот раз мы создаем серверную часть для проекта Mesto и подключаем базу данных MongoDB

На данный момент реализованы маршруты и функционал для получения списка пользователей, списка карточек, добавление пользователя, редактирование пользовательских данных, удаление карточек и постановка/снаятие лайков

Все данные хранятся в соответвующие коллекции базы данных `mestodb` - `users` и `cards`

## Основные директории проекта

`/routes` — папка с файлами роутера  
`/controllers` — папка с файлами контроллеров пользователя и карточки   
`/models` — папка с файлами описания схем пользователя и карточки  
 

## Запуск проекта

`npm run start` — запускает сервер
`npm run dev` — запускает сервер с hot-reload
