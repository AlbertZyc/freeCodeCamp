---
title: Immutable Types
localeTitle: Неизменяемые типы
---
> Неизменяемые средства неизменяемы, т. Е. Вы не можете изменить.

Javascript имеет множество неизменных типов, например, примитивный тип `string` . Попробуйте это в консоли.
```
s = "red"; 
 console.log(s[1]); //→ "e" 
 s[1] = "x"; 
 console.log(s) //→ "red" 
```

`s` не изменилось! WAT !

## Детали

Некоторые строковые методы, такие как `String.replace` возвращают новую строку.

JavaScript имеет один сложный тип данных, тип данных объекта и имеет пять простых типов данных: Number, String, Boolean, Undefined и Null. Эти простые (примитивные) типы данных неизменяемы (не могут быть изменены), в то время как объекты изменяемы (могут быть изменены).