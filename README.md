
# Задача:
 Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма (что и реализовано). При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

# Описание решения:

Задачу решаем с использованием двух методов:
1. Метод сверяет размер элементов исходного массива с заданной величиной и формирует новый массив элементов с заданной размерностью.
2. Метод выводит массив на печать. 

# Решение:

   Объявляем два строковых массива: исходный (inputArray) и конечный (outArray),  а также обнуляем счетчик. Выводим исходный массив на печать. Для этого вызываем метод 2: PrintIntArray.

   Для решения вызываем метод 1:  ArrayOfStringsOfThreeSymbols. Используем цикл "for" (с i=0, пока не выйдем за пределы массива, с шагом в единицу). Далее посредством цикла "if" каждый элемент исходного массива последовательно проверяем на соответствие заданному условию (inputArray[i]<=3), инкрементируя счетчик на каждом витке цикла. 
   
   По завершении циклов отправляем сформированный массив на печать, снова используя метод печати массива.
