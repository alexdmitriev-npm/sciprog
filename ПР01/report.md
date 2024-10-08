---
# Front matter
title: "Отчёт по 1 этапу проекта"
subtitle: "Сайт научного работника"
author: "Александр Дмитриев"

# Generic otions
lang: ru-RU
toc-title: "Содержание"

# Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

# Pdf output format
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
### Fonts
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
## Misc options
indent: true
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Подготовить репозиторий на основе шаблона. Ознакомиться с генератором сайтов hugo.

# Выполнение работы

Клонирую репозиторий с шаблоном сайта-визитки.

![Создание репозитория из шаблона](image/01.png){ #fig:001 width=70% height=70%}

Создаю локальные репозитории для размещение сайта.

![Создание локальных репозиториев](image/02.png){ #fig:002 width=70% height=70%}

Тестирую запуск hugo.

![Инициализация hugo](image/03.png){ #fig:003 width=70% height=70%}

Подготовка репозитория для файлов сайта.

![Подготовка репозитория](image/04.png){ #fig:004 width=70% height=70%}

Связывание папки public с подготовленным репозиторием.

![Подготовка папки public](image/05.png){ #fig:005 width=70% height=70%}

Развертывание сайта на основе HitHub Pages.

![Развертывание сайта](image/06.png){ #fig:006 width=70% height=70%}

# Выводы

Подготовили репозиторий и установили hugo.