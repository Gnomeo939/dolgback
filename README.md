﻿# dolgback
Этот проект реализует веб-приложение для управления информацией об автомобилях с использованием Django framework.

Установка и запуск

1. скачивание:

 скачать zip-файл
 распаковать его
 зайти в него через командную строку ( команда cd )
 
2. Активация виртуального окружения (лучше сделать):

   .\venv\Scripts\activate  


3  Миграции:
   python manage.py makemigrations
   python manage.py migrate

4 Создание суперпользователя:
   python manage.py createsuperuser
(Введите необходимые данные для создания пользователя администратора.)

5.Введите необходимые данные для создания пользователя администратора.
  python manage.py runserver

  После запуска теперь вы можете открыть веб-браузер и перейти по адресу http://127.0.0.1:8000/ (или указанному в сообщении после запуска сервера). 
  Административная панель доступна по адресу http://127.0.0.1:8000/admin/
	http://127.0.0.1:8000/list список машин
	http://127.0.0.1:8000/detail подробности
	http://127.0.0.1:8000/create создать машину
	http://127.0.0.1:8000/confirm_delete подтверждение удаления 

