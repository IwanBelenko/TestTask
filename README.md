Задача :
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

Описание алгоритма решения:

Обьявляем два массива: array0 и array1 равные по длине. Создаем метод, в котором цикл равный длине массива, внутри цикла проверяет условие ( <=3 ), если да элемент первого массива array1  заносится в count элемент второго массива array2. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. Потом создаем метод для печати массива. После запускаем оба метода.

Блок схема представлена в блок-схема метода.jpeg

Реализация алгоритма Program.cs
