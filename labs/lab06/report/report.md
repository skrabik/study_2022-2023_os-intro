---
## Front matter
title: "Отчет по лабораторной работе №6"
subtitle: "Дисциплина: Компьютерные науки и технологии программирования"
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

Ознакомится с инструментами поиска файлов и фильтрации текстовых данных. Приобрести практические навыки: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

# Выполнение лабораторной работы

С помощью данной команды записываем в файл  file.txt содержимое каталога /etc (рис. @fig:001).

![Запись в файл](image/1.jpg){#fig:001 width=70%}

Дописываем в этот файл названия файлов, содержащихся  в домашнем каталоге (рис. @fig:002).

![Дописываем данные в файл](image/2.jpg){#fig:002 width=70%}

Выводим в консоль все файлы, имеющие расширение "conf" (рис. @fig:003).

![Выводим имена файлов в консоль](image/3.jpg){#fig:003 width=70%}

Записываем имена этих файлов в отдельный файл (рис. @fig:004).

![Запись в отдельный файл](image/4.jpg){#fig:004 width=70%}

Определяем, какие файлы в домашнем каталоге имеют имена, которые начинаются на "c"  (рис. @fig:005).

![Файлы на "c"](image/5.jpg){#fig:005 width=70%}

Выводим на экран имена файлов из каталога /etc, начинающиеся с символа "h" (рис. @fig:006).

![Вывод файлов из каталога /etc](image/6.jpg){#fig:006 width=70%}

В фоновом режиме запускаем процесс, который записывает в  файл файлы, имена которых начинаются с "log" (рис. @fig:007).

![Запускаем запись в файл в фоновом режиме](image/7.jpg){#fig:007 width=70%}

Удаляем файл "logfile" (рис. @fig:008).

![Удаление файла](image/8.jpg){#fig:008 width=70%}

Запускаем в консоль в фоновом режиме редактор gedit (рис. @fig:009).

![Запуск "gedit" в фоновом режиме](image/9.jpg){#fig:009 width=70%}

Определяем идентификатор процесса (рис. @fig:0010).

![Айди процесса](image/10.jpg){#fig:0010 width=70%}

Завершаем процесс с помощью команды kill (рис. @fig:0011).

![Завершаем  процесс](image/11.jpg){#fig:0011 width=70%}

Выполняем команду df (рис. @fig:0012).

![df](image/12.jpg){#fig:0012 width=70%}

Выполняем команду du  (рис. @fig:0013).

![du](image/13.jpg){#fig:0013 width=70%}

Воспользовавшись командой find, выводим имена  всех директорий, имеющихся в домашнем каталоге

![Вывод с помощью find](image/14.jpg){#fig:0014 width=70%}



# Выводы

В ходе выполнения работы я научился искать файлы и фильтровать текстовые файлы, научился управлять процессами, проверять использование диска и обслуживать файловую систему.
