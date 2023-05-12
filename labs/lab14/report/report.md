---
## Front matter
title: "Лабораторная работа 14"
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

Приобретение практических навыков работы с именованными каналами.

# Задание

Изменить текст представленных в лабораторной работе программ, использующих каналы.

# Выполнение лабораторной работы

1. С помощью циклов for и while, а также функций sleep() и clock() изменен текст программ server.c и client.c, представленных в лабораторной работе, так, что может работать несколько клиентов, клиенты передают текущее время раз в пять секунд, сервер работает на протяжении 30 секунд (рис. @fig:001-@fig:002). Если сервер при завершении работы не закроет канал, при следующей активации невозможно будет создать новый.

![Изменения server.c](image/001.png){#fig:001 width=70%}

![Изменения client.c](image/002.png){#fig:002 width=70%}

![Работа сервера](image/003.png){#fig:003 width=70%}

2. Работа программ проверена с помощью активации сервера и двух клиентов (рис. @fig:003-@fig:005).

![Клиент 1](image/004.png){#fig:004 width=70%}

![Клиент 2](image/005.png){#fig:005 width=70%}

# Выводы

Необходимые изменения произведены, навык работы с именованными каналами получен. 
