# Веб-приложение TravelWithFriends
[Сервис для планирования и учета путешествий с друзьями, включая разделение расходов, маршруты и жилье.](https://travel-with-friends.ru) 

# Команда 7-6
1. [Екатерина Воронежская](https://github.com/egoistique)  - Тимлид, Fullstack разработчик <br />
2. [Валерий Деревянко](https://github.com/VaL1y)  - Аналитик, технический писатель <br />
3. [Максим Бондарев](https://github.com/bdybgs) - Frontend разработчик, тестировщик <br />

# Код программы 
[Backend](https://github.com/egoistique/TravelWithFriends_backend) <br />
[Frontend](https://github.com/bdybgs/TravelWithFriends-web) <br />
[Deploy](https://github.com/egoistique/twf_deploy_version) <br />

# Сервисы 
- [YouTrack](https://triptogether.youtrack.cloud/agiles/159-2/current)
- [Miro](https://miro.com/app/board/uXjVNKQcULM=/)
- [Figma](https://www.figma.com/file/2lYl2967DBFk9prQNro5qh/WebTrip?type=design&node-id=0-1&mode=design&t=pHlSkdu70V9r9KgC-0)
- [Swagger hub](https://app.swaggerhub.com/apis/kirakirillova762/travel-wf_api/TWF#/)

# Аналитика приложения 
[Яндекс Метрика](https://metrika.yandex.ru/dashboard?id=97428533) <br />
[Яндекс Метрика PDF](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Аналитика20веб-приложения)<br />

# Документация
- [Курсовой проект](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Курсовой%20Проект)
- [Презентация проекта](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Презентации%20проекта/Презентация%20продукта) 
- [Сопроводительное письмо](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Сопроводительное%20письмо)
- [Техническое задание](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Техническое%20задание)
- [Презентация ТЗ](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Презентации%20проекта/Презентация%20ТЗ)
- [Swagger docs yaml](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/SwaggerAPI)

# Видеообзор веб-приложения
- [Видеопрезентация](https://youtu.be/zmIHbz_8H18)
- [Видеообзор бекенда](https://youtu.be/lFWrIwzohBg)
- [Видеообзор фронтенда]()
- [Видеообзор деплоя](https://youtu.be/3DBmakNYca0)

# Инструкция по запуску веб-приложения

## Инструкция по запуску веб-приложения со стороны пользователя

Необходимо перейти по ссылке в [веб-приложение](https://travel-with-friends.ru). Далее возможен вариант его использования в качестве неавторизованного пользователя и авторизованного пользователя. <br />

<b>Учетные данные администратора:</b> <br />
<b>Логин:</b> admin@travelwf.com <br />
<b>Пароль:</b> pass1234 <br />

<b>Учетные данные тестового пользователя:</b> <br />
<b>Логин:</b> user@travelwf.com  <br />
<b>Пароль:</b> 123456 <br />

## Инструкция по запуску веб-приложения со стороны разработчика

Запуск Backend:  
Необходимо установить папку с серверной частью кода, открыть решение в ide, запустить 2 проекта: Travel.Api и Travel.Identity. Убедиться, что в docker есть контейнер с PostgreSQL. <br />

Альтернативный вариант:   
Находясь в корневом каталоге проекта в cmd прописать команды:
1. docker-compose build
2. docker-compose up  
После чего в docker появятся 3 контейнера.
Api будет доступен по адресу http://localhost:10000

Запуск Frontend:   
Необходимо скачать архив с клиентской частью кода, выгрузить его в отдельную папку, открыть командную строку, дойти до расположения папки созданной папки и прописать команду 'npm start'.

