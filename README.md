### LiteWK

API-клиент для VK, написанный без использования фреймворков на почти чистом JS.

Для использования нужен токен от VK API. Сайт сохраняет его в localStorage и не отправляет третьим лицам, но не забывай о XSS-уязвимостях.

Используются библиотеки jQuery и Moment.js.

По всем вопросам пишите в Discord — `seveneightiest`

### Задачи

- [x] AJAX-роутинг
- [ ] Нормальный дизайн :D
- [x] Поддержка капчи
- [x] Кнопка "наверх"

#### Авторизация
- [x] Возможность добавления больше одного аккаунта
- [x] Вход/выход

#### Настройки

- [x] Собственный CSS и JS
- [x] Выбор формата даты
- [ ] Настройка левого меню (перемещение, добавление, удаление элементов, кнопка вверх мб)
- [x] Выбор языка
- [x] Выбор аккаунтов
- [x] Отладка
- [x] Твики интерфейса ???

#### Страница пользователя

##### Информация о пользователе

- [x] **Личная информация**
- [x] Имя, Фамилия, Отчество (никнейм), Девичья фамилия
- [x] Статус
- [x] Семейное положение + человек в нём
- [x] Родной город
- [x] Владение языками
- [ ] ~~Дата регистрации~~
- [x] Родственники
- [x] **Контакты**
- [x] Страна
- [x] Мобильный телефон, дополнительный телефон, Skype, личный сайт
- [x] **Интересы**
- [x] **Образование**
- [x] **Карьера**
- [x] **Военная служба**
- [x] **Жизненная позиция**
- [x] **Счётчики**
- [x] Значок у имени

##### Действия с профилем

- [x] Добавить в закладки
- [x] Дружба
- [x] Чёрный список
- [x] Убрать из ленты новостей
- [x] Подписаться/отписать на/от обновления/обновлений
- [ ] Оставить в подписчиках
- [ ] Репорт

##### Редактирование профиля

- [ ] Смена аватара
- [ ] Смена миниатюры
- [ ] Смена обложки
- [ ] Смена имени/фамилии/п-пола (под вопросом из-за VK ID)
- [ ] Смена статуса
- [ ] Смена семейного положения
- [ ] Смена владения языками
- [ ] Смена родственников (под вопросом, вероятно нельзя изменить через API)
- [ ] Смена контактов (под вопросом)
- [ ] Смена интересов (под вопросом)
- [ ] Смена образования (под вопросом)
- [ ] Смена карьеры (под вопросом)
- [ ] Смена военной службы (под вопросом)
- [ ] Смена жизненной позиции (под вопросом)

#### Страница группы

##### Информация о группе
- [x] Название, описание, статус, прочая информация, шапка, аватарка
- [x] Вики-страница
- [ ] **Действия**
- [ ] Вступление
- [ ] Репорт
- [ ] Добавление в закладки
- [ ] "Рекомендовать друзьям"
- [ ] "Пригласить друзей"

#### Стена

- [x] Вкладки (все посты, владельца страницы, чужие посты, архивированные)
- [x] Отдельная стрнаица со стеной
- [x] Отдельная страница с постом
- [x] Поиск по стене
- [x] Сортировка "сначала старые" (как в kate mobile)
- [x] Пагинатор

##### Пост

- [x] Шаблон поста
- [ ] **Действия с постом**
- [x] Лайк (реакции не нужны)
- [ ] Репост
- [ ] Аттачменты при репосте
- [x] Удаление/восстановление
- [x] Архивирование/разархивирование
- [x] Добавление/удаление в закладки
- [x] Прикрепление/открепление
- [x] Отключение/включение комментариев
- [ ] Редактирование
- [ ] Репорт
- [x] **Аттачменты**
- [x] Фотография
- [x] Видео
- [ ] Аудио
- [ ] Документ
- [ ] Опрос
- [ ] Заметка
- [ ] Статья
- [ ] ВК-Клип(
- [ ] Местоположение
- [ ] Товар
- [ ] Граффити (старые)
- [ ] Вики-страница
- [ ] Ссылка
- [ ] Аудио-плейлист
- [ ] Фотоальбом
- [ ] "Masonry layout"
- [-] Адаптация аттачментов. К примеру, если у поста всего одно фото, отображать его шире, или если у поста только видео, отображать его плеер. То же самое с документами-гифами.
- [ ] **Дополнительные поля постов**
- [x] Подпись автора
- [x] Число просмотров
- [x] "Рекламный пост"
- [x] Источник поста

##### Комментарии

- [x] Шаблон комментария
- [ ] **Действия**
- [x] Лайк
- [ ] Репост
- [ ] Удаление
- [ ] Редактирование
- [ ] Репорт
- [ ] Ветка комментариев
- [x] "OP"

#### Новости

- [ ] Новости.
- [ ] Вкладки новостей
- [ ] Рекомендации
- [ ] "Не показывать в ленте"
- [ ] Списки новостей
