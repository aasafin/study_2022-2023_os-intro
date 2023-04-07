---
## Front matter
title: "Лабораторная работа 9"
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

Познакомиться с операционной системой Linux. Получить практические навыки рабо-
ты с редактором Emacs.

# Задание

Выполнить описанные в работе действия с редактором emacs.

# Теоретическое введение

Emacs - это экранный текстовый редактор. Он позволяет работать с текстами с помощью буферов, окон, в которых эти буферы открываются, и команд, которые позволяют редактировать содержимое буферов.

# Выполнение лабораторной работы

1. Открыт emacs (рис. @fig:001). Вписан текст, файл сохранен (рис. @fig:002). Выполнены основные команды редактирования текста (вырезание, копирование, вставка строк и областей, перемещение курсора и отмена действий) (рис. @fig:003-@fig:010). 

![emacs](image/001.png){#fig:001 width=70%}

![Введен текст](image/002.png){#fig:002 width=70%}

![Вырезана строка](image/003.png){#fig:003 width=70%}

![Вставлена строка](image/004.png){#fig:004 width=70%}

![Скопирован и вставлен фрагмент](image/005.png){#fig:005 width=70%}

![Вырезан фрагмент](image/006.png){#fig:006 width=70%}

![Перемещён курсор (1)](image/007.png){#fig:007 width=70%}

![Перемещён курсор (2)](image/008.png){#fig:008 width=70%}

![Перемещён курсор (3)](image/009.png){#fig:009 width=70%}

![Перемещён курсор (4)](image/010.png){#fig:010 width=70%}

2. Выведен список активных буферов (рис. @fig:011). Через него открыт один из буферов (рис. @fig:012). Окно закрыто (рис. @fig:013). Введена команда открытия буфера без использования списка (рис. @fig:014).

![Окно с буферами](image/011.png){#fig:011 width=70%}

![Открыт другой буфер](image/012.png){#fig:012 width=70%}

![Закрыто окно](image/013.png){#fig:013 width=70%}

![Команда для смены буфера](image/014.png){#fig:014 width=70%}

3. Открыты несколько окон с разными буферами, в них введен разный текст (рис. @fig:015). 

![Несколько окон с разными буферами](image/015.png){#fig:015 width=70%}

4. Осуществлен поиск текста (рис. @fig:016) и перемещение по нему (рис. @fig:017). Затем поиск с заменой (hello --> BB) (рис. @fig:018). После чего выполнена команда M-s o, осуществляющая поиск в отдельном окне в отличие от C-s (рис. @fig:019).

![Поиск текста](image/016.png){#fig:016 width=70%}

![Перемещение по поиску](image/017.png){#fig:017 width=70%}

![Поиск с заменой](image/018.png){#fig:018 width=70%}

![Поиск в отдельном буфере](image/019.png){#fig:019 width=70%}

# Выводы

Описанные действия с emacs произведены, навык работы получен.
