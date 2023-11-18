---
## Front matter
title: "Лабораторная работа №2"
subtitle: "Дисциплина: Компьютерный практикум по статистическому моделированию"
author: "Манаева Варвара Евгеньевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Техническое оснащение:

- Персональный компьютер с операционной системой Windows 10;
- Планшет для записи видеосопровождения и голосовых комментариев;
- Microsoft Teams, использующийся для записи скринкаста лабораторной работы;
- Приложение Pycharm для редактирования файлов формата *md*;
- *pandoc* для конвертации файлов отчётов и презентаций.

# Цели и задачи работы
## Цель

Изучить несколько структур данных, реализованных в Julia, научиться применять их и операции над ними для решения задач.

## Задачи [@lab:2]

1. Используя Jupyter Lab, повторите примеры из раздела 2.2.
2. Выполните задания для самостоятельной работы (раздел 2.4).

# Выполнение лабораторной работы

## Повторение примеров

1. Реализация кортежей (@fig:101, @fig:102)
2. Реализация словарей (@fig:102, @fig:103)
3. Реализация множеств (@fig:104, @fig:105, @fig:106)
4. Реализация массивов (@fig:106, @fig:107, @fig:108, @fig:109, @fig:1010)

![Повторение примеров (1)](image/1_1.png){#fig:101 width=80%}

![Повторение примеров (2)](image/1_2.png){#fig:102 width=80%}

![Повторение примеров (3)](image/1_3.png){#fig:103 width=80%}

![Повторение примеров (4)](image/1_4.png){#fig:104 width=80%}

![Повторение примеров (5)](image/1_5.png){#fig:105 width=80%}

![Повторение примеров (6)](image/1_6.png){#fig:106 width=80%}

![Повторение примеров (7)](image/1_7.png){#fig:107 width=80%}

![Повторение примеров (8)](image/1_8.png){#fig:108 width=80%}

![Повторение примеров (9)](image/1_9.png){#fig:109 width=80%}

![Повторение примеров (10)](image/1_10.png){#fig:1010 width=80%}


## Самостоятельная работа

1. Пересечение и объединение множеств $A = \{ 0, 3, 4, 9 \} $, $B = \{ 1, 3, 4, 7 \}$ и $C = \{ 0, 1, 2, 4, 7, 8, 9 \}$ (@fig:201).

![Функции и формула из задания 1](image/2_1.png){#fig:201 width=80%}

2. Примеры с выполнением операций над множествами элементов разных типов (@fig:202)

![Примеры выполнения операций](image/2_2_1.png){#fig:2021 width=80%}

![Примеры выполнения операций](image/2_2_2.png){#fig:2022 width=80%}

3. Создать разными способами несколько видов массивов (@fig:2031, @fig:2032)

![Массивы для пункта 3 (1)](image/2_3_1.png){#fig:2031 width=80%}

![Массивы для пункта 3 (2)](image/2_3_2.png){#fig:2032 width=80%}

![Массивы для пункта 3 (3)](image/2_3_3.png){#fig:2033 width=80%}

![Массивы для пункта 3 (4)](image/2_3_4.png){#fig:2034 width=80%}

![Массивы для пункта 3 (5)](image/2_3_5.png){#fig:2035 width=80%}

![Массивы для пункта 3 (6)](image/2_3_6.png){#fig:2036 width=80%}

![Массивы для пункта 3 (7)](image/2_3_7.png){#fig:2037 width=80%}

![Массивы для пункта 3 (8)](image/2_3_8.png){#fig:2038 width=80%}

![Массивы для пункта 3 (9)](image/2_3_9.png){#fig:2039 width=80%}

![Массивы для пункта 3 (10)](image/2_3_10.png){#fig:20310 width=80%}

![Массивы для пункта 3 (11)](image/2_3_11.png){#fig:20311 width=80%}

![Массивы для пункта 3 (12)](image/2_3_12.png){#fig:20312 width=80%}

![Массивы для пункта 3 (13)](image/2_3_13.png){#fig:20313 width=80%}

![Массивы для пункта 3 (14)](image/2_3_14.png){#fig:20314 width=80%}

![Массивы для пункта 3 (15)](image/2_3_15.png){#fig:20315 width=80%}

![Массивы для пункта 3 (16)](image/2_3_16.png){#fig:20316 width=80%}

![Массивы для пункта 3 (17)](image/2_3_17.png){#fig:20317 width=80%}

![Массивы для пункта 3 (18)](image/2_3_18.png){#fig:20318 width=80%}

![Массивы для пункта 3 (19)](image/2_3_19.png){#fig:20319 width=80%}

![Массивы для пункта 3 (20)](image/2_3_20.png){#fig:20320 width=80%}

![Массивы для пункта 3 (21)](image/2_3_21.png){#fig:20321 width=80%}

![Массивы для пункта 3 (22)](image/2_3_22.png){#fig:20322 width=80%}

![Массивы для пункта 3 (23)](image/2_3_23.png){#fig:20323 width=80%}

![Массивы для пункта 3 (24)](image/2_3_24.png){#fig:20324 width=80%}

![Массивы для пункта 3 (25)](image/2_3_25.png){#fig:20325 width=80%}

![Массивы для пункта 3 (26)](image/2_3_26.png){#fig:20326 width=80%}

![Массивы для пункта 3 (27)](image/2_3_27.png){#fig:20327 width=80%}

![Массивы для пункта 3 (28)](image/2_3_28.png){#fig:20328 width=80%}

![Массивы для пункта 3 (29)](image/2_3_29.png){#fig:20329 width=80%}

![Массивы для пункта 3 (30)](image/2_3_30.png){#fig:20330 width=80%}

![Массивы для пункта 3 (31)](image/2_3_31.png){#fig:20331 width=80%}

4. Создать массив квадратов натуральных чисел от 1 до 100 (@fig:204)

![Массив натуральных чисел](image/2_4.png){#fig:204 width=80%}

5. С помощью пакета `Primes` сгенерировать массив первых 168 простых чисел, определим 89-е простое число, создадим срез 
массива с 89-го по 99-й элементов (@fig:205)

![Работа с простыми числами](image/2_5.png){#fig:205 width=80%}

6. Реализовать формулы (@fig:2061, @fig:2062)

![Вычисление выражений (1)](image/2_6_1.png){#fig:2061 width=80%}

![Вычисление выражений (2)](image/2_6_2.png){#fig:2062 width=80%}

# Выводы по проделанной работе

## Вывод

В результате выполнения работы мы изучили несколько структур данных, реализованных в Julia, и научились применять их и
операции над ними для решения задач.

Были записаны скринкасты выполнения и защиты лабораторной работы.

Ссылки на скринкасты:

- [Выполнение, Youtube](https://youtu.be/M99ajOiDJEI)
- [Выполнение, Rutube](https://rutube.ru/video/16e589900388d33c8c5c872209de6635)
- [Защита презентации, Youtube](https://youtu.be/xZljAOs4-QU)
- [Защита презентации, Rutube](https://rutube.ru/video/1cf0c1d791e26feb36e21af028e006f3)

# Список литературы

