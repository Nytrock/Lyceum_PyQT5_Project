# Виртуальная школа
Данное приложение является удобным локальным аналогом веб-приложениям типа "Виртуальная школа". Оно было созданно на PyQt5 для Windows и является первым проектом по Яндекс.Лицею, а значит не было расчитано на промышленное использование.

# Инструкция по запуску на локальной машине

 - Клонировать репозиторий в свою среду
	```shell
	git clone [https://github.com/Nytrock/Newgramm](https://github.com/Nytrock/Lyceum_PyQT5_Project).git
	```

 - Установить зависимости с помощью requirements.txt
	```shell
	pip install -r requirements.txt
	```
  
 - Открыть и запустить файл `Main.py`

# Особенности работы

###  Тестовые аккаунты
В данном приложении существует два типа пользователей: учитель и ученик. Скорее всего, вы первом делом захотите испытать возможности этих пользователей, так что в базе данных уже есть по одному тестовому пользователю на каждый тип. Вот их данные для входа:
  - Ученик
  ```shell
    Логин: log
	Пароль: log
  ```
  
  - Учитель
  ```shell
    Логин: pas
	Пароль: pas
  ```
 
###  Функционал кнопок
Если в некоторых местах нажимать на кнопки `BackSpace` и `Enter`, которые находятся на нумпаде, то они будут иметь функционал. `Enter` будет подтверждать изменения в базе данных, а `BackSpace` возвращать на прошлое окно.

###  Взаимодействие с базой данных
Приложение позволяет добавлять, изменять и удалять информацию фактически для всех полей базы данных, но к сожалению не для всех, как например нельзя создать нового учителя или нельзя создать новый кабинет. Для полноценной возможности редактирования базы данных необходимо использовать сторонние программы. В качестве одной из программ, которая может помочь выйти из этой проблемы, рекомендую попробовать [SQLiteStudio](https://sqlitestudio.pl/).
