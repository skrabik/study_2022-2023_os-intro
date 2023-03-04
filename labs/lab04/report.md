---
## Front matter
title: "Отчёт по лабораторной работе №4"
subtitle: "Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки"
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

Научится взаимодействовать с системой при помощи командной строки.

# Выполнение лабораторной работы

Выводим расположение домашнего каталога (рис. @fig:001).

![Домашний каталог](image/1.png){#fig:001 width=70%}

Выводим содержимое каталога "tmp" (рис. @fig:002).

![Содержимое "tmp"](image/2.png){#fig:002 width=70%}

Определяем, существует ли подкаталог  "cron" в каталоге "/var/spool", ответ - нет (рис. @fig:003).

![Проверка наличия каталога](image/3.png){#fig:003 width=70%}

Выводим содержимое домашнего каталога, при этом указываем аргумент, который показывает владельца каталога (рис. @fig:004).

![Содержимое домашнего каталога](image/4.png){#fig:004 width=70%}

Создаём каталоги "nedir" и "morefun" (рис. @fig:005).

![Создание каталогов](image/5.png){#fig:005 width=70%}

Создаём одной командой три каталога (рис. @fig:006).

![Создание каталогов одной командой](image/6.png){#fig:006 width=70%}

Удаляем созданные каталоги командой "rmdir" (рис. @fig:007).

![Удаление каталогов](image/7.png){#fig:007 width=70%}

С помощью команды "man" смотрим какие опции нам нужны для "ls", чтобы вывести содержимое заданным образом (рис. @fig:008).

![Изучаем аргументы для "ls"](image/8.png){#fig:008 width=70%}

Используем команду "man" для просмотра описания следующих команд "cd, pwd, mkdir, rmdir, rm" (рис. @fig:009).

![Применяем "man" для разных команд](image/9.png){#fig:009 width=70%}

Используя "history" выполняем модификацию введённой ранее команды  (рис. @fig:010).

![Модифицируем команду](image/10.png){#fig:010 width=70%}

# Выводы

В ходе выполнения данной лабораторной работы я научился взаимодействовать с системой при помощи командной строки.
