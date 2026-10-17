# GoIT JavaScript Homework 01

Домашнє завдання №1 з JavaScript на курсі **GoIT**. Проєкт містить три функції для обчислень і виведення результатів у
консоль браузера.

- **Репозиторій:** [Ivanduik/goit-js-hw-01](https://github.com/Ivanduik/goit-js-hw-01)
- **Жива сторінка:** [GitHub Pages](https://ivanduik.github.io/goit-js-hw-01/) (після налаштування публікації в
  **Settings → Pages**)

## Завдання

### 1. Замовлення дроїдів — `js/task-1.js`

Функція `makeTransaction(quantity, pricePerDroid)` повертає повідомлення про кількість дроїдів і загальну вартість
замовлення.

```js
makeTransaction(5, 3000);
// "You ordered 5 droids worth 15000 credits!"
```

### 2. Доставка товару — `js/task-2.js`

Функція `getShippingMessage(country, price, deliveryFee)` додає вартість доставки до вартості товару та повертає
повідомлення.

```js
getShippingMessage('Australia', 120, 50);
// "Shipping to Australia will cost 170 credits"
```

### 3. Ширина елемента — `js/task-3.js`

Функція `getElementWidth(content, padding, border)` повертає загальну ширину елемента з урахуванням відступів і рамок
зліва та справа.

```js
getElementWidth(50, 8, 4);
// 74
```

Формула: `content + padding * 2 + border * 2`.

## Структура проєкту

```text
goit-js-hw-01/
├── js/
│   ├── task-1.js
│   ├── task-2.js
│   └── task-3.js
├── .gitignore
├── .prettierrc
├── .prettierrc.json
├── index.html
├── package.json
├── package-lock.json
└── readme.md
```

## Запуск

1. Склонуйте репозиторій:

   ```bash
   git clone https://github.com/Ivanduik/goit-js-hw-01.git
   cd goit-js-hw-01
   ```

2. Відкрийте `index.html` у браузері або за допомогою Live Server.
3. Натисніть **F12 → Console** — там мають відобразитися результати дев'яти тестових викликів функцій.

Для форматування коду через Prettier можна виконати:

```bash
npm install
npx prettier --write "js/**/*.js" index.html
```

## Використані технології

- JavaScript
- HTML5
- Prettier
