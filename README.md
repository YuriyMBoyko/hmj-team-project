# Handmade Jewelry

## Назва проекту

**Handmade Jewelry** — командний проект з блоку **HTML+CSS**.

## Про проект

Проект виконано як результат вивчення блоку **HTML+CSS** курсу **FullStack Developer** у [GoIT](https://goit.global/ua/).

Проект виконано на основі [Vanilla App Template](https://github.com/goitacademy/vanilla-app-template)

Посилання:
- [макет веб-сторінки](https://www.figma.com/design/54aZckZU4SZP8BtBARsYVU/Handmade-Jevelery?node-id=8202-62143&t=bU2eq9SkkgnQUH7v-0);
- [технічне завдання](https://docs.google.com/spreadsheets/d/16rx-hTSMhKpxae0-HjRQJNME0Lq8PWhv-zKCYqE2bVk/edit?gid=0#gid=0);
- [дошка Trello](https://trello.com/invite/b/69f26ae71778845fcaadf2b9/ATTI072e4cae23896f19e574cf8bc04b7f4bD67A3F48/hmj-team-project)

## Робота над проектом

Для реалізації проект було поділено на десять розділів:
1. header
2. секція hero
3. секція about
4. секція benefits
5. секція gallery
6. секція testimonials
7. секція contacts
8. footer
9. mobile menu
10. додаткові задачі

Кожен розділ (за виключенням двох останніх) складався з чотирьох задач:
1. html (підготовка html розмітки відповідної секції)
2. css mobile (реалізація мобільної верстки)
3. css tablet (реалізація верстки для планшетів)
4. css desktop (реалізація верстки для комп'ютера)

Над задачами кожного розділу працювали послідовно.

Над розділам працювали паралельно.

Виконавці обирали собі задачі самостійно з переліку задач ToDo.

## Виконавці

- Юрій Бойко **Team Lead** 
    (підготовка репозитарію, header-html, testimonials-css tablet, code review, bug fixing, доопрацювання: gallery-css, testimonials-css та footer-css)
- Ігор Гульчак **Web-developer** 
    (hero-css mobile, about-html, about-css desktop, testimonials-html, contacts-html, contacts-css mobile, contacts-css desktop, bug fixing, додаткові задачі)
- Ірина Антонюк **Web-developer** 
    (about-css mobile, footer-html, footer-css mobile, footer-css desktop, mobile menu-css)
- Ірина Коваль **Web-developer** 
    (benefits-css mobile, benefits-css tablet, benefits-css desktop, contacts-css tablet, mobile menu-html)
- Карина Бобровська **Web-developer** 
    (gallery-html, gallery-css mobile, gallery-css tablet, gallery-css desktop)
- Тетяна Бондаренко **Web-developer** 
    (about-css tablet, benefits-html, testimonials-css mobile, testimonials-css desktop)
- Петро Рудик **Web-developer** 
    (header-css mobile, header-css tablet, header-css desktop)
- Анастасія Дишлюк **Web-developer** 
    (hero-css tablet, hero-css mobile)
- Владислав Бугаєнко **Web-developer** 
    (hero-html)

## Технології, використані при роботі над проектом

- **HTML5** (розмітка сторінок)
- **CSS3** (адаптивна верстка)
- **Vite** (збирання проекту)
- **JavaScript**

## Структура проекту

- `src/index.html` — основна сторінка сайту
- `src/partials/` — HTML-частини сторінки (header, sections, footer тощо)
- `src/css/` — стилі (загальні стилі та стилі секцій)
- `src/js/` — JavaScript-логіка

## Запускаємо проект локально

### 1. передумови

- Встановлений **Node.js** (рекомендовано LTS)
- **npm** (встановлюється разом із Node.js)

### 2. встановлюємо залежності

```bash
npm install
```

### 3. запускаємо у режимі розробки

```bash
npm run dev
```

Після запуску відкрити у браузері адресу, яку покаже Vite (зазвичай
`http://localhost:5173`).

## Розгортання на github

Проєкт налаштований на збирання через Vite та може бути розгорнутий на **GitHub Pages**.

Для коректної роботи на GitHub Pages у файлі `package.json` вказано base-шлях:

```json
"build": "vite build --base=/hmj-team-project/"
```
