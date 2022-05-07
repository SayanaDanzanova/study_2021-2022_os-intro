---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап второй"
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
Добавить к сайту данные о себе. Добавить пост на тему: "Управление версиями. Git."

# Ход работы
1. Список добавляемых данных.
- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).

Сначала мы изменили данные о себе. Для этого необходимо зайти в файл content/authors/admin/_index.md и изменить там необходимые данные о себе (рис. 1). Также в папку content/authors/admin/ необходимо положить свою фотографию и назвать её avatar.jpg (рис. 2). Далее проверяем информацию на сайте. (рис. 3).
![рис. 1](1.jpg){ #fig:001 width=90% }

![рис. 2](2.jpg){ #fig:002 width=90% }

![рис. 3](3.jpg){ #fig:003 width=90% }

2. Пост по прошедшей неделе
В шаблон добавила еонтент для поста.
![рис. 4](4.jpg){ #fig:004 width=90% }

![рис. 5](5.jpg){ #fig:005 width=90% }

![рис. 6](6.jpg){ #fig:006 width=90% }

3.	Добавить пост.
Я выбраа тему Git. Решила не создавать новый пост и просто изменила старый. Для это я зашла в файл content/post/getting-started/index.md и изменила в нем контент для нашего поста. (рис. 4)
![рис. 7](7.jpg){ #fig:007 width=90% }

![рис. 8](8.jpg){ #fig:008 width=90% }

![рис. 9](9.jpg){ #fig:009 width=90% }

# Вывод
Я азобралась как обновлять данные о себе, а также создавать новый пост.