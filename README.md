**Итоговая проверочная работа.**
-
**Задача:**
-
*Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.*


***
**Алгоритм решения:**
-
1. Перебираем значения из исходного массива
2. Проверяем каждое значение из массива на соответствие условию: длина строки меньше или равна 3
3. Если строка удовлетворяет условию кладем значение в новый массив
4. Повторяем пункты 2 и 3 до тех пор пока не достигнем конца исходного массива
5. Возвращаем новый заполненый массив как результат

**Блок-схема алгоритма:**
-
Диаграмма в файле
***\final0.25\final.DRAWIO***

**Программа:**
-
Для запуска программы откройте файл Program.cs и запустите команду через терминал:

dotnet run 
-
**Примеры:**
-
["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []