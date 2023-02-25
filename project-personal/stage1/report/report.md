---
## Front matter
title: "Индивидуальный проект. Первый Этап"
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

Создание персонального сайта с помощью GitHub. Размещение своего проекта на хостинге git.

# Задание

Размещение на GitHub pages заготовки для персонального сайта.

# Выполнение лабораторной работы

1. Скачивание ПО hugo для дальнейшей работы

![Скачанный файл](image/hugo_download.jpg){#fig:001 width=70%}

2. Создание папки bin и перемещение туда файла hugo

![Папка bin с необходимым файлом](image/bin.jpg){#fig:002 width=70%}

3. Клонирование шаблона hugo academic для персонального сайта

![Создание репозитория с названием blog](image/blog.jpg){#fig:003 width=70%}

4. Первые этапы создания сайта

![Ввод нужной команды](image/binhugo.jpg){#fig:004 width=70%}

5. Проверка сайта на локальном уровне.

![Сайт](image/sayt.jpg){#fig:005 width=70%}

6. Создание именного репозитория для проекта сайта YazgeldiOrazgeldiyev.github.io

![Мой репозиторий](image/Yazgeldi_repos.jpg){#fig:006 width=70%}

7. Клонирование файлов репозитория для сайта

![Клонирование](image/repos_clone.jpg){#fig:007 width=70%}

8. Создание ветки

![Добавление файла для активации репозитория](image/add_site.jpg){#fig:008 width=70%}

9. Ввод команды origin для правильной работы ветки main

![Команда для точной работы](image/origin_push.jpg){#fig:009 width=70%}

10. Добавление ветки main и создание папки public

![Команда для добавления ветки](image/add_public.jpg){#fig:010 width=70%}

11. Комментирование папки public

![Комментирование](image/public_comment.jpg){#fig:011 width=70%}

12. Добавление файлов сайта 

![Созданные файлы в нашей папке](image/files.jpg){#fig:012 width=70%}

13. Проверка сайта на работу вне системы 

![Рабочий сайт](image/site_work.jpg){#fig:013 width=70%}

# Выводы

Мы создали персональный сайт по шаблону, используя необходимые репозитории.
