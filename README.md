# Нагрузочные тесты для двух эндпоинтов в jmeter

<div id="header"> <img src="https://media.giphy.com/media/sYYuY5oV5oKuqUHZqJ/giphy.gif" width="100"/>
</div>

Написаны нагрузочные тесты на два метода agent app ([документация](https://docs.google.com/document/d/1GkCP0HGfPz9EBk6piCPmGqMBRn3ETeYUcQao-IW9GIc/edit))

Предусловия:
1. Авторизация `/users/obtain-token`
2. Создание водителя `/insured_objects/drivers`
3. Задать нагрузку в 4 RPS длительностью в 20 секунд
4. Запустить нагрузочные тесты через терминал
