---
# Front matter
lang: ru-RU
title: "Отчет по лабораторной работе 8"
subtitle: "Командная оболочка Midnight Commander"
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

# Цель работы

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними. 

# Задание

- Изучить информацию о mc и его встроенном редакторе.
- Запуск mc и изучение его структуры и меню.
- Выполнение основнымх команд панелей, подменю Файл, подменю Команда и подменю Настройки.
- Работа с файлом с помощью встроенного редактора mc.
- Включение/выключение подсветки синтаксиса, используя меню редактора.

# Выполнение лабораторной работы

**Задание по mc**

Изучила информацию о mc. Запустила из командной строки mc, изучила его структуру и меню.

![Команды](image/1.png){ #fig:001 width=70% }

![man mc](image/2.jpg){ #fig:001 width=70% }

![Левая панель](image/3.jpg){ #fig:001 width=70% }

![Файл](image/4.jpg){ #fig:001 width=70% }

![Команда](image/5.jpg){ #fig:001 width=70% }

![Настройки](image/6.jpg){ #fig:001 width=70% }

![Правая панель](image/7.jpg){ #fig:001 width=70% }



![Меню mc (F9)](image/8.jpg){ #fig:001 width=70% }

![Удаление (F8)](image/9.jpg){ #fig:001 width=70% }

![Создание каталога (F7)](image/10.jpg){ #fig:001 width=70% }

![Перемещение файла (F6)](image/11.jpg){ #fig:001 width=70% }

![Копирование файла (F5)](image/12.jpg){ #fig:001 width=70% }

![Изменение файла (F4)](image/13.jpg){ #fig:001 width=70% }

![Просмотр файла (F3)](image/14.jpg){ #fig:001 width=70% }

![Выбор пользовательского меню (F2)](image/15.jpg){ #fig:001 width=70% }

![Подсказка (F1)](image/16.jpg){ #fig:001 width=70% }

*Работа с правой панелью:*

![Быстрый просмотр](image/17.png){ #fig:001 width=70% }

![Дерево](image/18.png){ #fig:001 width=70% }

![Информация](image/19.png){ #fig:001 width=70% }

*Работа с подменю Файл:*

![Просмотр файла](image/20.png){ #fig:001 width=70% }

![Редактирование файла](image/21.png){ #fig:001 width=70% }

![Создание каталога](image/22.png){ #fig:001 width=70% }

![Копирование файла в каталог](image/23.png){ #fig:001 width=70% }

![Скопированный файл](image/24.png){ #fig:001 width=70% }

*Работа с подменю Команда:*

![Поиск файла](image/25.png){ #fig:001 width=70% }

![Содержимое найденного файла](image/26.png){ #fig:001 width=70% }

![Выбор и повторение предыдущих команд](image/27.png){ #fig:001 width=70% }

![История команд](image/28.png){ #fig:001 width=70% }

![Анализ файла меню](image/29.png){ #fig:001 width=70% }

![Содержимое файла меню](image/30.png){ #fig:001 width=70% }

![Анализ файла расширений](image/31.png){ #fig:001 width=70% }

![Содержимое файла расширений](image/32.png){ #fig:001 width=70% }

*Работа с подменю Настройки:*

![Внешний вид](image/33.png){ #fig:001 width=70% }

![Оформление](image/34.png){ #fig:001 width=70% }

![Настройки панели](image/35.png){ #fig:001 width=70% }

**Задание по встроенному редактору mc**

![Команды](image/36.png){ #fig:001 width=70% }

Открыла файл на F4. Вставила текст.

![Изначальный текст](image/37.png){ #fig:001 width=70% }

Удалила строку (ctrl +y)

Выделила строку и скопировала ее на новую (F3-выделение, F5- копирование, shift+insert – вставка)

Выделила строку и перенесла ее на новую (F6)

Сохранила(F2)

Отмена последнего действия (ctrl+u, существенно ничего не изменилось, так как последнее мое действие было- сдвиг курсора)

Перешла в конец и написала рандомный текст (Ctrl+End)

Перешла в начало и написала рандомный текст (Ctrl+Home)

Сохранила и закрыла (F10)

![Итоговый текст](image/38.png){ #fig:001 width=70% }

Открыла файл С++.

![Открытие файла (F4)](image/39.png){ #fig:001 width=70% }

![Содержимое файла С++](image/40.png){ #fig:001 width=70% }

Настройки > общие

Выключила подсветку синтаксиса. 

![Настройки редактора](image/41.png){ #fig:001 width=70% }

![Сохранение и выход](image/42.png){ #fig:001 width=70% }

# Вывод

Я вполне освоила основные возможности командной оболочки Midnight Commander. 
Приобрела навыки практической работы по просмотру каталогов и файлов; манипуляций с ними
