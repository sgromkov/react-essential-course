# Урок 5 - ES2015, роутинг, CSS препроцессоры, PropTypes, контекст

## Резюме

Описание урока

## Вопросы к самопроверке

 - Чем отличается объявление переменных с помощью let от var?
 - Чем arrow-фунции отличаются от обыкновенных функций?
 - Какие возможности предоставляют CSS репроцессоры?
 - Как объявить переменую в LESS?
 - Что такое и какие функции выполняю миксины (примеси) в LESS?
 - Для чего нужен роутер в веб-приложении?
 - Зачем нужно валидировать свойства компонентов?
 - Как использовать контекст в React? Когда его следует использовать?

## Примеры из видео

 - Примеры на ES2015 [[код]](/04-routing-and-es6/01-es6)
 - Приложение для отображения сообщений (react-router) [[код]](/04-routing-and-es6/02-routing) [[demo]](/04-routing-and-es6/sdsd)
 - Использование PropTypes [[код]](/04-routing-and-es6/03-proptypes)
 - Использование контеста [[код]](/04-routing-and-es6/04-context)

## Материалы

**ES2015**

 - [javascript.ru](https://learn.javascript.ru/es-modern-usage)
 - [BabelJS](https://babeljs.io/docs/learn-es2015/)
 - Бесплатная [книга](http://exploringjs.com/) о ES2015 (на английском)
 - Еще одна [книга](https://github.com/getify/You-Dont-Know-JS/blob/master/es6%20&%20beyond/README.md#you-dont-know-js-es6--beyond) о ES6

Роутинг

 - React Router - [документация](https://github.com/rackt/react-router) [примеры](https://github.com/rackt/react-router/tree/master/examples)
 - Выступление Майкла Джексона на React.js Conf 2015 - [react-router increases your productivity](https://www.youtube.com/watch?v=XZfvW1a8Xac)

CSS препроцессоры

 - Документация less [http://lesscss.org/](http://lesscss.org/)
 - [LESS для новичков по-русски](https://www.gitbook.com/book/mrmlnc/less-guidebook-for-beginners/details)

Flexbox:

 - http://frontender.info/a-guide-to-flexbox/
 - https://habrahabr.ru/post/242545/

PropTypes: https://facebook.github.io/react/docs/reusable-components.html

Context: https://facebook.github.io/react/docs/context.html

## Домашнее задание

Задание 1 : В приложении с заметками определить propTypes
Уровень сложности: низкий
На предыдущем уроке мы писали приложение с заметками. Переписать его на ES2015 и для всех компонентов описать propTypes

Задание 2 : Отображение статей
Уровень сложности: средний
Задается articles.json файл в котором хранится массив объектов, которые соответствуют статьям. Написать приложение для отображения статей из этого файла. Должно быть две страницы: `/articles` (просто список всех статей) и `/article/:id` (страница со статьей.

Задание 3 : Маленький интернет-магазин
Уровень сложности: высокий
Напишите маленький интернет магазин, в котором есть такие страницы:

 - Главная страница (/home) на которой отображается информация о магазине.
 - Страница со писком товаров и поиском по нему (/goods).
 - Страница с описанием конкретного товара (/goods/:id).
 - Корзина (/cart)

Кадлый из товаров должна быть возможность положить в корзину.
