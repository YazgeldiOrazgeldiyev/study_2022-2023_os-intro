---
## Front matter
title: "Лабораторная работа 9"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Задание

Emacs представляет собой мощный экранный редактор текста, написанный на языке
высокого уровня Elisp.

# Выполнение лабораторной работы

1. Скачивание и открытие emacs

![Установка программы](image/1.jpg){#fig:001 width=70%}

2. Набрали текст из методички

![Наш текст](image/2.jpg){#fig:002 width=70%}

3. Редактировали файл

![Измененный файл](image/3.jpg){#fig:003 width=70%}

4. Выводили список буферов на экран

![Список буферов](image/4.jpg){#fig:004 width=70%}

5. Поделили фрейм на 4

![4 фрейма](image/5.jpg){#fig:005 width=70%}

6. Работали с буфером в 4 фреймах

![Буфер](image/6.jpg){#fig:006 width=70%}

7. Произвели поиск слов в тексте

![Поиск](image/7.jpg){#fig:007 width=70%}

8. Работали с поиском

![Поиск в файле](image/8.jpg){#fig:008 width=70%}

# Выводы

Я познакомился с операционной системой Linux. Получил практические навыки работы с редактором Emacs.

