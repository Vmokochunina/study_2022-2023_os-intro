---
## Front matter
lang: ru-RU
title: Отчёт по лабораторной работе №10
subtitle: Программирование в командном процессоре ОС UNIX. Командные файлы
author:
  - Мокочунина В.С.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 11 апреля 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Мокочунина Влада Сергеевна
  * Российский университет дружбы народов
  * [vmokochunina@gmail.com](mailto:vmokochunina@gmail.com)
  * <https://github.com/Vmokochunina/study_2022-2023_os-intro.git>

:::
::: {.column width="30%"}
:::
::::::::::::::

# Вводная часть

## Цели и задачи

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать небольшие командные файлы

# Создание презентации

##  Я изучила справки по использованию команд архивациии (рис. @fig:001)

![zip](image/1.png){#fig:001 width=70%}

## 

![bzip2](image/2.png){#fig:002 width=70%}

## 

![tar](image/3.png){#fig:003 width=70%}

##  Написала скрипт, который при запуске будет делать резервную копию самого себя в другую директорию backup в вашем домашнем каталоге. При этом файл должен архивироваться одним из архиваторов на выбор zip, bzip2 или tar. 

![скрипт](image/4.png){#fig:004 width=70%}

##  Проверила на выполнение

![Выполнение](image/5.png){#fig:005 width=70%}

##  Написала пример командного файла, обрабатывающего любое произвольное число аргументов командной строки, в том числе превышающее десять. 

![скрипт](image/6.png){#fig:006 width=70%}

##  Проверила на выполнение

![Выполнение](image/7.png){#fig:007 width=70%}

##  Написала командный файл — аналог команды ls

![скрипт](image/8.png){#fig:008 width=70%}

##  Проверила на выполнение

![Выполнение](image/9.png){#fig:009 width=70%}

##  Написала командный файл, который получает в качестве аргумента командной строки формат файла (.txt, .doc, .jpg, .pdf и т.д.) и вычисляет количество таких файлов в указанной директории.

![скрипт](image/10.png){#fig:010 width=70%}

##  Проверила на выполнение

![Выполнение](image/11.png){#fig:011 width=70%}

## Результаты

Я изучила основы программирования в оболочке ОС UNIX/Linux. Научилась писать небольшие командные файлы

## Итоговый слайд

Спасибо за внимание

