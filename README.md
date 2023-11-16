# E6-Chatapp-Skillfactory
В качестве итогового проекта вам необходимо разработать проект, состоящий из клиента на JavaScript и бэкенда на Django Rest Framework.

Ваше задание очень простое: нужно реализовать базовый мессенжер со следующими функциями:

- отправка и получение сообщений;
- создание, редактирование и удаление групповых чатов и переписка в них (подсказка — управлять чатами лучше по REST API, а переписываться так же, как в обычных чатах, но с использованием на сервере идеологии «комнат»);
- редактирование личной информации пользователя (имя и аватар);
- просмотр списка других пользователей с переходом на отправку им сообщений.

На первой странице регистрируемся или логинимся
Регистрация:

<img width="982" alt="image" src="https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/f9afcaa8-c56e-4e12-b565-d3d350f086b4">

Вход в систему:

<img width="941" alt="image" src="https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/6909ae59-83bc-4b31-bd95-ac10e27ee4fd">

После этого попадаем на страницу с комнатами

<img width="1003" alt="image" src="https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/baec67fe-f752-4b87-8bc0-31b591b98bec">

Комнаты может создать только админ через restapi или панель администатора

![image](https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/b403932e-138a-4738-9951-21b7ccc49944)

Также через restapi админ может поменять название комнаты, просмотреть и удалить сообщения

![image](https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/78e09141-3571-494d-9134-6235b59b6ecd)

![image](https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/01daf2bc-72e3-411b-8c12-d08255c7fb99)

Зайдем в систему как пользователь, кликаем на названии комнаты, попадаем в чат. Сообщения пользвателя справа, остальных участников - слева. Внизу страницы список всех участников чата. Чат реализован c помощью webcoskets

<img width="996" alt="image" src="https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/6708c9a1-301b-41e7-b35b-eacb2674df49">

<img width="1004" alt="image" src="https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/456f758f-5ca4-4277-a2ff-8103227415ba">

Пользователь может зайти на страницу профиля, изменить фото, имя

<img width="957" alt="image" src="https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/fd3a5334-b396-4eec-80af-ebde05477ecd">

Если кликнуть по кнопке change password, то также можно сменить пароль

<img width="933" alt="image" src="https://github.com/albinadesign/E6-Chatapp-Skillfactory/assets/117900508/8b7eee4f-c2d6-418c-9a55-1cadb5e72bdc">









