﻿# Решение задания 1

1. bool still_palindrom;  
// В функции, проверяющей, является ли строка палиндромом, новая логическая переменная, внутри цикла - результат проверки равенства i-ого и (strlen - i - 1)-ого элемента

2. В программе, подсчитывающей сумму целых чисел из файла, добавлена проверка на переполнение перед каждой операцией сложения.
3. const char END_OF_STRING = '\0';  
// В программе на языке С++, переводящей строку в верхний регистр, введена константа, обозначающая конец строки.
4. В функции, вычисляющей максимальное вещественное число из трёх своих аргументов, прямое сравнение изменено на сравнение модуля разности с погрешностью.
5. В программе, записывающей первые n натуральных чётных чисел в файл, а затем считывающей данные числа из того же файла, название файла "file.txt" вынесено в отдельную константу.
6. bool can_be_rounded_to_zero;  
// В программе, реализующей решение СЛАУ, показывает, достаточно ли мал элемент матрицы (вещественное число), чтобы он мог быть приравнен к нулю.
7. bool is_in_left_half, is_in_bottom_half;  
// В программе, ищущей минимальный положительный и максимальный отрицательный элементы матрицы в её левой и нижней половинах соответственно, переменные упрощают условия принадлежности элемента одной из этих половин.
8. В программе, одной из возможностей которой является определение товаров с суммой, больше/меньше указанной, прямое сравнение вещественных чисел изменено на сравнение модуля разности с погрешностью.
9. bool index_out_of_range;  
// В функции, удаляющей элемент в списке под указанным номером, упрощает условие - проверку границ индекса (больше нуля и меньше длины списка).
10. В программе, реализующей класс "комплексное число", для конструктора и оператора деления добавлены проверки на равенство знаменателя нулю.
11. Для класса "Обыкновенная дробь", при различных арифметических операциях, добавлены проверки на переполнение в числителе/знаменателе.
12. В программе, вычисляющей площадь круга, число Пи изменено с вещественной константы с одинарной точностью на константу из стандартной библиотеки языка.
