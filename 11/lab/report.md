---
# Front matter
lang: ru-RU
title: "Отчет по лабораторной работе №11"
subtitle: "Программирование в командномпроцессоре ОС UNIX. Командные файлы."
author: "Акопян Изабелла Арменовна"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать небольшие командные файлы. 

# Задание

1. Написать скрипты, командные файлы.

2. Просмотреть файл лабораторной.

# Выполнение лабораторной работы

Работаю по материалам лабораторной работы №11:

>[Ссылка1](https://esystem.rudn.ru/pluginfile.php/1142517/mod_resource/content/2/008-lab_shell_prog_1.pdf)

Далее мне пришлось сначала ознакомиться с дополнительными материалами про скрипты на Bash:

>[Ссылка2](https://losst.ru/napisanie-skriptov-na-bash)

Написала скрипт, который при запуске делает резервную копию самого себя в директорию backup в моем домашнем каталоге. Файл архивируется tar. Изучила справку по tar. (рис. -@fig:001) (рис. -@fig:002)

![Справка о tar](image/1.png){ #fig:001 width=70% }

![Первый скрипт](image/5.png){ #fig:002 width=70% }

Написала пример командного файла, обрабатывающего любое произвольное число аргументов командной строки. (рис. -@fig:003) (рис. -@fig:004)

![Второй скрипт](image/6.png){ #fig:003 width=70% }

![Второй скрипт](image/7.png){ #fig:004 width=70% }

Написала командный файл — аналог команды ls (без использования самой этой команды и команды dir). Он выдает информацию о каталогах и выводит информацию о возможностях доступа к файлам этого каталога.(рис. -@fig:005)

![Третий скрипт](image/8.png){ #fig:005 width=70% }

Написала командный файл, который получает в качестве аргумента командной строки формат файла (.txt, .doc, .jpg, .pdf и т.д.) и который показывает список этих файлов. Путь к директории передала в виде аргумента командной строки.(рис. -@fig:006)

![Четвертый скрипт](image/9.png){ #fig:006 width=70% }

**Прочее**

Создание и открытие для редактирования файлов:(рис. -@fig:007)

![Команды](image/2.jpg){ #fig:007 width=70% }

Вызов командных файлов, скрипта: (рис. -@fig:008) (рис. -@fig:009)

![Команды](image/3.png){ #fig:008 width=70% }

![Команды](image/4.jpg){ #fig:009 width=70% }

# Вывод

Я успешно изучила основы программирования в оболочке ОС UNIX/Linux. Научилась писать небольшие командные файлы.

# Библиография

>[Ссылка1](https://esystem.rudn.ru/pluginfile.php/1142517/mod_resource/content/2/008-lab_shell_prog_1.pdf)

>[Ссылка2](https://losst.ru/napisanie-skriptov-na-bash)
