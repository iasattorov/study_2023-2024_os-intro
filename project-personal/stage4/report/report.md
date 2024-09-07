---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Стадия 4"
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

Зарегистрироваться на множестве сайтов, так или иначе связанных с научной деятельностью, и внести их на наш сайт. А также написать два поста.

# Выполнение лабораторной работы

Зарегистрированный аккаунт на eLibrary (рис. [-@fig:1])

![фото подтверждение](image/p4s1.png){#fig:1 width=100%}

Зарегистрированный аккаунт на Google Scholar (рис. [-@fig:2])

![фото подтверждение](image/p4s2.png){#fig:2 width=100%}

Зарегистрированный аккаунт на ORCID (рис. [-@fig:3])

![фото подтверждение](image/p4s3.png){#fig:3 width=100%}

Зарегистрированный аккаунт на Mendeley (рис. [-@fig:4])

![фото подтверждение](image/p4s4.png){#fig:4 width=100%}

Зарегистрированный аккаунт на ReseacrhGate (рис. [-@fig:5])

![фото подтверждение](image/p4s5.png){#fig:5 width=100%}

Зарегистрированный аккаунт на Academia.edu (рис. [-@fig:6])

![фото подтверждение](image/p4s6.png){#fig:6 width=100%}

Зарегистрированный аккаунт на arXiv (рис. [-@fig:7])

![фото подтверждение](image/p4s7.png){#fig:7 width=100%}

Все добавленные сайты в профиле (рис. [-@fig:8])

![общий вид](image/p4s8.png){#fig:8 width=100%}

Пост по прошедшей неделе (рис. [-@fig:9])

![пост о неделe](image/p4s9.png){#fig:9 width=100%}

Пост по выбору (рис. [-@fig:10])

![пост на выбор](image/p4s10.png){#fig:10 width=100%}



# Выводы

Все необходимые сайты были добавлены в наш профиль. А также были написаны два поста.
