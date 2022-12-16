# Задание 3

## 3.1
Реализуйте тип (класс) `Money` для представления денежных величин со следующим функционалом:

- тип должен содержать валюту (для простоты предполагаем что это код валюты, строка, и вызывающая сторона сама позаботится о корректности) и сумму – атрибуты `currency` и `amount` 

- тип должен поддерживать операцию сравнения (==)

- тип должен поддерживать операции сложения и вычитания (+, -). Эти операции должны быть доступны только для экземпляров с одинаковой валютой, в противном случае необходимо возбуждать встроенное исключение `ValueError`. В результате должен создаваться новый объект с соответствующим `amount`.


## 3.2
Реализуйте тип (класс) `Point` для представления точки в двухмерном пространстве с такими свойствами:

- тип должен иметь атрибуты `x` и `y`, собственно координаты точки 

- тип должен поддерживать операцию сравнения (==)

- тип должен поддерживать операции сложения и вычитания (+, -). В результате должен создаваться новый объект.

- тип должен поддерживать операцию `*=`. В терминах геометрии это масштабирование, умножение всех осей на соответствующее число. Подсказка: в Python метод называется `__imul__`

- реализуйте метод `dist(other)` (distance, расстояние) который вычисляет расстояние до аргумента по формуле Пифагора. 