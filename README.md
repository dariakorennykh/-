# -Синтаксис
Тела функций заключаются в фигурные скобки { }. Код внутри фигурных скобок иногда называют блоком кода.
Каждая команда заканчивается точкой с запятой ;
Метод применяется к объекту через точку. Пример: Serial.begin();
Вызов функции или метода всегда заканчивается скобками, даже если функция не принимает параметров. Пример: loop()
Разделитель десятичных дробей - точка. Пример: 0.25 У запятой тут другое применение.
Запятыми перечисляются аргументы функций и методов, члены массива, также через запятую можно выполнить несколько действий в одну строчку. Пример: digitalWrite(3, HIGH); массив - int myArray[] = {3, 4, 5 ,6};
Одиночный символ заключается в одиночные кавычки 'а'
Строка и массив символов заключается в двойные кавычки "строка"
Имена переменных могут содержать латинские буквы в верхнем и нижнем регистре (большие и маленькие), цифры и подчеркивание. Пример: myVal_35 .
Имена переменных не могут начинаться с цифры. Только с буквы или подчёркивания.
Регистр имеет значение, т.е. большая буква отличается от маленькой. Пример: имена val и Val - не одно и то же.

Структура кода
Прежде чем переходить к структуре и порядку частей кода, нужно кое-что запомнить:

Переменная любого типа должна вызываться только после своего объявления. Иначе будет ошибка
Объявление и использование классов или типов данных из библиотеки/файла должно быть после подключения библиотеки/файла
Функция может вызываться как до, так и после объявления, потому что C++ компилируемый язык, компиляция проходит в несколько этапов, и функции "выделяются" отдельно, поэтому могут вызываться в любом месте программы
