# Встроенные  функции

* `print()` - печать (вывод)
    * `print()` - без аргументов
    * `print("Привет")` - 1 позиционный аргумент
    * `print(22, 33, 77)` - любое кол-во позиционных аргументов
    * именованные аргументы: `sep`, `end`, `file`
        * `print(55, 66, sep="!")`
        * `print("Привет", end="\n")`
        * `print("Привет", file=f)`

* `input()` - ввод
    * `input()` - без аргументов
    * `input("Ваше имя: ")` - 1 позиционный аргумент

    Не принимает 2 и более аргументов
* `len()` - возвращает длину объекта
    * `len("Привет")` - принимает только 1 позиционный аргумент (итерируемый объект  - может быть обработан циклом `for`:
        * `str` - string - строка
        * `list` - список
        * `tuple` - кортеж
        * `set` - множество
        * `dict` - dictionary - словарь
        * `range` - диапазон