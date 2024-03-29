---
## Front matter
title: "Отчёт по лабораторной работе №13"
subtitle: "Средства, применяемые при разработке программного обеспечения в ОС типа UNIX/Linux"
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

Приобрести простейшие навыки разработки, анализа, тестирования и отладки при-
ложений в ОС типа UNIX/Linux на примере создания на языке программирования
С калькулятора с простейшими функциями.

# Задание

Приобрести простейшие навыки разработки, анализа, тестирования и отладки при-
ложений в ОС типа UNIX/Linux на примере создания на языке программирования
С калькулятора с простейшими функциями.

# Выполнение лабораторной работы

1. Создала подкаталог (рис. [-@fig:001]).

![Создание подкаталога](image/1.png){#fig:001 width=70%}

2. Создала в нем файлы

![Создание файлов](image/2.png){#fig:002 width=70%}

3. Заполнила первый файл

![Заполнение файла](image/3.png){#fig:003 width=70%}

4. Заполнила второй файл

![Заполнение файла](image/4.png){#fig:004 width=70%}

5. Заполнила третий файл

![Заполнение файла](image/5.png){#fig:005 width=70%}

6. Скомпилировала файлы

![Компиляция](image/6.png){#fig:006 width=70%}

7. Создала файл и заполнила его

![Заполнение файла](image/7.png){#fig:007 width=70%}

8. Запустила откладчик

![Запуск](image/8.png){#fig:008 width=70%}

9. Запустила программу

![Запуск](image/9.png){#fig:009 width=70%}

10. Команды просмотра

![Просмотр](image/10.png){#fig:010 width=70%}

11. Установила точку останова

![Точка останова](image/11.png){#fig:011 width=70%}

12. Вывела о ней информацию

![Информация](image/12.png){#fig:012 width=70%}

13. Запустила программу

![Запуск](image/13.png){#fig:013 width=70%}

14. Значение на этапе

![Значение](image/14.png){#fig:014 width=70%}

15. Значение на этапе

![Значение](image/15.png){#fig:015 width=70%}

16. Убрала точку останова

![Точка останова](image/16.png){#fig:016 width=70%}

17. Код файла

![Код](image/17.png){#fig:017 width=70%}

18. Код файла

![Код](image/18.png){#fig:018 width=70%}

# Выводы

Я приобрела простейшие навыки разработки, анализа, тестирования и отладки при-
ложений в ОС типа UNIX/Linux на примере создания на языке программирования
С калькулятора с простейшими функциями.
