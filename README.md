# Вакансия Frontend Engineer

<details>
  <summary>Описание вакансии</summary>
  <p>  
<h3>Требования</h2>  

<ul>
    <li>Опыт веб-разработки</li>
    <li>Знание HTML, CSS, JavaScript, Vue</li>
    <li>Знание фундаментальных основ клиент-серверного взаимодействия</li>
    <li>Знание паттернов проектирования</li>
    <li>Понимание принципов и задач ООП</li>
    <li>Умение оптимизировать производительность</li>
    <li>Опыт продвинутой настройки Webpack</li>
    <li>Умение писать красивый и задокументированный код</li>
</ul>

<h3>Будет плюсом</h3>   

<ul>
    <li>Знание TypeScript</li>
    <li>Опыт написания Unit и End-to-end тестов</li>
    <li>Опыт работы со Storybook</li>
    <li>Контрибуции в Open-source проекты, активность на GitHub</li>
</ul>

<h3>Задачи</h2>  

<ul>
    <li>Разработка frontend-части нашей платформы, на которой работают vc.ru , dtf.ru, tjournal.ru</li>
    <li>Создание и поддержка компонентов дизайн-системы</li>
    <li>Оптимизация производительности модулей платформы</li>
</ul>

<h3>Условия</h2>

<ul>
    <li>Работа в голодной до сложных задач команде</li>
    <li>Разумное и мягкое отношение к понятию «рабочий график»</li>
    <li>Удалённая работа</li>
    <li>Испытательный срок — три месяца</li>
    <li>Нужно будет пройти тестовое задание</li>
</ul>

<h3>Дополнительно</h2>

<ul>
    <li>
        Присылайте, пожалуйста, ссылки на ваши GitHub-профили, если хочется что-то показать
    </li>
    <li>
        Мы готовы рассматривать студентов и начинающих веб-разработчиков на позицию Intern и Junior Frontend Developer
    </li>
    <li>
        Студентам предоставляется гибкий график и возможность совмещения с учебой
    </li>
</ul>

> [Перейти к вакансии](https://vc.ru/team/197153-frontend-razrabotchik)

  </p>
</details>


## Тестовое задание 

### Задача

Разработать приложение-фреймворк для создания административных страниц.

### Требования

- Приложение должно быть написано на Vue
- Для сборки приложения нужно использовать Webpack
- Нельзя использовать vue-cli, сборку настраиваем вручную
- Верстаем по макету, стремимся сделать pixel-perfect, уделяем внимание мелочам
- Уделяем внимание структуре приложения, разделению на абстрактные части
- Само приложение представляет из себя общий лэйаут админки + набор компонентов, из которых можно собирать страницы. 
- Примеры компонентов: таблица, кнопка, поле поиска
- Содержание меню и содержание страниц должно задаваться каким-то конфигом. То есть в этом конфиге описана структура меню + для каждой страницы указан список блоков с их данными (например таблица с такими-то данными + кнопка с таким-то текстом и ссылкой)
- Все методы, аргументы, свойства, переменные, возвращаемые значения, типы и основные логические моменты должны быть продокументированы в формате jsdoc
- Иконки можно взять с https://feathericons.com
- Для стилей можно использовать PostCSS

### Бонусные пункты

- Адаптировать верстку под мобилки
- Использовать TypeScript (через Vue.extend)
- Настроить проверку синтаксиса с помощью ESlint

### Как оформить результат

- Выложить полученный код в отдельный репозиторий GitHub 
- Захостить решение на GitHub Pages, чтобы был доступ к тестированию

### Примечания 

- Макеты сделаны в размере x2
- Верстаем по картинке
- Шрифт Roboto

### Макеты

Главный экран, меню, пример страницы с блоком "Таблица"

![](/assets/Main@2x.png)

Поповеры

![](/assets/Popover@2x.png)

Функциональность кнопок внутри выпадающих меню и у кнопки "Добавить пользователя" реализовывать не нужно. Главное, чтобы обработчики задавались конфигом.
