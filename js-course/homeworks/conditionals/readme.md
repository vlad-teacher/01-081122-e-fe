# Conditionals

1. Пользователь вводит **ТРИ** числа
вывести в консоль наибольшее из них.
В этой задаче необходимо сделать проверку на число (нужно убедиться, что пользователь ввел именно число)

2. Используя конструкцию switch, напишите
программу, которая переводит числа в слова.
Например: пользователь вводит число 2,
программа выводит «Два». Программу необходимо сделать для цифр от 0 до 5 (включительно)

3. Дан следующий код:

```js
    let age = 10;

    if (age < 10) {
        console.log('hi!');
    } else if (age < 20) {
        console.log('hello!');
    } else {
        console.log('good day!');
    }
```

Необходимо переписать этот код используя `тернарный оператор`

4. Написать программу для проверки таблицы умножения:
    1. Пользователь вводит число `a`
    2. Пользователь вводит число `b`
    3. Пользователь вводит ответ на `a * b`

Нам необходимо проверить ответ пользователя на корректность, если пользователь ответил неправильно то выводим ответ вида:
**Ошибка! Правильный ответ: `correctAnswer`**

Где `correctAnswer` - это переменная, в которой находится правильный ответ

Если пользователь ввел правильный ответ, то выводим сообщение вида:
**Правильно!**