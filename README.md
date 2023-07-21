# Нагрузочные тесты для двух эндпоинтов в jmeter

<div id="header"> <img src="https://media.giphy.com/media/sYYuY5oV5oKuqUHZqJ/giphy.gif" width="100"/>
</div>

Написаны нагрузочные тесты на два метода Agent app 

1. Авторизация `/users/obtain-token`
   </br> `POST`
 </br> https://partner.agentapp.ru/v1/users/obtain-token
 </br> {
 </br>	"username": "qa@qa.qa",
 </br>	"password": "111"
 </br>}
 </br>В ответе получаем "token"

2. Создание водителя `/insured_objects/drivers`
    </br> `POST` 
 </br>https://partner.agentapp.ru//v1/insured_objects/drivers
 </br> Пример Body запроса
 </br>{
 </br>  "first_name": "Илон",
 </br>  "last_name": "Маск",
 </br>  "patronymic": "Американович",
 </br>  "birth_date": "1980-02-20",
 </br>  "driving_experience_started": "2018-06-25",
 </br>  "driver_licenses": [
 </br>    {
 </br>      "credential_type": "DRIVER_LICENSE",
  </br>     "number": "619605",
 </br>      "series": "7031",
 </br>      "issue_date": "2018-06-25" } ]}

3. Задать нагрузку в 4 RPS длительностью в 20 секунд

