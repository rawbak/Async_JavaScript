## Task 4. Асинхронность в JavaScript

### Задание 1: "Получение данных о пользователе"
  Реализуйте асинхронную функцию для получения данных о пользователе с удаленного
  сервера:
   ### Функция getUserData
  #### Описание:
  1. Функция принимает идентификатор пользователя (ID) в качестве аргумента и использует fetch для получения данных с удаленного сервера.
  2. Функция возвращает промис, который разрешается с объектом данных о
   пользователе, если запрос был успешным.
  3. Если пользователь с указанным ID не найден, промис должен быть
  отклонен с соответствующим сообщением об ошибке.
  #### Последовательность действий:
  1. Вызовите fetch, передав URL с нужным ID пользователя.
  2. Если ответ успешен (код 200), извлеките данные с помощью
   response.json().
  3. Верните объект с данными о пользователе.
  4. Если ответ не успешен, отклоните промис с сообщением об ошибке.
   
### Задание 2: "Отправка данных на сервер"
Реализуйте функцию для отправки данных о пользователе на сервер:
### Функция saveUserData
#### Описание:
  1. Функция принимает объект с данными о пользователе и использует fetch для отправки этих данных на удаленный сервер.
  2. Функция возвращает промис, который разрешается, если данные успешно отправлены.
  3. Если запрос неуспешен, промис должен быть отклонен с соответствующим сообщением об ошибке.
  #### Подсказка:
  1. Используйте метод POST и задайте заголовок Content-Type как application/json.
  2. Объект с данными о пользователе необходимо сериализовать в JSON-строку с помощью JSON.stringify().


### Задание 3: "Изменение стиля элемента через заданное время"
Реализуйте функцию, которая изменяет стиль элемента с задержкой:
### Функция changeStyleDelayed
#### Описание:
  1. Функция принимает идентификатор элемента (id)и время задержки в миллисекундах (delay).
  2. После истечения времени задержки, функция должна изменить стиль элемента.

