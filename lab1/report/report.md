---
## Front matter
title: "Лабораторная работа №1. Julia. Установка и настройка. Основные принципы"
subtitle: "Дисциплина: Компьютерный практикум по статистическому анализу данных"
author: "Манаева Варвара Евгеньевна, НФИбд-01-20"

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

Подготовить рабочее пространство и инструментарий для работы с языком программирования Julia, на простейших примерах
познакомиться с основами синтаксиса Julia.

## Задачи [@lab:1]

1. Установите под свою операционную систему Julia, Jupyter (разделы 1.3.1 и 1.3.2).
2. Используя Jupyter Lab, повторите примеры из раздела 1.3.3.
3. Выполните задания для самостоятельной работы (раздел 1.3.4).

# Выполнение лабораторной работы

## Повторение задания

![Повторение (1)](image/1.png){#fig:001 width=80%}

![Повторение (2)](image/2.png){#fig:002 width=80%}

## Выполнение самостоятельной части

### Выдержки из документации [@julia:oficialdoc]

![read()](image/3.png){#fig:003 width=80%}

![readline()](image/4.png){#fig:004 width=80%}

![readlines()](image/5.png){#fig:005 width=80%}

![readdlm()](image/6.png){#fig:006 width=80%}

![println()](image/7.png){#fig:007 width=80%}

![print()](image/8.png){#fig:008 width=80%}

![show()](image/9.png){#fig:009 width=80%}

![write()](image/10.png){#fig:0010 width=80%}

![parse()](image/11.png){#fig:0011 width=80%}

### Прикладные применения

![Решения (1)](image/12.png){#fig:0012 width=80%}

![Решения (2)](image/13.png){#fig:0013 width=80%}

# Выводы по проделанной работе

## Вывод

В результате выполнения работы мы на простейших примерах ознакомились с основами синтаксиса языка Julia.

Были записаны скринкасты выполнения и защиты лабораторной работы.

Ссылки на скринкасты:

- [Выполнение, Youtube](https://youtu.be/U2erDbl_bVM)
- [Выполнение, Rutube](https://rutube.ru/video/e07b58518ff3ba12420d7607ac808505)
- [Защита презентации, Youtube](https://youtu.be/_WcTOLN6ZI0)
- [Защита презентации, Rutube](https://rutube.ru/video/3f61e62d4606db8263061e840913bb53)

# Список литературы

