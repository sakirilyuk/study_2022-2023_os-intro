---
## Front matter
title: "Лабораторная работа №12"
subtitle: "Операционные системы"
author: "Кирилюк Светлана Алексеевна"

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

Изучить основы программирования в оболочке ОС UNIX. Научиться писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

# Выполнение лабораторной работы

Я создала новый файл с командой touch и перешла в него при помощи mc, после чего написала скрипт программы (рис. @fig:fig1). Затем я написала команду, которая даёт все права пользователю на работу с файлом, и выполнила программу (рис. @fig:fig2).

![Скрипт 1-ой программы](image/fig1.png){#fig:fig1 width=70%}

![Выполнение 1-ой программы](image/fig2.png){#fig:fig2 width=70%}

Вновь создав файл и открым его в mc, я написала новый скрипт (рис. @fig:fig3). И снова выполнила программу (рис. @fig:fig4).

![Скрипт 2-ой программы](image/fig3.png){#fig:fig3 width=70%}

![Выполнение 2-ой программы](image/fig4.png){#fig:fig4 width=70%}

Создав последний файл и зпустив его, я вновь написала скрипт (рис. @fig:fig5) и выполнила программу (рис. @fig:fig6).

![Скрипт 3-й программы](image/fig5.png){#fig:fig5 width=70%}

![Выполнение 3-й программы](image/fig6.png){#fig:fig6 width=70%}

# Выводы

В ходе лабораторной работы я изучила основы программирования в оболочке ОС UNIX. Научилась писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.
