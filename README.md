# Asynchronous
Домашние задание № 2 "асинхронность в js"

Я не обрабатывал все возможне исключения в функциях.
Например в моем варианте номер 7,
не смотря на то что указан интерфейс AsyncArray, это не значит, что все значения массивы будут числами.
Не занимался проверкой и приведением типов, ((

Так же мои функци могут возвращать не только нужный callback с указаннми параметрами, но и промисы,
то есть, если вы изъявите желание не передавать callback в качестве одного из аргументов, то всегда можете получить promise в качестве ответа
или же сделать и callback и promise, на вкус и цвет так сказать

Сделал все 10 вариантов, не скажу что идеально, но как есть, код фукнций лежит в js/helpers.js
Сам вызов функций из helpers.js происходит внутри html страницы))), то есть здесь)

Код из бонусных заданий находиться в js/bonus.js, к html не подключен.