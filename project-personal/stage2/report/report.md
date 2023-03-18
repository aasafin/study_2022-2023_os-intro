---
## Front matter
title: "Второй этап индивидуального проекта"
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

- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору:
    Управление версиями. Git.
    Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Выполнение этапа

1. Размещена фотография выполняющего индивидуальный проект в content/authors/admin (рис. @fig:001).

2. Размещены биография (рис. @fig:004) и краткая информация (рис. @fig:002) в файл content/authors/admin/index.md (туда же вносятся все последующие изменения кроме постов). 

3. Размещена информация об интересах (рис. @fig:002).

4. Размещена информация об образовании (рис. @fig:003).

![Добавление фотографии](image/001.png){#fig:001 width=70%}

![Добавление имени и интересов](image/002.png){#fig:002 width=70%}

![Добавление информации об образовании](image/003.png){#fig:003 width=70%}

![Добавление биографии](image/004.png){#fig:004 width=70%}

5. Созданы посты за прошлую неделю и по git (рис. @fig:005, @fig:007). Для этого созданы соответствующие папки в content/post. Итоговый вид постов можно видеть на рис. @fig:006, @fig:008.

![Создание поста за прошедшую неделю](image/005.png){#fig:005 width=70%}

![Вид поста на сайте](image/006.png){#fig:006 width=70%}

![Создание поста по git](image/007.png){#fig:007 width=70%}

![Вид поста по git](image/008.png){#fig:008 width=70%}

# Выводы

Необходимая информация добавлена, сайт видоизменен (можно проверить по адресу aasafin.github.io). 
