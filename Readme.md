# Личный проект «Cat energy»

* Студент: [Дмитрий Баранов](https://up.htmlacademy.ru/adaptive-individual/1/user/2324921).
* Наставник: `Татьяна Симоненко`.
*  [МАКЕТ](https://www.figma.com/design/GLlcDqnmpzr82PtaPLHcIZ/HTML-2-%2F-%D0%9A%D1%8D%D1%82-%D1%8D%D0%BD%D0%B5%D1%80%D0%B4%D0%B6%D0%B8-(29)?node-id=0-1&p=f&t=tqPdDGNm7GjtknNZ-0)
* [ОБЗОР ПРОЕКТА](https://baranovdmitriy87.github.io/2324921-cat-energy-1/build/)
---


**Проект работает корректно на Node не выше версии node@16**


Техническое задание

1. Общие технические требования

1.1. Сетка: определена в макете.

1.2. Адаптивность сетки: мобильная, планшетная и десктопная версии («фикс» или «резина»).

1.3. Адаптивность графики: ретинизация, векторные изображения.

1.4. Используемая методология: БЭМ.

1.5. Используемый препроцессор: Less.

1.6. Используемый инструмент автоматизации: Gulp.

1.7. Используемые библиотеки: нет.

1.8. Кроссбраузерность: Chrome, Firefox, Safari.

1.9. Типографика: частично определена в макете (прочее — на усмотрение разработчика).

1.10. Используемый шрифт: Oswald, Lato.

3. Все макеты

3.1. Между версиями (мобильная, планшетная, десктопная) сетка может быть как резиновой, так и фиксированной.

3.2. При фиксированной сетке контентная область центруется и не может быть уже макетной ширины. Фоны, которые упираются в края макета должны тянуться на всю страницу.

3.3. Логотип на внутренних страницах — это ссылка на главную страницу.

3.4. Мобильное меню может быть реализовано двумя способами:

-- реализация без JS;

-- реализация с использованием JS.

3.5. При реализации без использования JS главное меню в мобильной версии должно быть открыто, а иконка с крестиком — скрыта. Должны быть предусмотрены классы для скрытого и открытого состояний меню.

3.6. При реализации с использованием JS блок с главным меню в мобильной версии должен открываться при нажатии на иконку «гамбургера». Когда меню открыто, иконка «гамбургера» заменяется на крестик. При нажатии на иконку с крестиком меню закрывается.

3.7. Все состояния элементов при наведении и нажатии указаны в стайлгайде. Состояние ошибки должно быть реализовано только для обязательных полей формы (в макете они помечены звёздочкой).

3.8. Логотип и текст HTML Academy в футере являются ссылкой на лендинг интенсива «HTML и CSS. Адаптивная вёрстка и автоматизация».

4. Главная

Мобильная версия (Index > Mobile):

4.1. Логотип состоит из упрощённой иконки и названия магазина «Кэт энерджи».

4.2. Кнопка «Подобрать программу» должна вести на страницу формы для подбора программы.

4.3. В блоках «Похудение» и «Набор массы» ссылкой должна быть строка, начинающаяся со слова «Каталог». При нажатии должен осуществляться переход на соответствующие разделы каталога. Страницы разделов реализовывать не нужно.

4.4. В блоке «Живой пример» достаточно вёрстки, соответствующей макету. Логику слайдера реализовывать не обязательно.

4.5. Блок карты: необходимая реализация — интерактивная карта (карты Google или Яндекса), ширина подстраивается под ширину вьюпорта (но не уже контентной ширины макета), на карте размещён маркер (может быть как кастомным, так и дефолтным), центр карты соответствует центру блока в макете.

Планшетная версия (Index > Tablet):

4.6. Блоки меняют размеры и расположение согласно макету.

4.7. В состав иконки логотипа добавляются новые элементы.

4.8. Главное меню всегда открыто вне зависимости от его состояния на мобильной версии.

Десктопная версия (Index > Desktop):

4.9. Блоки меняют размеры и расположение согласно макету.

4.10. В составе логотипа добавляются новые элементы.

4.11. Фон первого блока под шапкой тянется на всю ширину экрана и состоит из двух равных частей: левая — с белым фоном, правая — с зелёным фоном и изображением кота, которое упирается в правую границу экрана.

5. Форма

Мобильная версия (Form > Mobile):

5.1. Должны быть реализованы кастомные элементы форм.

5.2. У полей ввода телефона и почты должны быть указаны соответствующие типы для удобного заполнения с телефона.

Планшетная версия (Form > Tablet):

5.3. Блоки меняют размеры и расположение согласно макету.

Десктопная версия (Form > Desktop):

5.4. Блоки меняют размеры и расположение согласно макету.

6. Страница каталога

Мобильная версия (Catalog > Mobile):

6.1. Изображение и название товара — ссылки на страницу с описанием товара. Страницу с описанием товара реализовывать не нужно.

6.2. Кнопка «Заказать» открывает страницу оформления заказа.

6.3. Кнопка «Показать все» показывает новые товары. При отключенном JS должен осуществляться переход на страницу новых товаров. Показ новых товаров и их страницу реализовывать не нужно.

Планшетная версия (Catalog > Tablet):

6.4. Блоки меняют размеры и расположение согласно макету.

Десктопная версия (Catalog > Desktop):

6.5. Блоки меняют размеры и расположение согласно макету.

---

**Обратите внимание, что папка с вашими исходными файлами для работы над проектом — `source/`.**

Полезный файл:

- [Contributing.md](Contributing.md) — руководство по внесению изменений.

_Не удаляйте и не обращайте внимание на файлы и папки:_<br>
_`.github`, `.editorconfig`, `.gitattributes`, `.gitignore`, `.stylelintrc`, `package.json`, `package-lock.json`._

---


### Памятка

#### 1. Зарегистрируйтесь на Гитхабе

Если у вас ещё нет аккаунта на [github.com](https://github.com/join), скорее зарегистрируйтесь.

#### 2. Создайте форк

[Откройте мастер-репозиторий](https://github.com/htmlacademy-adaptive/2324921-cat-energy-1) и нажмите кнопку «Fork» в правом верхнем углу. Репозиторий из Академии будет скопирован в ваш аккаунт.

<img width="800" alt="" src="https://user-images.githubusercontent.com/10909/60808133-3a7ace00-a190-11e9-9d29-401b02036a9c.jpg">

Получится вот так:

<img width="800" alt="" src="https://user-images.githubusercontent.com/10909/60808135-3a7ace00-a190-11e9-9a8d-7390b3784c65.jpg">

#### 3. Клонируйте репозиторий на свой компьютер

Будьте внимательны: нужно клонировать свой репозиторий (форк), а не репозиторий Академии. Также обратите внимание, что клонировать репозиторий нужно через SSH, а не через HTTPS. Нажмите зелёную кнопку «Code» в правой части экрана, чтобы скопировать SSH-адрес вашего репозитория:

<img width="800" alt="" src="https://user-images.githubusercontent.com/10909/60808136-3a7ace00-a190-11e9-884f-24621e62b29a.jpg">

Клонировать репозиторий можно так:

```
git clone SSH-адрес_вашего_форка
```

Команда клонирует репозиторий на ваш компьютер и подготовит всё необходимое для старта работы.

#### 4. Начинайте обучение!

---

<a href="https://htmlacademy.ru/intensive/adaptive"><img align="left" width="50" height="50" alt="HTML Academy" src="https://up.htmlacademy.ru/static/img/intensive/adaptive/logo-for-github-2.png"></a>

Репозиторий создан для обучения на профессиональном онлайн‑курсе «[HTML и CSS. Адаптивная вёрстка и автоматизация](https://htmlacademy.ru/intensive/adaptive)» от [HTML Academy](https://htmlacademy.ru).

[check-image]: https://github.com/htmlacademy-adaptive/2324921-cat-energy-1/workflows/Project%20check/badge.svg?branch=master
[check-url]: https://github.com/htmlacademy-adaptive/2324921-cat-energy-1/actions
