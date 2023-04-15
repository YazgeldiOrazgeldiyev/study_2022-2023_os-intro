---
## Front matter
title: "Лабораторная работа № 10"
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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.

# Задание

1. Написать скрипт, который при запуске будет делать резервную копию самого себя (то
есть файла, в котором содержится его исходный код) в другую директорию backup
в вашем домашнем каталоге. При этом файл должен архивироваться одним из архиваторов на выбор zip, bzip2 или tar. Способ использования команд архивации
необходимо узнать, изучив справку.
2. Написать пример командного файла, обрабатывающего любое произвольное число
аргументов командной строки, в том числе превышающее десять. Например, скрипт
может последовательно распечатывать значения всех переданных аргументов.
3. Написать командный файл — аналог команды ls (без использования самой этой команды и команды dir). Требуется, чтобы он выдавал информацию о нужном каталоге
и выводил информацию о возможностях доступа к файлам этого каталога.
4. Написать командный файл, который получает в качестве аргумента командной строки
формат файла (.txt, .doc, .jpg, .pdf и т.д.) и вычисляет количество таких файлов
в указанной директории. Путь к директории также передаётся в виде аргумента командной строки.


# Выполнение лабораторной работы

1. Создал директорию бэкап для сохранения копии файла

![Создание папки](image/1.jpg){#fig:001 width=70%}

2. Написал скрипт, который создает резервную копию самого себя и архивируется в формат tar

![Скрипт 1](image/2.jpg){#fig:002 width=70%}

3. Дал права скрипту, и проверил директорию

![Права доступа скрипта](image/3.jpg){#fig:003 width=70%}

4. Создал скрипт, который обрабатывает произвольное число аргументов(в том числе больше 10)

![Скрипт 2](image/4.jpg){#fig:004 width=70%}

5. Дал права скрипту и проверил его работу

![Проверка](image/5.jpg){#fig:005 width=70%}

6. Написал скрипт - аналог ls, который будет выдавать информацию о нужном каталоге

![Скрипт 3](image/6.jpg){#fig:006 width=70%}

7. Вывел информацию о моей директории

![Информация](image/7.jpg){#fig:007 width=70%}

8. Написать командный файл, который получает в качестве аргумента командной строки 
формат файла и выдает число таких файлов

![Скрипт 4](image/8.jpg){#fig:008 width=70%}

![Проверка кода](image/9.jpg){#fig:008 width=70%}

# Выводы

Изучил основы программирования в оболочке ОС UNIX/Linux. Научился писать
небольшие командные файлы.

