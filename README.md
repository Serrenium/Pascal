# GetJSONByLongString

Как разобрать JSON, если тебе приходит массив, а результат нужно вернуть в виде объекта?

Метод ParseJSONValue конечно работает, но он создаёт значение (TJSONValue).

Так вот, пробуем привести полученный результат к массиву (TJSONArray) .

И если получилось, то просто создаём новый объект (TJSONObject) а в нём - новое значение с данным массивом.
