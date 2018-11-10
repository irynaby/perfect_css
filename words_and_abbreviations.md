# Words and abbreviations in CSS

## Крупные блоки/элементы

### `page` 
Cтраница (обычно, корневой элемент). <br>
Sort Form:  - <br>
Example: `page` 

### `container` 
Контейнер, обёртка. <br>
Sort Form:  - <br>
Example: `container` 

### `grid` 
Сетка (для раскладки блоков по модульной сетке). <br>
Sort Form:  - <br>
Example: <br>
`grid` (элемент, внутри которого будет модульная сетка)

### `row` 
Обёртка для ячеек модульной сетки. <br>
Sort Form:  - <br>
Example: <br>
`grid__row` (одна или несколько «строк» модульной сетки) 

### `column` 
Ячейка модульной сетки. <br>
Sort Form:`col`  <br>
Example: <br>
`grid__col-md-6` (ячейка, занимающая 6 колонок на MD-ширине)

### `wrapper` 
Обёртка чего-либо. <br>
Sort Form:`wrap`  <br>
Example: <br>
`contacts__wrapper` (обёртка вокруг контента блока контактов)

### `inner` 
Внутренняя обёртка чего-либо (чаще всего — для ограничения ширины и выравнивания по центру). <br>
Sort Form:  - <br>
Example: <br>
`promo__inner` (внутренняя обертка промо-блока)

### `navigation` 
Навигация. <br>
Sort Form:`nav`  <br>
Example: <br>
`main-nav` (главная навигация)

### `promo` 
Внутренняя реклама, какое-то введение. <br>
Sort Form:  - <br>
Example: `promo` <br>

### `features` 
Особенности, преимущества. <br>
Sort Form:  - <br>
Example: <br>
`features` (блок с описанием свойств и преимуществ)

### `cart` 
Корзина в магазине. <br>
Sort Form:  - <br>
Example: <br>
`cart` (блок корзины на странице корзины)

### `sidebar`, `aside` 
Дополнительная информация (часто — узкая колонка на блоговой странице). <br>
Sort Form:нет  <br>
Example: `sidebar`, `aside`  <br>

---

## Мелкие блоки/элементы

### `item`, `element`, `part` 
Часть, элемент, отдельная «единица». Универсальное слово, если не удаётся придумать что-то специфическое. <br>
Sort Form:`element` → `el`  <br>
Example: <br>
`main-nav__list-item` (пункт в списке в главной навигации, вероятно, `li`), <br>
`filter__part` (типовая часть фильтра)

### `widget` 
Виджет. <br>
Sort Form:  - <br>
Example: <br>
`aside__widget` (виджет в блоке дополнительной информации)

### `logo` 
Логотип. <br>
Sort Form:  - <br>
Example: <br>
`logo` (вы не поверите...) 
`.partner__logo` (логотип партнёра)

### `field` 
Поле формы. <br>
Sort Form:  - <br>
Example: <br>
`field-text` (универсальный блок для набора форм), <br>
`field-radio` (универсальный блок для набора форм), <br>
`field-checkbox` (универсальный блок для набора форм), <br>
`field-select` (универсальный блок для набора форм), <br>
`field-file` (универсальный блок для набора форм)

### `pagination` 
Навигация по нескольким страницам (1 2 3 ...). <br>
Sort Form:  - <br>
Example: `pagination` <br>

### `breadcrumbs` 
«Хлебные крошки» (Главная > Каталог > Товар). <br>
Sort Form:  - <br>
Example: `breadcrumbs` <br>

### `modal` 
Модальное окно. <br>
Sort Form:  - <br>
Example: `modal` <br>

### `popup` 
Всплывающий блок (обычно, по клику на чем-либо). <br>
Sort Form:  - <br>
Example: `popup` <br>

### `tooltip` 
Всплывающая подсказка, небольшой блок (обычно, по наведению на что-либо). <br>
Sort Form:  - <br>
Example: `tooltip` <br>

### `copyright` 
Копирайт. <br>
Sort Form:  - <br>
Example: `copyright` <br>

### `button` 
Кнопка/кнопки. Сама по себе кнопка — всегда [БЭМ-блок](http://nicothin.github.io/idiomatic-pre-CSS/#bem-block). Может иметь миксование с БЭМ-элементами. Слово может использоваться в классах-обёртках (см. пример). <br>
Sort Form:`btn` <br>
Example: <br>
`btn` (отдельная кнопка), <br>
`.promo__btns` (обёртка для кнопок в промо-блоке)

### `title`, `heading`, `caption` 
Заголовок (часто применяется на заголовочных тегах, но не обязательно на них). <br>
Sort Form:нет  <br>
Example: <br>
`promo__title` (заголовок промо-блока) 

### `subtitle` 
Подзаголовок. <br>
Sort Form:  - <br>
Example: <br>
`post__subtitle` (подзаголовок записи в блоге)

### `name` 
Название. <br>
Sort Form:  - <br>
Example: `product__name` <br>

### `slogan` 
Слоган. <br>
Sort Form:  - <br>
Example: <br>
`logo__slogan` (слоган в блоке логотипа)

### `user` 
Пользователь. <br>
Sort Form:  - <br>
Example: <br>
`user` (блок авторизованного/неавторизованного посетителя, к примеру, в шапке)

### `label`, `tag` 
Метка, тег. <br>
Sort Form:  - <br>
Example: <br>
`label` (лейбл), <br>
`post__tags-list` (список меток записи в блоге)

### `category` 
Рубрика(и). <br>
Sort Form:`cat`  <br>
Example: <br>
`post__cats` (рубрики записи в блоге)

### `dropdown` 
Выпадающий элемент (направление выпадения не имеет значения). <br>
Sort Form:`drop`  <br>
Example: <br>
`filter__drop` (выпадающий по клику блок в фильтре) 

### `search` 
Поиск. <br>
Sort Form:  - <br>
Example: <br>
`search-form` (блок быстрого поиска, возможно, в «шапке»)

### `socials` 
Социальные сети (иконки, обычно). <br>
Sort Form:  - <br>
Example: <br>
`socials__list` (список с соц. ссылками)

### `carousel`, `slider` 
Карусель, слайдер (несколько сменяющих друг друга слайдов). <br>
Sort Form:  - <br>
Example: <br>
`promo__slider` (карусель в промо-блоке)

### `header` 
Верхняя часть, «шапка». <br>
Sort Form:  - <br>
Example: <br>
`page-header` («шапка» страницы), <br>
`post__header` («шапка» записи в блоге)

### `footer` 
Нижняя часть, «подвал». <br>
Sort Form:  - <br>
Example: <br>
`page-footer` («подвал» страницы), <br>
`post__footer` («подвал» записи в блоге)

### `additional` 
Добавление чего-либо. <br>
Sort Form:`add`  <br>
Example: <br>
`location__btn-add` (кнопка добавления в блоке какого-то места)

### `info`, `meta` 
Информация о какой-либо сущности. <br>
Sort Form:  - <br>
Example: <br>
`post__info` (информация о записи в блоге)  

### `body` 
Главная контентная часть чего-либо. <br>
Sort Form:  - <br>
Example: <br>
`post__body` (основной текстовой фрагмент записи в блоге)

### `content` 
Содержимое чего-либо. <br>
Sort Form:  - <br>
Example: <br>
`post__content` (основной текстовой фрагмент записи в блоге)

### `section` 
Крупный раздел чего-либо. <br>
Sort Form:  - <br>
Example: <br>
`promo__section` (большой раздел промо-блока)

### `icon` 
Иконка. <br>
Sort Form:  - <br>
Example: <br>
`icon--twitter` (иконка соц. сети (модификатор))

### `link` 
Cсылка. <br>
Sort Form:  - <br>
Example: <br>
`product__more-link` (ссылка «Далее» в блоке продукта)

### `list` 
Cписок. <br>
Sort Form:  - <br>
Example: <br>
`features__list` (список преимуществ)

### `description` 
Описание какой-либо сущности <br>
Sort Form:`descr` <br>
Example: <br>
`product__descr` (описание продукта)

### `image` 
Изображение. <br>
Sort Form:`img`  <br>
Example: <br>
`promo__img` (изображение в промо-блоке)

### `picture` 
Изображение. <br>
Sort Form:`pict`, `pic`  <br>
Example: <br>
`promo__pict` (картинка в промо-блоке)

### `toggle` 
Переключение, тумблер. Часто — «гамбургер», переключающий показ/сокрытие главного меню (на медиа-условии, при котором меню скрывается под «гамбургером»). <br>
Sort Form:  - <br>
Example: <br>
`main-nav__toggle` (переключатель видимости гл. меню)

### `tab` 
Вкладка. <br>
Sort Form:  - <br>
Example: <br>
`tabs` (вкладки), <br>
`promo__tab` (вкладка в промо-блоке)

### `thumbnail` 
Миниатюра (обычно, в какой-либо галерее). <br>
Sort Form:`thumb` <br>
Example: <br>
`photo__thumb` (миниатюра в фотогалерее)

### `avatar` 
Аватарка, маленькая картинка пользователя. <br>
Sort Form:  - <br>
Example: <br>
`user__avatar` (аватарка пользователя в блоке пользователя в шапке)

### `text` 
Текстовой фрагмент (обычно, выводимый из CMS). <br>
Sort Form:  - <br>
Example: <br>
`about__text` (текст «о нас», вероятно обертка вокруг нескольких параграфов)

### `author` 
Автор. <br>
Sort Form:  - <br>
Example: <br>
`post__author` (имя/ник автора записи в блоге)

### `more` 
«далее», «подробнее». <br>
Sort Form:  - <br>
Example: <br>
`product__more-link` (кнопка или ссылка в промо-блоке, предлагающая ознакомиться подробнее)



## Модификации, состояния

### `active`, `current` 
Активный элемент (пункт навигации, активный таб). <br>
Sort Form:  - <br>
Example: <br>
`main-nav__item--active` (модификатор на пункте гл. навигации, соответствущем странице, на которой пребывает посетитель)

### `hidden` 
Скрытое. <br>
Sort Form:  - <br>
Example: <br>
`product--hidden` (модификатор, скрывающий блок продукта)

### `shown` 
Показанное. <br>
Sort Form:  - <br>
Example: <br>
`product--shown` (модификатор, показывающий продукт)

### `error` 
Состояние ошибки. <br>
Sort Form:  - <br>
Example: <br>
`field-text--error` (модификатор, помечающий блок текстового поля как ошибочное)

### `success` 
Состояние успеха. <br>
Sort Form:  - <br>
Example: <br>
`field-text--success`

### `warning` 
Предупреждение. <br>
Sort Form:  - <br>
Example: <br>
`btn--warning` (модификатор, меняющий вид кнопки)   

### `pending` 
Ожидание чего-либо (к примеру, ответа севера после асинхронной отправки формы). <br>
Sort Form:  - <br>
Example: <br>
`btn--pending` (модификатор, меняющий вид кнопки)

---

## Размеры

### `extra small` 
Очень маленький. <br>
Sort Form:`xs` <br>
Example: <br>
`grid__col-xs-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-xs` (имя переменной с соотв. шириной вьюпорта в значении)

### `small` 
Маленький. <br>
Sort Form:`sm` <br>
Example: <br>
`grid__col-sm-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-sm` (имя переменной с соотв. шириной вьюпорта в значении)

### `medium` 
Средний. <br>
Sort Form:`md` <br>
Example: <br>
`grid__col-md-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-md` (имя переменной с соотв. шириной вьюпорта в значении)

### `large` 
Большой. <br>
Sort Form:`lg` <br>
Example: <br>
`grid__col-lg-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-lg` (имя переменной с соотв. шириной вьюпорта в значении)

### `extra large` 
Очень большой. <br>
Sort Form:`xl` <br>
Example: <br>
`grid__col-xl-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-xl` (имя переменной с соотв. шириной вьюпорта в значении)

### `extra extra large` 
Сафсэм балшой. <br>
Sort Form:`xxl` <br>
Example: <br>
`grid__col-xxl-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-xxl` (имя переменной с соотв. шириной вьюпорта в значении)

### `narrow` 
Узкий. <br>
Sort Form:  - <br>
Example: <br>
`btn--narrow` (модификатор, делающий кнопку узкой)

### `wide` 
Широкий. <br>
Sort Form:  - <br>
Example: <br>
`btn--wide` (модификатор, делающий кнопку широкой)

### `phone`, `mobile` 
Мобильные устройства (телефоны до 5 дюймов). <br>
Sort Form:нет  <br>
Example: <br>
`promo--phone` (модификация промо-блока для соотв. устройств)

### `tablet` 
Планшеты (ориентировочно до 12 дюймов). <br>
Sort Form:  - <br>
Example: <br>
`promo--tablet` (модификация промо-блока для соотв. устройств)

### `notebook`, `laptop` 
Ноутбуки. <br>
Sort Form:нет      <br>
Example: <br>
`promo--laptop` (модификация промо-блока для соотв. устройств)

### `desktop` 
Настольные компьютеры. <br>
Sort Form:  - <br>
Example: <br>
`promo--desktop` (модификация промо-блока для соотв. устройств)

---

## Прочее

### `previous` 
Предыдущее (часто - ссылка/кнопка). <br>
Sort Form:`prev`  <br>
Example: <br>
`slider__prev` (кнопка/стрелка на слайдере) 

### `next` 
Следущее (часто - ссылка/кнопка). <br>
Sort Form:  - <br>
Example: <br>
`slider__next` (кнопка/стрелка на слайдере)  

### `advertisement` 
Рекламный фрагмент (осторожно, может вырезаться баннерорезками). <br>
Sort Form:`adv`  <br>
Example: <br>
`aside__adv` (рекламный блок в сайдбаре) 

### `background` 
Фон (чаще — какое-то изменение фонового цвета блока). <br>
Sort Form:`bg` <br>
Example: <br>
`top-rated--bg-gray` (модификация фонового цвета блока самых рейтинговых товаров/услуг)

### `number` 
Число. <br>
Sort Form:`num`  <br>
Example: <br>
`field-text--num` (модификатор для текстового поля, позволяющий иначе оформить числовые поля)
