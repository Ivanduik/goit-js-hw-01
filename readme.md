# GoIT JavaScript Homework 01

Домашнє завдання №1 з JavaScript у межах курсу **GoIT**. Проєкт містить три функції для простих обчислень і форматування
результатів.

## Завдання

### 1. Замовлення дроїдів — `task-1.js`

Функція `makeTransaction(quantity, pricePerDroid)` обчислює загальну вартість замовлення та повертає повідомлення.

```js
makeTransaction(5, 3000);
// "You ordered 5 droids worth 15000 credits!"
```

### 2. Доставка товару — `task-2.js`

Функція `getShippingMessage(country, price, deliveryFee)` додає вартість доставки до ціни товару й повертає
повідомлення.

```js
getShippingMessage('Australia', 120, 50);
// "Shipping to Australia will cost 170 credits"
```

### 3. Ширина елемента — `task-3.js`

Функція `getElementWidth(content, padding, border)` обчислює загальну ширину елемента з урахуванням відступів і рамки з
обох боків.

```js
getElementWidth(50, 8, 4);
// 74
```

Формула: `content + padding * 2 + border * 2`.

## Структура проєкту

```text
goit-js-hw-01/
├── index.html
├── README.md
└── js/
    ├── task-1.js
    ├── task-2.js
    └── task-3.js
```

## Як запустити

1. Склонуйте репозиторій:

   ```bash
   git clone https://github.com/USERNAME/goit-js-hw-01.git
   ```

2. Відкрийте `index.html` у браузері (або через Live Server).
3. Відкрийте інструменти розробника (`F12` → **Console**), щоб переглянути результати всіх перевірочних викликів.

Проєкт не потребує встановлення залежностей.

## Жива сторінка

Після увімкнення GitHub Pages сторінка буде доступна за адресою:

`https://USERNAME.github.io/goit-js-hw-01/`

> Замініть `USERNAME` на свій логін GitHub.

## Використані технології

- JavaScript
- HTML5
- Prettier (форматування коду)
