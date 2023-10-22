# Academy-Top-C-sharp

#### Экзаменационная работа C#

## ExaminationWork

Задание. Создать приложение «Словари».    
Основная задача проекта: хранить словари на разных языках и разрешать пользователю находить перевод нужного слова или фразы.    
Интерфейс приложения должен предоставлять такие возможности:    
- Создавать словарь. При создании нужно указать тип словаря. Например, англо-русский или русско-английский.    
- Добавлять слово и его перевод в уже существующий словарь. Так как у слова может быть несколько переводов, необходимо поддерживать возможность создания нескольких вариантов перевода.    
- Заменять слово или его перевод в словаре.    
- Удалять слово или перевод. Если удаляется слово, все его переводы удаляются вместе с ним. Нельзя удалить перевод слова, если это последний вариант перевода.    
- Искать перевод слова.    
- Словари должны храниться в файлах.    
- Слово и варианты его переводов можно экспортировать в отдельный файл результата.    
- При старте программы необходимо показывать меню для работы с программой. Если выбор пункта меню открывает подменю, то тогда в нем требуется предусмотреть возможность возврата в предыдущее меню.
   
#### Решения домашних заданий C#

## Homework 01

### Тема: "Введение в платформу Microsoft.NET. Основы языка программирования C#"

Задание 1. Пользователь вводит с клавиатуры число в диапазоне от 1 до 100. Если число кратно 3 (делится на 3 без остатка) нужно вывести слово Fizz. Если число кратно 5 нужно вывести слово Buzz. Если число кратно 3 и 5 нужно вывести Fizz Buzz. Если число не кратно не 3 и 5 нужно вывести само число.    
Если пользователь ввёл значение не в диапазоне от 1 до 100 требуется вывести сообщение об ошибке.

Задание 2. Пользователь вводит с клавиатуры два числа. Первое число – это значение, второе число процент, который необходимо посчитать. Например, мы ввели с клавиатуры 90 и 10. Требуется вывести на экран 10 процентов от 90. Результат: 9.

Задание 3. Пользователь вводит с клавиатуры четыре цифры. Необходимо создать число, содержащее эти цифры. Например, если с клавиатуры введено 1, 5, 7, 8 тогда нужно сформировать число 1578.

Задание 4. Пользователь вводит шестизначное число. После чего пользователь вводит номера разрядов для обмена цифр. Например, если пользователь ввёл один и шесть – это значит, что надо обменять местами первую и шестую цифры. Число 723895 должно превратиться в 523897.    
Если пользователь ввёл не шестизначное число требуется вывести сообщение об ошибке.

Задание 5. Пользователь вводит с клавиатуры дату. Приложение должно отобразить название сезона и дня недели. Например, если введено 22.12.2021, приложение должно отобразить Winter Wednesday.

Задание 6. Пользователь вводит с клавиатуры показания температуры. В зависимости от выбора пользователя программа переводит температуру из Фаренгейта в Цельсий или наоборот.

Задание 7. Пользователь вводит с клавиатуры два числа. Нужно показать все чётные числа в указанном диапазоне. Если границы диапазона указаны неправильно требуется произвести нормализацию границ. Например, пользователь ввёл 20 и 11, требуется нормализация, после которой начало диапазона станет равно 11, а конец 20.

Задание 8. Пользователь вводит с клавиатуры слово. Определить является ли оно палиндромом.

## Homework 02

### Тема: "Массивы"

Задание 1. Сжать массив, удалив из него все 0 и, заполнить освободившиеся справа элементы значениями -1.

Задание 2. Преобразовать массив так, чтобы сначала шли все отрицательные элементы, а потом положительные (0 считать положительным).

Задание 3. Написать программу, которая предлагает пользователю ввести число и считает, сколько раз это число встречается в массиве.

Задание 4. В двумерном массиве порядка М на N поменяйте местами заданные столбцы.

## Homework 03

### Тема: "Структура"

Задание 1. Описать структуру Article, содержащую следующие поля: код товара; название товара; цену товара.

Задание 2. Описать структуру Client содержащую поля: код клиента; ФИО; адрес; телефон; количество заказов осуществлённых клиентом; общая сумма заказов клиента.

Задание 3. Описать структуру Request Item содержащую поля: товар; количество единиц товара.

Задание 4. Описать структуру Request содержащую поля: код заказа; клиент, дата заказа; перечень заказанных товаров; сумма заказа (реализовать вычисляемым свойством).

Задание 5. Описать перечисление ArticleType определяющее типы товаров, и добавить соответствующее поле в структуру Article из задания №1.

Задание 6. Описать перечисление ClientType определяющее важность клиента, и добавить соответствующее поле в структуру из задания №2.

Задание 7. Описать перечисление РауТуре определяющее форму оплаты клиентом заказа, и добавить соответствующее поле в структуру Request из задания №4.

Задание 8. Придумать класс, описывающий студента. Предусмотреть в нем следующие моменты: фамилия, имя, отчество, группа, возраст, массив (зубчатый) оценок по программированию, администрированию и дизайну. А также добавить методы по работе с перечисленными данными: возможность установки/получения оценки, получение среднего балла по заданному предмету, распечатка данных о студенте.

## Homework 04

### Тема: "Пространство имён"

Задание 1. Разработайте приложение «7 чудес света», где каждое чудо будет представлено отдельным классом. Создайте дополнительный класс, содержащий точку входа. Распределите приложение по файлам проекта и с помощью пространства имён обеспечьте возможность взаимодействия классов.

Задание 2. Разработать приложение, в котором бы сравнивалось население трёх столиц из разных стран. Причём страна бы обозначалась пространством имён, а город – классом в данном пространстве.

## Homework 05

### Тема: "Наследование"

Задание. Разработать абстрактный класс «Геометрическая Фигура» с методами «Площадь Фигуры» и «Периметр Фигуры». Разработать классы-наследники: Треугольник, Квадрат, Ромб, Прямоугольник, Параллелограмм, Трапеция, Круг, Эллипс. Реализовать конструкторы, которые однозначно определяют объекты данных классов.    
Реализовать класс «Составная Фигура», который может состоять из любого количества «Геометрических Фигур». Для данного класса определить метод нахождения площади фигуры. Создать диаграмму взаимоотношений классов.

## Homework 06

### Тема: "Полиморфизм"

Задание 1. Создайте приложение для перевода обычного текста в азбуку Морзе. Пользователь вводит текст. Приложение отображает введённый текст азбукой Морзе. Используйте механизмы пространств имён.

Задание 2. Добавьте к предыдущему заданию механизм перевода текста из азбуки Морзе в обычный текст.

## Homework 07

### Тема: "Перегрузка индексаторов"

Задание. Создайте приложение «Список книг для прочтения». Приложение должно позволять добавлять книги в список, удалять книги из списка, проверять есть ли книга в списке, и т. д. Используйте механизм свойств, перегрузки операторов, индексаторов.

## Homework 08

### Тема: "Интерфейсы"

Задание. Разработать абстрактный класс ГеометрическаяФигура с полями ПлощадьФигуры и ПериметрФигуры.    
Разработать классы-наследники: Треугольник, Квадрат, Ромб, Прямоугольник, Параллелограмм, Трапеция, Круг, Эллипс и реализовать свойства, которые однозначно определяют объекты данных классов.    
Реализовать интерфейс ПростойНУгольник, который имеет свойства: Высота, Основание, УголМеждуОснованиемИСмежнойСтороной, КоличествоСторон, ДлиныСторон, Площадь, Периметр.    
Реализовать класс СоставнаяФигура который может состоять из любого количества ПростыхНУгольников. Для данного класса определить метод нахождения площади фигуры.    
Предусмотреть варианты невозможности задания фигуры (введены отрицательные длины сторон или при создании объекта треугольника существует пара сторон, сумма длин которых меньше длины третьей стороны и т.п.).

## Homework 09

### Тема: "Исключения"

Задание 1. Пользователь вводит с клавиатуры в строку набор символов от 0-9. Необходимо преобразовать строку в число целого типа. Предусмотреть случай выхода за границы диапазона, определяемого типом int. Используйте механизм исключений.

Задание 2. Пользователь вводит с клавиатуры в строку набор 0 и 1. Необходимо преобразовать строку в число целого типа в десятичном представлении. Предусмотреть случай выхода за границы диапазона, определяемого типом int, неправильный ввод. Используйте механизм исключений.

Задание 3. Пользователь вводит в строку с клавиатуры математическое выражение. Например, 3*2*1*4. Программа должна посчитать результат введённого выражения. В строке могут быть только целые числа и оператор *. Для обработки ошибок ввода используйте механизм исключений.

## Homework 10

### Тема: "Коллекции"

Задание. Создайте примитивный англо-русский и русско-английский словарь, содержащий пары слов – названий стран на русском и английском языках. Пользователь должен иметь возможность выбирать направление перевода и запрашивать перевод.

## Homework 11

### Тема: "Коллекции Generic"

Задание. Напишите программу, которая будет использовать generic-коллекцию List для хранения объектов класса Person. Класс Person должен содержать следующие поля: имя (string), возраст (int), пол (enum Gender).    
Программа должна предоставлять пользователю следующие возможности:    
1. Добавление нового объекта Person в коллекцию.    
2. Удаление объекта Person из коллекции по индексу.    
3. Поиск объекта Person по имени.    
4. Вывод всех объектов Person из коллекции.

## Homework 12

### Тема: "Взаимодействие с файловой системой"

Дан бинарный файл целых чисел. (Файл создайте сами. Числа записываются только через « ».). Обнулить его минимальный элемент (считать, что в файле он единственный). Если файл пуст, ничего не делать.      
1. Следует найти позицию минимального элемента (пользуясь Position).      
2. С помощью метода Seek, следует перейти в позицию минимального элемента и записать в файл переменную с нулевым значением.      
3. Показать полученный результат в консоли.

#### Лабораторные работы

## LaboratoryWork 01

### Тема: "Введение в платформу Microsoft.NET. Основы языка программирования C#"

Задание 1. Выведите на экран цитату Бьярна Страуструпа: It's easy to win forgiveness for being wrong; being right is what gets you into real trouble.    
Пример вывода:    
It's easy to win forgiveness for being wrong;    
being right is what gets you into real trouble.    
Bjarne Stroustrup

Задание 2. Пользователь вводит с клавиатуры пять чисел. Необходимо найти сумму чисел, максимум и минимум из пяти чисел, произведение чисел. Результат вычислений вывести на экран.

Задание 3. Пользователь с клавиатуры вводит шестизначное число. Необходимо перевернуть число и отобразить результат. Например, если введено 341256, результат 652143.

Задание 4. Пользователь вводит с клавиатуры границы числового диапазона. Требуется показать все числа Фибоначчи из этого диапазона. Числа Фибоначчи – элементы числовой последовательности, в которой первые два числа равны 0 и 1, а каждое последующее число равно сумме двух предыдущих чисел. Например, если указан диапазон 0–20, результат будет: 0, 1, 1, 2, 3, 5, 8, 13.

Задание 5. Даны целые положительные числа A и B (A < B). Вывести все целые числа от A до B включительно; каждое число должно выводиться на новой строке; при этом каждое число должно выводиться количество раз, равное его значению. Например: если А = 3, а В = 7, то программа должна сформировать в консоли следующий вывод:    
3 3 3    
4 4 4 4    
5 5 5 5 5    
6 6 6 6 6 6    
7 7 7 7 7 7 7.

Задание 6. Пользователь с клавиатуры вводит длину линии, символ заполнитель, направление линии (горизонтальная, вертикальная). Программа отображает линию по заданным параметрам. Например: +++++.      
Параметры линии: горизонтальная линия, длина равна пяти, символ заполнитель +.

#### Решения тестов C#

## Тесты

1. Test 01 "Основы C#"    
2. Test 02 "Перегрузка операторов, обработка исключений"
3. Test 03 "Интерфейсы"
4. Test 04 "Делегаты"
5. Test 05 "Сборщик мусора"
6. Test 06 "Контрольный"

#### Работа на уроках

## Workinclass 01

### Тема: "Массивы и строки"

Задание 1. Объявить одномерный массив с именем A и с именем B. Заполнить массивы А и В случайными числами с помощью циклов. Вывести на экран значения массивов. Найти в массиве B минимальный/максимальный элемент, общую сумму всех элементов, общее произведение всех элементов, найти общие элементы в обоих массивах.

Задание 2. Даны 2 массива размерности M и N соответственно. Необходимо переписать в третий массив общие элементы первых двух массивов без повторений.

Задание 3. Пользователь вводит строку. Проверить, является ли эта строка палиндромом. Палиндромом называется строка, которая одинаково читается слева направо и справа налево.

Задание 4. Подсчитать количество слов во введённом предложении.

## Workinclass 02

### Тема: "Перегрузка операторов"

Задание. Реализовать класс для хранения комплексного числа. Выполнить в нём перегрузку всех необходимых операторов.

## Workinclass 03

### Тема: "Пространства имён"

Задание. Написать приложение, имитирующее работу банкомата. Реализовать классы Banc, Client, Account в различных пространствах имён (общее пространство имён «Bankomat»). Изначально клиенту нужно открыть счёт в банке, получить номер счёта, получить свой пароль, положить сумму на счёт.    
1. Приложение предлагает ввести пароль предполагаемой кредитной карточки, даётся 3 попытки на правильный ввод пароля. Если попытки исчерпаны, приложение выдаёт соответствующее сообщение и завершается.    
2. При успешном вводе пароля выводится меню. Пользователь может выбрать одно из нескольких действий:    
• вывод баланса на экран;    
• пополнение счёта;    
• снять деньги со счёта;    
• выход.    
3. Если пользователь выбирает вывод баланса на экран, приложение отображает состояние предполагаемого счёта, после чего предлагает либо вернуться в меню, либо совершить выход.    
4. Если пользователь выбирает пополнение счёта, программа запрашивает сумму для пополнения и выполняет операцию, сопровождая её выводом соответствующего комментария. Затем следует предложение вернуться в меню или выполнить выход.    
5. Если пользователь выбирает снять деньги со счёта, программа запрашивает сумму. Если сумма превышает сумму счёта пользователя, программа выдаёт сообщение и переводит пользователя в меню. Иначе отображает сообщение о том, что сумма снята со счёта и уменьшает сумму счёта на указанную величину.

## Workinclass 04

### Тема: "Наследование"

Задание. Разработать приложение «Резервная копия».    
Цель: произвести расчёт необходимого количества внешних носителей информации при переносе за один раз важной информации (565 Гб, файлы по 780 Мб) с рабочего компьютера на домашний компьютер и затрачиваемое на данный процесс время. Вы имеете в распоряжении следующие типы носителей информации:    
• Flash-память,    
• DVD-диск,    
• съёмный HDD.    
Каждый носитель информации является объектом соответствующего класса:    
• Flash-память – класс «Flash»;    
• класс DVD-диск – класс «DVD»;    
• класс съёмный HDD – класс «HDD».    
Все три класса являются производными от абстрактного класса «Носитель информации» – класс «Storage».    
Базовый класс («Storage») содержит следующие закрытые поля:    
• наименование носителя;    
• модель.    
Класс обладает всеми необходимыми свойствами для доступа к полям, а также абстрактными методами:    
• получение объёма памяти;    
• копирование данных (файлов/папок) на устройство,    
• получение информации о свободном объёме памяти на устройстве;    
• получение общей/полной информации об устройстве.    
Кроме того, каждый из производных классов дополняется следующими полями:    
• класс Flash-память: скорость USB 3.0, объем памяти;    
• класс DVD-диск: скорость чтения / записи, тип (односторонний (4.7 Гб) /двусторонний (9 Гб));    
• класс съёмный HDD: скорость USB 2.0, количество разделов, объем разделов.    
Работа с объектами соответствующих классов производится через ссылки на базовый класс («Storage»), которые хранятся в массиве.    
Приложение должно предоставлять следующие возможности:    
• расчёт общего количества памяти всех устройств;    
• копирование информации на устройства;    
• расчёт времени необходимого для копирования;    
• расчёт необходимого количества носителей информации представленных типов для переноса информации.

## Workinclass 05

### Тема: "Полиморфизм"

Задание 1 Создайте класс Human, который будет содержать информацию о человеке. С помощью механизма наследования, реализуйте класс Builder (содержит информацию о строителе), класс Sailor (содержит информацию о моряке), класс Pilot (содержит информацию о лётчике). Каждый из классов должен содержать необходимые для работы методы.

Задание 2 Создайте класс Passport (паспорт), который будет содержать паспортную информацию о гражданине заданной страны. С помощью механизма наследования, реализуйте класс ForeignPassport (загранпаспорт) производный от Passport. Напомним, что заграничный паспорт содержит помимо паспортных данных, также данные о визах, номер заграничного паспорта. Каждый из классов должен содержать необходимые методы.

Задание 3 Создать базовый класс «Животное» и производные классы «Тигр», «Крокодил», «Кенгуру». С помощью конструктора установить имя каждого животного и его характеристики. Создайте для каждого класса необходимые методы и поля.

## Workinclass 06

### Тема: "Перегрузка операторов"

Задание. Создайте класс «Кредитная карточка». Вам необходимо хранить информацию о номере карты, ФИО владельца, CVC, дата завершения работы карты и т.д. Предусмотреть механизмы для инициализации полей класса. Добавьте к уже созданному классу информацию о сумме денег на карте. Выполните перегрузку + (для увеличения суммы денег на указанную величину), - (для уменьшения суммы денег на указанную величину), == (проверка на равенство СМС кода), < и > (проверка на меньше или больше суммы денег), != и Equals. Используйте механизм свойств для полей класса.

## Workinclass 07

### Тема: "Коллекции Generic"

Задание. Программа «Статистика»    
Подсчитать, сколько раз каждое слово встречается в заданном тексте. Результат записать в коллекцию Dictionary<TKey, TValue>. Текс использовать из приложения 1. Вывести статистику по тексту в виде таблицы.    
Приложение 1. Вот дом, Который построил Джек. А это пшеница, Которая в темном чулане хранится В доме, Который построил Джек. А это веселая птица-синица, Которая часто ворует пшеницу, Которая в темном чулане хранится В доме, Который построил Джек.    
Вывести статистику по тексту в виде таблицы:    
............Слово:.........Кол-во:    
1..........Вот...................1    
2..........дом..................1    
3..........Который........3    
4...    
Всего слов: 45 из них уникальных: 20

## Workinclass 08

### Тема: "Делегаты"

Задание. Создадим проект консольного приложения С#, название SharpWasher.    
Разработайте следующие классы: автомобиль Саг, гараж Garage, мойка Washer. Гараж – это коллекция автомобилей. Мойка – независимое предприятие, которое может только мыть автомобиль методом Wash.    
Делегируйте помывку всех автомобилей этому предприятию.

## Workinclass 09

### Тема: "Взаимодействие с файловой системой"

Задание. Чтение и запись в файл      
Написать приложение, позволяющее:      
• создать новый файл с именем «Dayl7.txt». В случае наличия файла с таким именем – вывести сообщение;      
• открыть и прочесть файл с именем «Dayl7.txt». В случае отсутствия – вывести сообщение об отсутствии;      
• записать форматированную информацию в файл;      
Структура записываемой информации:      
Исходные данные: двумерный массив дробных чисел; двумерный массив целых чисел.      
– фамилия, имя, отчество, дата рождения;      
– с новой строки количество строк и столбцов массива дробных чисел;      
– с новой строки значения элементов двумерного массива дробных чисел (каждая строка массива в новой строке файла);      
– с новой строки количество строк и столбцов массива целых чисел;      
– с новой строки двумерный массив целых чисел, записанных в одну строку;      
– с новой строки текущая дата.      
• прочесть информацию из файла и преобразовать её в соответствии с исходной структурой.      
Реализовать простейшее меню.
