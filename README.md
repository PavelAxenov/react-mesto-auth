# Проект: Места России

**_Простой способ поделиться фото с друзьями и близкими_**
### Окно регистрации
![Окно регистрации](https://github.com/KishlyanovP/mesto-react/raw/main/src/images/registration.png)
### Окно входа
![Окно входа](https://github.com/KishlyanovP/mesto-react/raw/main/src/images/sign-in.png)
### Главная страница
![Главная](https://github.com/KishlyanovP/mesto-react/raw/main/src/images/main.png)
### Редактирование профиля
![Профиль](https://github.com/KishlyanovP/mesto-react/raw/main/src/images/redactProf.png)
### Попап с картинкой
![Картинка](https://github.com/KishlyanovP/mesto-react/raw/main/src/images/popupImage.png)
### Добавление карточки с фото
![Добавить место](https://github.com/KishlyanovP/mesto-react/raw/main/src/images/addImage.png)
### Обновление аватара
![Обновить аватар](https://github.com/KishlyanovP/mesto-react/raw/main/src/images/uploadAvatar.png)

## Функциональность    <img src="https://img.icons8.com/ios-filled/30/000000/camera--v1.png"/>

* Подключен API. Использован стейт для данных из API;
* Созданы роуты и описаны перенаправления:
    * /sign-up — для регистрации пользователя;
    * /sign-in — для авторизации пользователя.
* Компонентом HOC ProtectedRoute защищен роут '/', чтобы на него не смогли перейти неавторизованные пользователи.
* Шапка для авторизованного и неавторизованного пользователя отличается.
* Реализована аутентификация пользователя.
* Модальные окна открываются при нажатии на соответствующий элемент интерфейса.
* При клике на картинку показывается полноразмерное изображение.
* Настроена работа с localStorage так, чтобы токен сохранялся в нём и использовался при работе с сайтом. При повторном визите пользователю не нужно вновь авторизоваться;
* Индикаторы загрузки данных на сервер: блокировка и смена внешнего вида кнопки submit форм.
## Стек
* HTML;
* CSS;
* ReactJS;
* ReactHooks;
* ReactRouter;
* API;
* Webpack;
* Git.

## Инструкция по запуску приложения
* Клонировать проект https://github.com/KishlyanovP/react-mesto-auth;
* Установить зависимости npm install;
* Запустить локальный сервер npm start. В браузере откроется проект по адресу http://localhost:3000.


