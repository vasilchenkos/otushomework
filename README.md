# otushomework
Домашние задания к курсу OTUS Python QA Engineer

*Подготовка рабочего окружения для разработки автоматических тестов.*

1. Создаем virtualenv. 
```python3 -m venv env```
2. Запускаем виртуальное окружение source
``` env/bin/activate ```
3. Обновляем pip
``` pip pip install -U pip```
4. Устанавливаем зависимости
``` pip install -r requirements.txt ```
5. Проверяем установку pytest командой
``` pytest ```


*Описать пирамиду автоматического тестирования своего текущего проекта.*
Автоматизации в данный момент на проекте нет, есть юнит тесты, code coverage ~82 %
Преобладает ручное тестирование, смоуки и регресс в том числе тестируются руками и на вебе, и на мобилке.
В планах в течении курса и после окончания думаю покрывать тестами api и ui по ключевым сценариям.

*Запуск тестов с помощью Pytest.*
После того, как будет развернуто окружение запустить команду pytest
```pytest```

