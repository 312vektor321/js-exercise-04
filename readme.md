# Упражнения

### Подготовка

1. Форкните текущий репозиторий на свою учетную запись github
2. Склонируйте свой репозиторий на компьютер
3. Выполните команду: `npm ci`

# Задание
- в папке `src` создайте файл `functions.js`, в котором напишите пять функций (одно задание – одна функция) и экспортируйте их.

### Локальная проверка
Для локальной проверки используйте `npm test`

### Задание 1. Обратное число.
Создайте функцию `reverseNumber`, которая принимает число и возвращает число, записанное в обратном порядке. Например, если вход - 12345, функция должна вернуть 54321.

```js
reverseNumber(11);    // 11
reverseNumber(211);   // 112
reverseNumber(9876);  // 6789
```

### Задание 2. Определение, является ли число квадратным числом.
Создайте функцию `isPerfectSquare`, которая принимает число и определяет, является ли оно квадратом какого-то целого числа.
```js
isPerfectSquare(16); // true
isPerfectSquare(-4); // false
isPerfectSquare(0);  // true
```
### Задание 3. Вычисление факториала.
Создайте функцию `factorial`, которая принимает положительное целое число и возвращает его факториал.

```js
factorial(0); // 1
factorial(2); // 2
factorial(5); // 120
```
### Задание 4. Поиск наибольшего общего делителя (НОД).
Создайте функцию `findGCD`, которая принимает два числа и возвращает их наибольший общий делитель.
```js
findGCD(48, 18); // 6
findGCD(10, 11); // 1
findGCD(44, 11); // 11
```

### Задание 5. Объединение массивов.

Создайте функцию `mergeStrings`, которая принимает несколько строк и объединяет их в один.

```js
mergeStrings();        // ''
mergeStrings('a','b'); // 'ab'
mergeStrings('a','C','!');     // 'aC!'
```
