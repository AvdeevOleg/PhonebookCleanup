# Проект "Обработка адресной книги

## Описание проекта

Проект предназначен для приведения в порядок адресной книги, используя регулярные выражения. Основная задача - очистить и отформатировать контакты, а также устранить дублирующиеся записи.

## Структура данных

Данные имеют следующую структуру: lastname, firstname, surname, organization, position, phone, email

## Структура проекта

1. main.py: Основной скрипт для обработки данных адресной книги.
2. phonebook_raw.csv: Исходный файл с данными адресной книги.
3. phonebook.csv: Файл с отформатированными данными после обработки.
4. README.md: Этот файл с описанием проекта.

## Задачи

1. Привести Фамилию, Имя и Отчество в правильные поля.
2. Привести все телефоны в формат +7(999)999-99-99. Если есть добавочный номер, формат будет такой: +7(999)999-99-99 доб.9999.
3. Объединить все дублирующиеся записи о человеке в одну.

## Установка

1. Склонируйте репозиторий: git clone <URL репозитория>
2. Перейдите в папку проекта: cd PhonebookCleanup
3. Запустите `main.py` для выполнения скрипта: main.py

## Как работает скрипт

Скрипт main.py считывает данные из файла phonebook_raw.csv, обрабатывает их, приводит в соответствие требованиям и сохраняет результат в файл phonebook.csv. В исходном файле предполагается, что данные имеют структуру: lastname,firstname,surname,organization,position,phone,email. Скрипт выполняет следующие действия:

1. Преобразует номера телефонов в формат: +7(999)999-99-99.
2. Объединяет дублирующиеся записи о человеке в одну.
3. Сохраняет отформатированные данные в файл phonebook.csv.





