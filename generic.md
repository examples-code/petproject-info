# Общие рекомендации к пет-проекту

Данный раздел содержит общие рекомендации, применимые к любому проекту вне зависимости от идеи и стека.
<br><br>

## Отсутствие приватных данных

Если в Вашем проекте присутствуют приватные данные (секретные ключи, токены, dsn базы данных и т.п) — выносите их в переменные окружения.
В качестве одного из решений можно использовать библиотеку **python-dotenv**

## Документирование кода

Если Ваш код предназначен для работодателя, портфолио или подобных случаев — документируйте свой код, 
т.е используйте понятный и осмысленный нейминг, комментарии и аннотации типов.

Если выбранная Вами библиотека или фреймворк не совсем совместимы с аннотациями типов, попробуйте поискать её, так называемую, **stub**-версию. 
(Например есть версия django-stub, добавляющая поддержку типов во фреймворк django)

## Не ищите "крутые" идеи проектов

В большинстве случаев, идея Вашего проекта играет малейшую роль, т.к самое главное то, что содержится в деталях реализации.
Важнее реализовать обычный Блог с интересными фишками, чем скудный и примитивный интернет-магазин.

## YAGNI — You ain’t gonna need it

Светлый принцип, который гласит о том, чтобы Вы избавлялись от не нужных Вам инструкций в коде.
Если у Вас есть закомментированные блоки кода — удаляйте их; 
Написали функции и думаете: "Ладно, оставлю, может быть пригодится" — такого быть не должно.

Удаляйте из исходников всё то, что не используется.

## Пишите тесты

Тесты — это потрясающая вещь для отладки Вашего кода, более того, работадатели очень ценят тех разработчиков, что пишут автоматизированные тесты к приложениям.

Пишите их, не забывайте об этом
