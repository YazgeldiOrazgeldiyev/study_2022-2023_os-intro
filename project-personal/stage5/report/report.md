---
## Front matter
title: "Индивидуальный проект. Этап 5"
subtitle: "Операционные системы"
author: "Оразгелдиев Язгелди"

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

Редактура собственного сайта на шаблоне с гитхаба

# Задание

Добавить к сайту элементы:
- Сделать записи для персональных проектов.
- Сделать пост по прошедшей неделе.
- Добавить пост на тему: Языки научного программирования.

# Выполнение лабораторной работы

1. Отредактировал записи для персональных проектов и проверил на локальном уровне

![Результат изменений](image/1.jpg){#fig:001 width=70%}

2. Написал пост по прошедшей 4-ой неделе работы по Операционным системам

![Пост](image/2.jpg){#fig:002 width=70%}

3. Сделал пост на тему "Языки научного программирования". Написал про некоторые из них в небольшой статье

![Пост на тему](image/3.jpg){#fig:003 width=70%}

4. Проверил добавленные посты на сайте

![Пост по теме и по прошедшей неделе](image/4.jpg){#fig:004 width=70%}

5. Внес все новые данный на сам сайт и увидел результат работы

![Результат](image/5.jpg){#fig:005 width=70%}

# Выводы

- Провел последнюю редактуру собственного сайта на шаблоне с гитхаба. 
- Проделал работу с постами в виде отчетов по прошедшей неделе и научных статей с интернета.

