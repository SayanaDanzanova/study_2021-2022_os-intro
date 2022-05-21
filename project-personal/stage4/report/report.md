---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап четвертый"
author: "Данзанова Саяна Зоригтоевна"

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
Добавить к сайту ссылки на научные и библиометрические ресурсы.

# Ход работы
1. Добавили ссылки на соц. сети и некоторые сайты (рис.1,2)

![рис. 1](1.jpg){ #fig:001 width=90% }

![рис. 2](2.jpg){ #fig:002 width=90% }

2. Сделать пост по прошедшей неделе (рис.3,4)

![рис. 3](3.jpg){ #fig:003 width=90% }

![рис. 4](4.jpg){ #fig:004 width=90% }

3. Добавить пост на тему "Создание презентаций" (рис. 3,5)

![рис. 5](5.jpg){ #fig:005 width=90% }
# Вывод
Добавили к сайту ссылки на литературные источники. Сделали 2 поста: пост по прошедшей неделе и пост на тему "Создание презентации"