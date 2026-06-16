# Sudoku Project — API Testing Notes

Repository: https://github.com/Tomaso1420/sudoku-project

## Описание
REST API-приложение для генерации и решения Sudoku с асинхронной обработкой фоновых задач.

## Что можно тестировать
- создание задачи на генерацию Sudoku;
- создание задачи на решение Sudoku;
- получение задачи по id;
- изменение статуса задачи;
- успешную обработку результата;
- ошибочные входные данные;
- работу очереди задач;
- сценарии pending / processing / done / failed.

## Моя роль
Разработчик и тестировщик учебного проекта.

## Стек
Python, FastAPI, PostgreSQL, RabbitMQ, Docker, REST API.
