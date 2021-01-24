**Цикл while**

**Полная форма**
```js
while (/*<условие>*/) { // Пока выполняется <условие> - выполняется <код>
    /*
        <код>
    */;
}
```
**Краткая форма**
```js
while (/*<условие>*/) /*<код>*/;
// или
while (/*<условие>*/)
    /*<код>*/;
```
**Пример**
```js
var i = 10;
while (i > 0) {
    if (i % 2 == 0) document.write(i);
    else document.write(i + " ");
    i--; // уменшаем i, чтобы не сделать бесконечный цикл 
    // & 109 87 65 43 21
}
```
***Попробуй***