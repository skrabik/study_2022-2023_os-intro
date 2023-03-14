---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе номер 6
subtitle: Линукс это хорошо.
  - Бабенко Р.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 11 марта 2023 год

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Бабеноко Роман Игоревич 
  * студент
  * направление "Математика и механика"
  * Российский университет дружбы народов


:::
::: {.column width="30%"}


:::
::::::::::::::

# Вводная часть

С помощью данной команды записываем в файл  file.txt содержимое каталога /etc (рис. @fig:001).

![Запись в файл](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\1.jpg){#fig:001 width=70%}

Дописываем в этот файл названия файлов, содержащихся  в домашнем каталоге (рис. @fig:002).

![Дописываем данные в файл](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\2.jpg){#fig:002 width=70%}

Выводим в консоль все файлы, имеющие расширение "conf" (рис. @fig:003).

![Выводим имена файлов в консоль](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\3.jpg){#fig:003 width=70%}

Записываем имена этих файлов в отдельный файл (рис. @fig:004).

![Запись в отдельный файл](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\4.jpg){#fig:004 width=70%}

Определяем, какие файлы в домашнем каталоге имеют имена, которые начинаются на "c"  (рис. @fig:005).

![Файлы на "c"](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\5.jpg){#fig:005 width=70%}

Выводим на экран имена файлов из каталога /etc, начинающиеся с символа "h" (рис. @fig:006).

![Вывод файлов из каталога /etc](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\6.jpg){#fig:006 width=70%}

В фоновом режиме запускаем процесс, который записывает в  файл файлы, имена которых начинаются с "log" (рис. @fig:007).

![Запускаем запись в файл в фоновом режиме](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\7.jpg){#fig:007 width=70%}

Удаляем файл "logfile" (рис. @fig:008).

![Удаление файла](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\8.jpg){#fig:008 width=70%}

Запускаем в консоль в фоновом режиме редактор gedit (рис. @fig:009).

![Запуск "gedit" в фоновом режиме](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\9.jpg){#fig:009 width=70%}

Определяем идентификатор процесса (рис. @fig:0010).

![Айди процесса](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\10.jpg){#fig:0010 width=70%}

Завершаем процесс с помощью команды kill (рис. @fig:0011).

![Завершаем  процесс](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\11.jpg){#fig:0011 width=70%}

Выполняем команду df (рис. @fig:0012).

![df](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\12.jpg){#fig:0012 width=70%}

Выполняем команду du  (рис. @fig:0013).

![du](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\13.jpg){#fig:0013 width=70%}

Воспользовавшись командой find, выводим имена  всех директорий, имеющихся в домашнем каталоге

![Вывод с помощью find](C:\Users\baben\OneDrive\Рабочий стол\Labs\study_2022-2023_os-intro\labs\lab06\report\image\14.jpg){#fig:0014 width=70%}



# Выводы

В ходе выполнения работы я научился искать файлы и фильтровать текстовые файлы, научился управлять процессами, проверять использование диска и обслуживать файловую систему.
