---
# Front matter
lang: ru-RU
title: "Лабораторная работа №4"
subtitle: "Знакомство с операционной системой Linux"
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

Познакомиться с операционной системой Linux,получить практические навыки работы с консолью и некоторыми графическими менеджерами рабочих столов операционной системы.

# Задание

- Ознакомиться стеоретическим материалом.
- Загрузить компьютер.
- Перейти натекстовую консоль.
- Сколькотекстовых консолей доступно на вашем компьютере?
- Перемещаться междутекстовыми консолями.Какие комбинации клавиш необходимо при этом нажимать?
- Зарегистрироваться втекстовойконсоли операционной системы. Какой логин вы приэтом использовали? Какие символы отображаются при вводе пароля?
- Завершить консольный сеанс.Какую команду или комбинацию клавиш необходимо для этого использовать?
- Переключиться на графический интерфейс. Какую комбинацию клавиш для этого необходимо нажать?
- Ознакомиться с менеджером рабочих столов. Как называется менеджер,запускаемый по умолчанию?
- Поочерёдно зарегистрироваться в разных графических менеджерах рабочих столов(GNOME,KDE,XFCE) и оконных менеджерах (Openbox). Продемонстрировать разницу между ними, сделав снимки экрана (скриншоты). Какие графические менеджеры установлены на вашем компьютере?
- Изучить список установленных программ. Обратить внимание на предпочтительные программы для разных применений.Запустите поочерёдно браузер,текстовойредактор,текстовой процессор,эмулятор консоли.Укажите названия программ.


# Выполнение лабораторной работы

Перешла на текстовую консоль (Alt +Ctrl + F1). Всего числится 6 текстовых консолей на моем компьютере.
Чтобы перемещаться между текстовыми консолями,использую сочетание Alt + (F1-F6).
Чтобы зарегистрироваться в текстовой консоли, ввожу логин и пароль от своей учетной записи, с помощью которого я работаю в ДК.При вводе пароля символы не отображаются.
Завершаю консольный сеанс командой *logout*. Выхожу на графичекий интерфейс с помощью Ctrl + Alt + F7.

![Текстовая консоль](image/textcons.jpg){ #fig:001 width=70% }


Вышла, ознакомилась с менеджером рабочих столов.По умолчанию стоит "Классический Gnome".


![Менеджер рабочих столов](image/menedg.jpeg){ #fig:001 width=70% }


Ниже представлены примеры графических менеджеров рабочих столов и оконный менеджер OpenBox.


![GNOME](image/gnome.png){ #fig:001 width=70% }


![KDE Plazma](image/kde.jpeg){ #fig:001 width=70% }


![XFCE](image/xfce.png){ #fig:001 width=70% }


![OPENBOX](image/openbox.png){ #fig:001 width=70% }


Изучила список установленных программ. Запустила браузер, текстовой редактор, текстовой процессор и эмулятор консоли.


![Visual Studio Code](image/1.png){ #fig:001 width=70% }


![LibreOffice Writer](image/2.png){ #fig:001 width=70% }


![Terminal](image/3.png){ #fig:001 width=70% }


# Вывод

Познакомилась с операционной системой Linux,получила практические навыки работы с консолью и некоторыми графическими менеджерами рабочих столов операционной системы.
