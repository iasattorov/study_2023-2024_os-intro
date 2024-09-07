---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Стадия 2"
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

Разместить мою фотографию на сайте, рассказать о себе, указать мои развлечения и хобби, а также написать два поста: о прошедшей неделе и на выбор.

# Выполнение лабораторной работы

Запустим наш сервер. (рис. [-@fig:1])

![запуск сервера](image/p2s1.png){#fig:1 width=100%}

Сменим стоковую фотографию на нашу. (рис. [-@fig:2])

![смена аватарки](image/p2s2.png){#fig:2 width=100%}

Поменяем стоковую китайщину на мое имя и фамилию. (рис. [-@fig:3])

![смена имени](image/p2s3.png){#fig:3 width=100%}

Укажем интересы. (рис. [-@fig:4])

![интересы](image/p2s4.png){#fig:4 width=100%}

Укажем про имеющееся у меня обучение (рис. [-@fig:5]),(рис. [-@fig:6])

![обучение](image/p2s5.png){#fig:5 width=100%}

![обучение](image/p2s6.png){#fig:6 width=100%}

Укажем умения/навыки и хобби. (рис. [-@fig:7])

![навыки](image/p2s7.png){#fig:7 width=100%}

Укажем информацию обо мне на главной странице. (рис. [-@fig:8])

![обо мне](image/p2s8.png){#fig:8 width=100%}

Общий вид стартовой шапки после изменений. (рис. [-@fig:9])

![новый вид](image/p2s9.png){#fig:9 width=100%}

Пост на выбор на тему "Управление версиями git". (рис. [-@fig:10])

![пост на выбор](image/p2s10.png){#fig:10 width=100%}

Пост о прошедшей неделе. (рис. [-@fig:11])

![пост о прошедшей неделе](image/p2s11.png){#fig:11 width=100%}

# Выводы

Информация о владельце сайта была указана на этом же сайте.
