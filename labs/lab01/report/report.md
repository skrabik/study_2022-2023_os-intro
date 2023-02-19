---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Установка OC Linux"
author: "Бабенко Роман Игоревич"

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

# Цель работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Выполнение лабораторной работы

Виртуальна машина была установлена и настроена в первом семестре, поэтому сразу перехожу к выполнению "Домашнего задания"

Для того, чтобы найти версию ядра, вводим: (рис. @fig:001).

![](image/1.jpg){#fig:001 width=70%}

Для того, чтобы найти частоту процессора, вводим: (рис. @fig:002).

![](image/2.jpg){#fig:002 width=70%}

Для того, чтобы найти модель процессора, вводим: (рис. @fig:003).

![](image/3.jpg){#fig:003 width=70%}

Для того, чтобы найти объём доступной оперативной памяти, вводим: (рис. @fig:004).

![](image/4.jpg){#fig:004 width=70%}

Для того, чтобы найти тип гипервизора, вводим: (рис. @fig:005).

![](image/5.jpg){#fig:005 width=70%}

Для того, чтобы найти тип файловой системы, вводим: (рис. @fig:006).

![](image/6.jpg){#fig:006 width=70%}

Для того, чтобы найти тип последовательность монтирования файловых систем, вводим: (рис. @fig:007).

![](image/7.jpg){#fig:007 width=70%}

# Выводы

В ходе выполнения лабораторной работы я освежил в памяти, как нужно устанавливать операционную систему на виртуальную машину и настраивать необходимые сервисы.
