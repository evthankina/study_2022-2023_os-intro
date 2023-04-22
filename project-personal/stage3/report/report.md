---
## Front matter
title: "Отчет"
subtitle: "2 этап индивидуального проекта"
author: "Щанкина Екатерина Викторовна"

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

Выполнение следующего этапа проекта

# Задание


1. Добавить информацию о навыках (Skills).
2. Добавить информацию об опыте (Experience).
3. Добавить информацию о достижениях (Accomplishments).
4. Сделать пост по прошедшей неделе.
5. Добавить пост на тему по выбору


# Выполнение лабораторной работы

1. Добавила информацию о навыках. (рис. @fig:001)

![skills](image/1.png){#fig:001 width=70%}

2. Добавила инфомацию об опыте. (рис. @fig:002)

![experience](image/2.png){#fig:002 width=70%}

3. Проверила, что все появилось на моем сайте. (рис. @fig:003)

![сайт](image/3.png){#fig:003 width=70%}

4. Создала папку для нового поста. (рис. @fig:004)

![папка](image/4.png){#fig:004 width=70%}

5. Ввела текст в файл и создала новый пост о событии на прошлой неделе. (рис. @fig:005) (рис. @fig:006) 

![текст](image/5.png){#fig:005 width=70%}

![сайт](image/6.png){#fig:006 width=70%}

6. Создала папку для нового поста по выбору и ввела текст в файл. (рис. @fig:007)

![текст](image/7.png){#fig:007 width=70%}

7. Создала пост о легковесных языках программирования.(рис. @fig:008)

![создание](image/8.png){#fig:008 width=70%}

8. Проверила посты. (рис. @fig:009)

![проверка](image/9.png){#fig:009 width=70%}


# Выводы

Выполнила все задачи 3 этапа индивидуального проекта.

