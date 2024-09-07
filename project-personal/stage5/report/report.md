---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Стадия 5"
author: "Икромджон Сатторов"

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

Заполнить сайт до конца.

# Выполнение лабораторной работы

 Заполненный раздел предстоящих событий  (рис. [-@fig:1])

![предстоящие события](image/p5s1.png){#fig:1 width=100%}

 Заполненный раздел моих/понравившихся мне проектов.  (рис. [-@fig:2])

![проекты](image/p5s2.png){#fig:2 width=100%}

 То, что я изучаю, либо планирую изучать.  (рис. [-@fig:3])

![изучения](image/p5s3.png){#fig:3 width=100%}

 Мои публикации. Совместные либо самостоятельные. (рис. [-@fig:4])(рис. [-@fig:5])(рис. [-@fig:6])

![публикации](image/p5s4.png){#fig:4 width=100%}

![публикации](image/p5s5.png){#fig:5 width=100%} 

![публикации](image/p5s6.png){#fig:6 width=100%}

 Пост о прошедшей неделе  (рис. [-@fig:7])(рис. [-@fig:8])

![пост о неделе](image/p5s7.png){#fig:7 width=100%}

![пост о неделе](image/p5s8.png){#fig:8 width=100%}

 Пост на тему по выбору (рис. [-@fig:9])

![пост на выбор](image/p5s9.png){#fig:9 width=100%}





# Выводы

Заполненный до конца сайт.
