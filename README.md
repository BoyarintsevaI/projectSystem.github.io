# Отчет а лабораторных работах
# студент группы ИДБ-15-14 Бояринцева И.Д.

## Лабораторная 1
[Задание 1 - Модель IDEF0](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/1.png)  
[Задание 2 - Код диаграммы](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Code%20PlantUML)  
[Задание 2 - Диаграмма](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0.png)  
[Задание 3 - Код Диаграммы](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Code2%20PlantUML)  
[Задание 3 - Диаграмма](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/2.png)  

## Лабораторная 2
[Задание 1 - Диаграмма PDC](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/PDC.PNG)  
## Лабораторная 3

## Лабораторная 4
-Тема курсовой работы: Проектирование автоматизированной системы расчёта инженерных работ в сфере телекоммуникаций.

-Функциональная модель разрабатывается с точки зрения менеджера проекта, который будет непосредственно заниматься расчетом стоимости инженерных работ для разработки плана проекта.

-Объектом моделирования является процесс расчёта сметы на работы. 

-Целью моделирования является определение автоматизируемых процессов и наглядное представление взаимодействия блоков разрабатываемой автоматизированной системы расчета стоимости инженерных работ.
 
 
 IDEF0 Контекстная: 
 
 ![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Контексная%20диаграмма.PNG)
 
 
 IDEF0 Процессов:
 
  ![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Idef0%20все%20блоки.PNG)
  
  IDEF0 декомпозиция процесса определения требований к проекту:
  
   ![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Декомпозиция%20А1.PNG) 
   
   IDEF0 декомпозиция процесса расчёта стоимости инженерных работ:
   
   ![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Декомпозиция%20А2.PNG) 
   
   IDEF0 декомпозиция процесса вывода о готовности вхождения в проект:
   
   ![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Ltrjvgjpbwbz%20F3.PNG) 

## Лабораторная 5

- Определение конфигурации технических средств: ноутбук для разработки и ноутбук на рабочем месте менеджера проекта для проверки системы.

- Определение конфигурации программных средств: Microsoft Visual Studio -  интегрированная среда разработки программного обеспечения.

- Определение допустимых видов хранилищ и их размещения: реалиционная база данных

- Декомпозиция в диаграмму потоков данных DFD была произведена из блоков: А21, А22, А23.

DFD для блока А21:

![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/ДФД%20для%20проверки%20аккаунта.PNG)

DFD для блока А22:

![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/ДФД%20для%20ввода%20данных.PNG)

DFD для блока А23:

![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/ДФД%20для%20расчёта.PNG)

Классификаторы:

![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/БД.PNG)

* "Параметры проекта" - хранит освновную информацию об основных параметрах проекта ;
* "Тип работ" - хранит информацию о типе работ, которые планируются в проекте;
* "Инженеры" - хранит информацию об инженерах, которые работают в организации ;
* "Аккаунты" -  хранит информацию о данных менеджеров проектов для входа в систему.

## Лабораторная 6

Завершение идентификации всех потоков путём построения ERD (диаграммы классов без атрибутов) для всех потоков.

* ERD для потоков:

![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Диаграмма%20потоков.png)

* ERD для модулей:

![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Модули.png)

* ERD для ролей:

![](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Роли.png)

## Курсовой проект

# Эффект от проекта

Для расчета эффекта от проекта будем сравнивать ручной труд менеджера проекта и используемую систему.
Рассматриваемый период – 1 год (12 месяцев).
Менеджер проекта = 1;
Проектов в месяц = 5;

* С использованием ИС

Время расчёта стоимости для менеджера: 

Заполнение параметров проекта из ТЗ – 10 мин.


Расчёт стоимости проеведения работ – 5 мин.

* Ручной труд

Время расчёта стоимости для менеджера: 

Заполнение параметров проекта из ТЗ – 20 мин.


Расчёт стоимости проеведения работ – 60 мин.


* Расчет экономии времени от реализации проекта для блока А22

* С использованием ИС

За один месяц: 

10 мин * 5 = 50 мин.

За рассматриваемый период:

50 мин. * 12 = 600 мин. = 10 ч. 

* Ручной труд

За один месяц: 

20 мин * 5 = 100 мин.

За рассматриваемый период:

100 мин. * 12 = 1200 мин. = 20 ч.

* Расчет экономии времени от реализации проекта для блока А32
* С использованием ИС

За один месяц: 

5 мин * 5 = 25 мин.

За рассматриваемый период:

25 мин. * 12 = 300 мин. = 5 ч. 

* Ручной труд

За один месяц: 

60 мин * 5 = 300 мин. = 5 ч.

За рассматриваемый период:

300 мин. * 12 = 3600 мин. = 60 ч. 

* Таким образом:

10+5= 15 ч/час в автоматизированной системе

20+60=80 ч/час через ручной труд

Итого выгода: 80-15= 65 ч/час

* Определение числовых показателей для трудозатрат на разработку программных средств:

Расчеты, выполненные первым методом FPA IFPUG, позволяют оценить сложность требуемых для создания информационной системы программных средств в 64 выровненных функциональных точек, а объем программного кода на языках программирования высокого уровня - 2880 строк кода.

Расчеты, выполненные вторым методом COCOMO II, позволяют оценить общие трудозатраты проекта разработки программных средств в 9 человеко-месяцев, а ожидаемую продолжительность проекта – в 7 месяцев 

[Текст курсовой работы](https://github.com/BoyarintsevaI/projectSystem.github.io/blob/master/Курсач%20проектирование%20инф%20систем%20(Бояринцева).docx)


