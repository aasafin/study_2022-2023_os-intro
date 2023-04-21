---
## Front matter
title: "Лабораторная работа 11"
author: "Сафин Андрей Алексеевич"

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

Изучить основы программирования в оболочке ОС UNIX. Научится писать более
сложные командные файлы с использованием логических управляющих конструкций
и циклов.

# Задание

Написать программы, описанные в лабораторной работе.

# Теоретическое введение

bash (Bourne Again Shell) - это интерпретатор команд, позволяющий пользователю взаимодействовать с операционной системой через терминал. Bash способен считывать не только команды, вводимые в интерактивном режиме, но и файлы с командами. Эту функцию можно использовать для написания командных файлов.

# Выполнение лабораторной работы

1. Создана программа, которая анализирует командную строку с ключами и в зависимости от них по-разному выполняет grep (рис. @fig:001). Как видно, программа написана корректно - составленная команда grep выводится верно (рис. @fig:002). Лишь по некой причине оболочка не считывает >> как перенаправление вывода (что она делает при ручном введении той же команды.

![Первая программа](image/001.png){#fig:001 width=70%}

![Выполнение первой программы](image/002.png){#fig:002 width=70%}

2. Язык Си автору лабораторной работы не известен.

3. Написана программа, создающая файлы вида n.tar, 1<=n<=N, а затем удаляющая их же(рис. @fig:003). Программа работает корректно (рис. @fig:004).  

![Вторая программа](image/003.png){#fig:003 width=70%}

![Выполнение второй программы](image/004.png){#fig:004 width=70%}

4. Создана программа, запаковывающая в архив все файлы из данной директории, котрые редактировались в течение недели (рис. @fig:005). Программа выполнена (рис. @fig:006).

![Третья программа](image/005.png){#fig:005 width=70%}

![Выполнение третьей программы](image/006.png){#fig:006 width=70%}

# Выводы

Описанные командные файлы созданы, навык работы с bash получен.
