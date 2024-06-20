# Веб-приложение TravelWithFriends
[Сервис для планирования и учета путешествий с друзьями, включая разделение расходов, маршруты и жилье.](https://travel-with-friends.ru) 

## <span style="font-size:larger;">Команда 7-6</span>

- [Екатерина Воронежская](https://github.com/egoistique)  - Тимлид, Fullstack разработчик
- [Валерий Деревянко](https://github.com/VaL1y)  - Аналитик, технический писатель
- [Максим Бондарев](https://github.com/bdybgs) - Frontend разработчик, тестировщик

## <span style="font-size:larger;">Код программы: </span>
- [Backend](https://github.com/egoistique/TravelWithFriends_backend) 
- [Frontend](https://github.com/bdybgs/TravelWithFriends-web)
- [Deploy](https://github.com/egoistique/twf_deploy_version)

## <span style="font-size:larger;">Сервисы: </span>
- [YouTrack](https://triptogether.youtrack.cloud/agiles/159-2/current)
- [Miro](https://miro.com/app/board/uXjVNKQcULM=/)
- [Figma](https://www.figma.com/file/2lYl2967DBFk9prQNro5qh/WebTrip?type=design&node-id=0-1&mode=design&t=pHlSkdu70V9r9KgC-0)

## <span style="font-size:larger;">Документация: </span>

- [Техническое задание docx](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Техническое%20задание.docx)
- [Техническое задание pdf](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Техническое%20задание.pdf)
- [Сопроводительное письмо docx](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Сопроводительное%20письмо.docx)
- [Сопроводительное письмо pdf](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Сопроводительное%20письмо.pdf)
- [Презентация pdf](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Презентация.pdf) 
- [Презентация pptx](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Презентация.pptx)
- [Видеопрезентация](https://youtu.be/zmIHbz_8H18)
- [Видеообзор бекенда](https://youtu.be/lFWrIwzohBg)
- [Видеообзор фронтенда]()
- [Видеообзор деплоя](https://youtu.be/3DBmakNYca0)
- [Курсовой проект pdf](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Курсовой%20Проект.pdf)
- [Курсовой проект docx](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/Курсовой%20Проект.docx)
- [Swagger docs yaml](https://github.com/egoistique/TravelWithFriends/blob/main/documentation/swagger_docs_api.yaml)
- [Swagger hub](https://app.swaggerhub.com/apis/kirakirillova762/travel-wf_api/TWF#/)

## <span style="font-size:larger;">Аналитика приложения: </span>

[Яндекс Метрика](https://metrika.yandex.ru/dashboard?id=97428533)

## <span style="font-size:larger;">Тестовые данные для входа в приложение: </span>

[Ссылка на сайт](https://travel-with-friends.ru)   

Администратор:

Логин: admin@travelwf.com  
Пароль: pass1234  

Пользователь:

Логин: user@travelwf.com  
Пароль: 123456  


## <span style="font-size:larger;">Инструкция для запуска: </span>
Инструкция по запуску веб-приложения со стороны разработчика:

Запуск Backend:  
Необходимо установить папку с серверной частью кода, открыть решение в ide, запустить 2 проекта: Travel.Api и Travel.Identity. Убедиться, что в docker есть контейнер с PostgreSQL.

Альтернативный вариант:   
Находясь в корневом каталоге проекта в cmd прописать команды:
1. docker-compose build
2. docker-compose up  
После чего в docker появятся 3 контейнера.
Api будет доступен по адресу http://localhost:10000

Запуск Frontend:   
Необходимо скачать архив с клиентской частью кода, выгрузить его в отдельную папку, открыть командную строку, дойти до расположения папки созданной папки и прописать команду 'npm start'.

