---
## Front matter
title: "Лабораторная работа №7"
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

Основной целью работы является освоение специализированных пакетов Julia для обработки данных.

## Задачи [@lab:7]

1. Повторить примеры из раздела 7.2
2. Выполнить задания для самостоятельной работы из раздела 7.4

# Выполнение лабораторной работы

## Повторение примеров

Повторение примеров (@fig:001, @fig:002, @fig:003, @fig:004, @fig:005, @fig:006, @fig:007, @fig:008, @fig:009, @fig:0010
, @fig:0011, @fig:0012, @fig:0013, @fig:0014, @fig:0015, @fig:0016, @fig:0017, @fig:0018, @fig:0019)

![Повторение примеров (1)](image/1.png){#fig:001 width=80%}

![Повторение примеров (2)](image/2.png){#fig:002 width=80%}

![Повторение примеров (3)](image/3.png){#fig:003 width=80%}

![Повторение примеров (4)](image/4.png){#fig:004 width=80%}

![Повторение примеров (5)](image/5.png){#fig:005 width=80%}

![Повторение примеров (6)](image/6.png){#fig:006 width=80%}

![Повторение примеров (7)](image/7.png){#fig:007 width=80%}

![Повторение примеров (8)](image/8.png){#fig:008 width=80%}

![Повторение примеров (9)](image/9.png){#fig:009 width=80%}

![Повторение примеров (10)](image/10.png){#fig:0010 width=80%}

![Повторение примеров (11)](image/11.png){#fig:0011 width=80%}

![Повторение примеров (12)](image/12.png){#fig:0012 width=80%}

![Повторение примеров (13)](image/13.png){#fig:0013 width=80%}

![Повторение примеров (14)](image/14.png){#fig:0014 width=80%}

![Повторение примеров (15)](image/15.png){#fig:0015 width=80%}

![Повторение примеров (16)](image/16.png){#fig:0016 width=80%}

![Повторение примеров (17)](image/17.png){#fig:0017 width=80%}

![Повторение примеров (18)](image/18.png){#fig:0018 width=80%}

![Повторение примеров (19)](image/19.png){#fig:0019 width=80%}

## Самостоятельная работа [@julia:oficialdoc]

Самостоятельная работа (@fig:0020, @fig:0021, @fig:0022, @fig:0023, @fig:0024, @fig:0025, @fig:0026)

![Самостоятельная работа (1)](image/20.png){#fig:0020 width=80%}

![Самостоятельная работа (2)](image/21.png){#fig:0021 width=80%}

![Самостоятельная работа (3)](image/22.png){#fig:0022 width=80%}

![Самостоятельная работа (4)](image/23.png){#fig:0023 width=80%}

![Самостоятельная работа (5)](image/24.png){#fig:0024 width=80%}

![Самостоятельная работа (6)](image/25.png){#fig:0025 width=80%}

![Самостоятельная работа (7)](image/26.png){#fig:0026 width=80%}


# Выводы по проделанной работе

## Вывод

В результате выполнения работы мы освоили специальные пакеты Julia для обработки данных.

Были записаны скринкасты выполнения и защиты лабораторной работы.

Ссылки на скринкасты:

- [Выполнение, Youtube](https://youtu.be/2ZFSWA96Oss)
- [Выполнение, Rutube](https://rutube.ru/video/3c6ad613197acf13de45da29276d42b7)
- [Защита презентации, Youtube](https://youtu.be/2mnjZYnRBqE)
- [Защита презентации, Rutube](https://rutube.ru/video/f20a1a38de08db41bb292bd2eefec5ff)

# Список литературы

