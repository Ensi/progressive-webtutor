# StrDate()

```js
/**
 * Преобразует дату в строку в формате, используемом по умолчанию в операционной системе. Если в качестве аргумента передается null или пустая строка, функция возвращает пустую строку.
 * @param {Date, null, ""} date Объект даты
 * @param {Boolean} ShowTime    Включать время. Необязательный аргумент.
 * @param {Boolean} ShowSeconds Включать секунды во времени. Необязательный аргумент.
 * @return {String}
 */
function StrDate(date, ShowTime, ShowSeconds) {...}

// Пример
StrDate(Date(), true, true);
// '29.08.2016 20:28:08'; 
```