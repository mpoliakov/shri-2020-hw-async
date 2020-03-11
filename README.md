# Домашнее задание ШРИ по теме "Асинхронность"

Вам дан асинхронный API, реализующий арифметические действия, операции сравнения и операции над элементами массива. Каждый метод API последним аргументом принимает callback, который будет вызван после окончания асинхронного действия. В файле [example.html](example.html) можно посмотреть примеры использования.

- [код асинхронного API](https://github.com/dima117/shri-async-hw/blob/master/shri-async-hw.js)
- [код примера использования](https://github.com/dima117/shri-async-hw/blob/master/example.html)

## Задания

Нужно написать функцию, которая реализует задание вашего варианта. Массивами, математическими операциями и операциями сравнения пользоваться нельзя. Код нужно разместить на отдельной страничке и выложить её на GitHub Pages.

#### Студент: [Поляков Максим](https://github.com/mpoliakov)

#### Вариант 8

Реализовать операцию [map](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/Map) для асинхронного массива.

```ts
function map(
    array: AsyncArray,
    fn: (cur: any, idx: Number, src: AsyncArray) => any,
    cb: (result: AsyncArray) => void) {

}
```
