Простое SPA на React + Аnt Design

Приложение создано с использованием npm пакета create-react-app.
Приложение имеет:
- 2 странички (список пользователей, карточки) и модальное окно (профиль);
- используется react-router для маршрутизации.
	
Страница "Список пользователей":
- получает данные по api и выводит их в таблицу;
- есть возможность удалить пользователя;
- есть возможность добавить пользователя;
- есть фильтрация по полям: name и height.

Модальное окно "Профиль":
- форма для просмота/изменения пользователя

Страница "Карточки":
- список пользователей в виде карточек (компонент Card);
- есть кнопка редактировать, при нажатии на которую открывается модальное окно "Профиль" для изменения данных. При сохранении изменять данные на карточке.
- и т.д.
