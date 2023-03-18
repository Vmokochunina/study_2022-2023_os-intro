---
## Front matter
title: "Отчет по индивидуальному проекту"
subtitle: "2 этап"
author: "Мокочунина Влада Сергеевна"

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

Загрузить фото,написать информацию о себе (биография,образование,интересы),выложить два поста

# Задание

Загрузить фото,написать информацию о себе (биография,образование,интересы),выложить два поста

# Выполнение лабораторной работы

1.  Добавила фотографию для сайта (рис. [-@fig:001]).

![Фото](image/1.png){#fig:001 width=70%}

2. Написала информацию о себе ( биография,интересы,образование)

![Информация](image/2.png){#fig:002 width=70%}

3. Видим,что все синхронизировалось с сайтом

![Сайт](image/3.png){#fig:003 width=70%}

4. Написала пост о прошедшей неделе. Вот он уже на сайте

![Пост](image/4.png){#fig:004 width=70%}

5. Пишу пост о системе контроля версий

![Пишу пост](image/5.png){#fig:005 width=70%}

6. Видим пост на сайте

![Пост](image/6.png){#fig:006 width=70%}

# Выводы

Я научилась работать с сайтом: загружать фото,посты,информацию о себе

# Список литературы{.unnumbered}

::: {#refs}
:::
