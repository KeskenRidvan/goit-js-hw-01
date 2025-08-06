# GoIT JavaScript Homework - Module 1 🚀

Congratulations, you've reached the finish line of Module 1!

By now, you should know how to declare variables, distinguish between basic data types, and perform simple arithmetic operations. You should also remember the syntax for formatted strings, be able to use comparison operators, and understand how functions work.

It's time to solidify your practical skills on these topics by solving the homework problems!

---

## Homework Assignment №1 📚

- Create a new repository named `goit-js-hw-01` and clone it to your computer.
- In the `goit-js-hw-01` folder, create the project structure according to the diagram below:

```
goit-js-hw-01/
├── index.html
└── js/
    ├── task-1.js
    ├── task-2.js
    └── task-3.js
```

> #### :bangbang: Attention!
>
> File and folder names, as well as the nesting structure, must match the specified diagram. Otherwise, the work will not be accepted.

- Read each task and complete it in the corresponding file.
- Ensure that the code is formatted with `Prettier` and that the live page does not show any errors or warnings.
- Submit your homework to your mentor on the LMS platform.

**Submission Format:** The assignment must include two links: a link to the source files (code repository) and a link to the live page on `GitHub Pages`.

## Task 1. Droid Order

Complete this task in the `task-1.js` file.

The sales station for repaired droids is ready to launch, and a program needs to be written for the sales department. Create a function `makeTransaction` that will expect two parameters when called:

- `quantity` — The first parameter, a `number` representing the number of droids ordered.
- `pricePerDroid` — The second parameter, a `number` representing the price of one droid.

Complete the function's code so that it returns a string with a message about the delivery of the product to the user's country: `"You ordered <quantity> droids worth <totalPrice> credits!"`, where:

- `<quantity>` — The number of droids ordered.
- `<totalPrice>` — The total value of the order, which is the total cost of all ordered droids.

Take the following code and paste it after completing your function to check its correctness. The function's output will be printed to the console.

```js
console.log(makeTransaction(5, 3000)); // "You ordered 5 droids worth 15000 credits!"
console.log(makeTransaction(3, 1000)); // "You ordered 3 droids worth 3000 credits!"
console.log(makeTransaction(10, 500)); // "You ordered 10 droids worth 5000 credits!"
```

Leave this code for your mentor to check.

## Mentor's review criteria:

- The function `makeTransaction(quantity, pricePerDroid)` is defined.
- The call `makeTransaction(5, 3000)` returns `"You ordered 5 droids worth 15000 credits!"`.
- The call `makeTransaction(3, 1000)` returns `"You ordered 3 droids worth 3000 credits!"`.
- The call `makeTransaction(10, 500)` returns `"You ordered 10 droids worth 5000 credits!"`.
- The results of all calls are printed to the console.
- The `makeTransaction` function returns the correct value for any valid arguments.

---

## Task 2. Product Delivery

Complete this task in the `task-2.js` file.

Define a function named `getShippingMessage`. This function, when called, will take three parameters with the following values:

- `country` - The first parameter, a `string` representing the country where the delivery will be made.
- `price` - The second parameter, a `number` representing the total product cost.
- `deliveryFee` - The third parameter, a `number` representing the product delivery cost.

Complete the function's code so that it returns a string with a message about the delivery of the product to the user's country: `"Shipping to <country> will cost <totalPrice> credits"`, where:

- `<country>` - The delivery country.
- `<totalPrice>` - The total order cost, which includes the product and delivery costs.

Take the following code and paste it after completing your function to check its correctness. The function's output will be printed to the console.

```js
console.log(getShippingMessage('Australia', 120, 50)); // "Shipping to Australia will cost 170 credits"
console.log(getShippingMessage('Germany', 80, 20)); // "Shipping to Germany will cost 100 credits"
console.log(getShippingMessage('Sweden', 100, 20)); // "Shipping to Sweden will cost 120 credits"
```

Leave this code for your mentor to check.

## Mentor's review criteria:

- A function named `getShippingMessage(country, price, deliveryFee)` is defined.
- The call `getShippingMessage("Australia", 120, 50)` returns `"Shipping to Australia will cost 170 credits"`.
- The call `getShippingMessage("Germany", 80, 20)` returns `"Shipping to Germany will cost 100 credits"`.
- The call getShippingMessage("Sweden", 100, 20) returns `"Shipping to Sweden will cost 120 credits"`.
- The `getShippingMessage` function returns the correct value for any valid arguments.

---

## Task 3. Element Width

Complete this task in the `task-3.js` file.

Define a function named `getElementWidth` that, when called, expects three parameters:

- `content` — The first parameter, which is the content width.
- `padding` — The second parameter, which is the padding value for each side.
- `border` — The third parameter, which is the border thickness value for each side.

All parameter values will be in the format `Npx`, where `N` is any integer or decimal number.

The function should return the total width of the element. Assume that the `box-sizing` value is `border-box` when calculating the total width.

Take the following code and paste it after completing your function to check its correctness. The function's output will be printed to the console.

```js
console.log(getElementWidth('50px', '8px', '4px')); // 74
console.log(getElementWidth('60px', '12px', '8.5px')); // 101
console.log(getElementWidth('200px', '0px', '0px')); // 200
```

Leave this code for your mentor to check.

## Mentor's review criteria:

- The function `getElementWidth(content, padding, border)` is defined.
- The call `getElementWidth("50px", "8px", "4px")` returns the number `74`.
- The call `getElementWidth("60px", "12px", "8.5px")` returns the number `101`.
- The call `getElementWidth("200px", "0px", "0px")` returns the number `200`.
- The `getElementWidth` function returns the correct value for any valid arguments.
