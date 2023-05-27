---
## Front matter
title: "Шестой этап индивидуального проекта"
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

- Сделать поддержку английского и русского языков.
- Разместить элементы сайта на обоих языках.
- Разместить контент на обоих языках.
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору (на двух языках).



# Выполнение этапа

1. Обеспечена возможность размещения информации на другом языке с помощью файла language.yaml (рис. @fig:001). Созданы две директории для разных языков (рис. @fig:002).

![Изменение файла language.yaml](image/001.png){#fig:001 width=70%}

![Директории для разных языков](image/002.png){#fig:002 width=70%}

2. Вся информация переразмещена на русском языке (рис. @fig:003-@fig:013)

![Повторное размещение информации на русском (1)](image/003.png){#fig:003 width=70%}

![Повторное размещение информации на русском (2)](image/004.png){#fig:004 width=70%}

![Повторное размещение информации на русском (3)](image/005.png){#fig:005 width=70%}

![Повторное размещение информации на русском (4)](image/006.png){#fig:006 width=70%}

![Повторное размещение информации на русском (5)](image/007.png){#fig:007 width=70%}

![Повторное размещение информации на русском (6)](image/008.png){#fig:008 width=70%}

![Повторное размещение информации на русском (7)](image/009.png){#fig:009 width=70%}

![Повторное размещение информации на русском (8)](image/010.png){#fig:010 width=70%}

![Повторное размещение информации на русском (9)](image/011.png){#fig:011 width=70%}

![Повторное размещение информации на русском (10)](image/012.png){#fig:012 width=70%}

![Повторное размещение информации на русском (11)](image/013.png){#fig:013 width=70%}

3. Создан пост по прошедшей неделе (рис. @fig:014). Создан пост по теме "Планы на лето" (по выбору) (рис. @fig:015).

![Пост по прошедшей неделе](image/014.png){#fig:014 width=70%}

![Пост по теме по выбору](image/015.png){#fig:015 width=70%}

4. Сайт работает корректно (рис. @fig:016).

![Итоговый вид сайта](image/016.png){#fig:016 width=70%}

# Выводы

Необходимая информация добавлена, сайт видоизменен, навык работы получен. 
