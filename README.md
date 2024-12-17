# Учебный проект "Место"

#### Спринт 6:
1. Добавлена библиотека `gh-pages`, автоматически размещающая проект на GitHub Pages, в `package.json` добавлен скрипт `deploy`, запускающий сборку;
2. Добавлена разметка всплывашки удаления карточки с кнопкой подтверждения;
3. В разметку добавлена всплывашка редактирования аватара пользователя, а так же кнопка редактирования аватара, отображающаяся при наведении курсора на аватар;
4. Для кнопок без текстовых значений добавлены артибуты `aria-label` для улучшения доступности;
5. Добавлен класс `Api` для работы с сервером;
6. Карточки загружаются с сервера;
7. Добавлен класс `PopupWithConfirmation.js` для всплывашек с кнопкой подтверждения;
8. Изменен шаблон карточки - добавлен счетчик лайков;
9. Карточки добавляются / удаляются через API;
10. Кол-во лайков берется из свойств карточки полученных от сервера, если в поставленных лайках есть id текущего пользователя, то лайк на карточке будет активным;
11. Аватар берется из ответа сервера, сохраняет на сервере новый, в разметке исправлено object-fit для аватара (для не квадратных аватаров);
12. В разметке все изображения, которые подгружаются с сервера, заменены на битовое изображение с черным фоном, текстовые значения данных пользователя заменены на заглушки;
13. При отправке данных на сервер (аватар, инфо пользователя, карточка) надпись на кнопке меняется на "Сохранение...";
14. Настройки валидации перенесены в `src/utils/const.js`;
