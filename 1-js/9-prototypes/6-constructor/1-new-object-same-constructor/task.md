# Создать объект тем же конструктором

[importance 5]

Пусть у нас есть произвольный объект `obj`, созданный каким-то конструктором, каким -- мы не знаем, но хотели бы создать новый объект с его помощью.

Сможем ли мы сделать так?

```js
var obj2 = new obj.constructor();
```

В каком случае такой код будет работать, а в каком -- нет?