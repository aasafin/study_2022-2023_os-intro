---
## Front matter
title: "Лабораторная работа 7"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приоб-
ретение навыков практической работы по просмотру каталогов и файлов; манипуляций
с ними.

# Задание

Выполнить описанные в работе действия с оболочкой mc и её встроенным текстовым редактором.

# Теоретическое введение

Командная оболочка — интерфейс взаимодействия пользователя с операционной системой и программным обеспечением посредством команд.
Midnight Commander (или mc) — псевдографическая командная оболочка для UNIX/Linux
систем. 

# Выполнение лабораторной работы

Вызвана справка по mc (рис. @fig:001). Открыт mc (рис. @fig:002). Осуществлены несколько операций, в их числе копирование (рис. @fig:003). Выполнены основные команды меню левой панели (рис. @fig:004-@fig:006). 

![man mc](image/001.png){#fig:001 width=70%}

![mc](image/002.png){#fig:002 width=70%}

![Копирование](image/003.png){#fig:003 width=70%}

![Быстрый просмотр файла](image/004.png){#fig:004 width=70%}

![Информация о файле](image/005.png){#fig:005 width=70%}

![Дерево](image/006.png){#fig:006 width=70%}

С помощью подменю файл: просмотрено и отредактировано содержимое hello.asm (рис. @fig:007, @fig:008); создан каталог 001 (рис. @fig:009); скопирован lab5 в 001  (рис. @fig:010).

![Просмотр файла](image/007.png){#fig:007 width=70%}

![Редактирование](image/008.png){#fig:008 width=70%}

![Создание каталога 001](image/009.png){#fig:009 width=70%}

![Копирование файла в каталог](image/010.png){#fig:010 width=70%}

С помощью подменю команда выполнены: поиск в файловой системе с условиями (рис. @fig:011); повторение одной из предыдущих команд (рис. @fig:012); переход в домашний каталог (рис. @fig:013); просмотр файла расширений (рис. @fig:014).

![Поиск файлов с условиями](image/011.png){#fig:011 width=70%}

![Выполнение команды из истории](image/012.png){#fig:012 width=70%}

![Возвращение в домашний каталог](image/013.png){#fig:013 width=70%}

![Файл расширений](image/014.png){#fig:014 width=70%}

С помощью подменю настройки изменен интерфейс (рис. @fig:015).

![Изменение интерфейса mc](image/015.png){#fig:015 width=70%}

Создан файл text.txt, в него скопирован текст hello.asm (рис. @fig:016). Установлено выделение синтаксиса (рис. @fig:017). Удалена строка (рис. @fig:018). Скопирован фрагмент (рис. @fig:019). Фрагмент перенесен (рис. @fig:020). Изменение отменено (рис. @fig:021). Файл изменен в конце и в начале (рис. @fig:022).

![Текст, скопированный в text.txt](image/016.png){#fig:016 width=70%}

![Выделение синтаксиса](image/017.png){#fig:017 width=70%}

![Удаление строки](image/018.png){#fig:018 width=70%}

![Копирование фрагмента](image/019.png){#fig:019 width=70%}

![Перенос фрагмента на другую строку](image/020.png){#fig:020 width=70%}

![Отмена изменений](image/021.png){#fig:021 width=70%}

![Изменение файла в начале и в конце](image/022.png){#fig:022 width=70%}


# Выводы

Описанные действия с mc произведены, навык работы получен.
