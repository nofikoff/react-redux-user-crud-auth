﻿# Запуск
npm i
mpn start





# Тестовое задание (срок 3 рабочих дня от момента взятия задания в работу).
Необходимо создать React+Node.js SPA приложение, которое будет отображать форму авторизации пользователя.


# Описание:
При заходе на стартовую страницу пользователю отображается форма авторизации, на которой находятся поля для ввода логина и пароля и кнопка "Отправить".
При нажатии на кнопку "Отправить" происходит валидация формы (оба поля не могут быть пустыми), при ошибке валидации пользователю отображается соответствующее сообщение. 
Валидация происходит на стороне клиента без перезагрузки страницы. При корректном вводе login & password, после проверки пользователя на стороне сервера, 
пользователю отображается страница с приветствием, в противном случае - сообщение об ошибке авторизации и предложение повторного ввода.
Дизайн - свободный, можно использовать material.

# Обмен данными между клиентом и сервером осуществляется в XML.

В результате в ответ на это письмо должны быть отправлены:
1. Исходный код (ссылка на git) с комментариями

# Приветствуется:
1. Комментирование кода
2. Использование пакетов (по желанию): Formik, Yup, Axios, express, парсер xml || любые альтернативы пакетов из перечня
3. Управление пользователями CRUD (на примитивном уровне)
4. Ссылка на развернутое рабочее приложение

# Настоятельно рекомендуется:
1. Redux || любая другая альтернатива контейнера состояний
2. Добавить пользователя admin с паролем 12345 для входа в приложение. БД не обязательна, можно "хардкод" || "файловое" хранение (eg node fs || sqlite3 etc).
3. сессионность/токенизация (можно на примитивном уровне), webpack cfg * (задание со звездочкой, делать по желанию/возможности)
