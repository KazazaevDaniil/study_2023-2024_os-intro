---
## Front matter
title: "Отчёт по четвертой стадии проекта"
subtitle: "Дисциплина: операционные системы"
author: "Казаазев Даниил Михайлович"

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
lot: false # List of tables
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

# Задание

1. Зарегистрироваться на ресурсах и добавить их ссылки на сайт
2. Сделать пост о прошедшей неделе
3. Добавить пост на тему по выбору

# Выполнение работы

Для начала регистрируюсь на всех сайтах, приложэенных к этапу проекта. (рис. [-@fig:001],[-@fig:002],[-@fig:003],[-@fig:004],[-@fig:005],[-@fig:006])

![eLibrary](image/1.png){#fig:001 width=30%}

![ORCID](image/2.png){#fig:002 width=70%}

![Mendeley ](image/3.png){#fig:003 width=70%}

![Academia.edu](image/4.png){#fig:004 width=70%}

![GitHub](image/5.png){#fig:005 width=70%}

![Google Scholar](image/6.png){#fig:006 width=70%}

Перейдя в директорию content/authors/admin, редактирую файл index.md, а точнее пункт social (рис. [-@fig:007]).

![Добавление ссылок](image/7.png){#fig:007 width=70%}

Перейдя в директорию content/post и, после создания папок для нового поста и еженедельного отчета, перехожу в папку нового еженельного отчета и начинаю редактировать файл index.md. (рис. [-@fig:008])

![Еженедельный пост](image/8.png){#fig:008 width=70%}

Перехожу в content/post/post3 и делаю пост про создание отчетов по ГОСТу. (рис. [-@fig:009])

![Новый пост](image/9.png){#fig:009 width=70%}

# Выводы

Был выполнен четвертый этап индивидуального проекта
