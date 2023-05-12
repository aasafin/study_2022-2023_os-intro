---
## Front matter
title: "Пятый этап индивидуального проекта"
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

Целью индивидуального проекта является приобретение навыков создания персонального сайта с помощью hugo и github.

# Задание

- Разместить информацию о проектах.
- Сделать пост по прошедшей неделе.
- Добавить пост по теме "Языки научного программирования".


# Выполнение этапа

1. Размещена информация о проектах (рис. @fig:001-@fig:002).

2. Размещен пост по прошедшей неделе (далее скриншоты с изменениями в текстовых документах приводиться не будут, так как они не представляют ценности с точки зрения отчета) (рис. @fig:003).

3. Размещен пост по теме "Языки научного программирования" (рис. @fig:004).

![Проекты (в текстовом документе)](image/001.png){#fig:001 width=70%}

![Проекты (на сайте)](image/002.png){#fig:002 width=70%}

![Пост по прошедшей неделе](image/003.png){#fig:003 width=70%}

![Пост по теме "Языки научного программирования"](image/004.png){#fig:004 width=70%}


# Выводы

Необходимая информация добавлена, сайт видоизменен (можно проверить по адресу aasafin.github.io). 
