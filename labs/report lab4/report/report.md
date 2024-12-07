---
## Front matter
title: "Компьютерный практикум по статистическому анализу данных лабораторная работа №4"
subtitle: "Линейная алгебра"
author: "Ким Илья Владиславович НФИбд-01-21"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Основной целью работы является изучение возможностей специализированных пакетов Julia для выполнения и оценки эффективности операций над объектами линейной
алгебры.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 4.2.

2. Выполните задания для самостоятельной работы (раздел 4.4).

# Выполнение работы. Повтор примеров из раздела 4.2

## 4.2.1. Поэлементные операции над многомерными массивами

![](image/1.png){#fig:001 width=70%}

![](image/2.png){#fig:002 width=70%}

![](image/3.png){#fig:003 width=70%}

![](image/4.png){#fig:004 width=70%}

![](image/5.png){#fig:005 width=70%}

## 4.2.2. Транспонирование, след, ранг, определитель и инверсия матрицы

![](image/6.png){#fig:006 width=70%}

![](image/7.png){#fig:007 width=70%}

![](image/8.png){#fig:008 width=70%}

![](image/9.png){#fig:009 width=70%}

## 4.2.3. Вычисление нормы векторов и матриц, повороты, вращения

![](image/10.png){#fig:010 width=70%}

![](image/11.png){#fig:011 width=70%}

![](image/12.png){#fig:012 width=70%}

![](image/13.png){#fig:013 width=70%}

![](image/14.png){#fig:014 width=70%}

## 4.2.4. Матричное умножение, единичная матрица, скалярное произведение

![](image/15.png){#fig:015 width=70%}

![](image/16.png){#fig:016 width=70%}

![](image/17.png){#fig:017 width=70%}

# 4.2.5. Факторизация. Специальные матричные структуры

![](image/18.png){#fig:018 width=70%}

![](image/19.png){#fig:019 width=70%}

![](image/20.png){#fig:020 width=70%}

![](image/21.png){#fig:021 width=70%}

![](image/22.png){#fig:022 width=70%}

![](image/23.png){#fig:023 width=70%}

![](image/24.png){#fig:024 width=70%}

![](image/25.png){#fig:25 width=70%}

![](image/26.png){#fig:26 width=70%}

![](image/27.png){#fig:27 width=70%}

![](image/28.png){#fig:28 width=70%}

![](image/29.png){#fig:29 width=70%}

![](image/30.png){#fig:30 width=70%}

![](image/31.png){#fig:31 width=70%}

![](image/32.png){#fig:32 width=70%}

![](image/33.png){#fig:33 width=70%}

![](image/34.png){#fig:34 width=70%}

![](image/35.png){#fig:35 width=70%}

![](image/36.png){#fig:36 width=70%}

# 4.2.6. Общая линейная алгебра

![](image/37.png){#fig:37 width=70%}

![](image/38.png){#fig:38 width=70%}

![](image/39.png){#fig:39 width=70%}

# 4.4 Задания для самостоятельного выполнения

## 4.4.1. Произведение векторов

![](image/40.png){#fig:40 width=70%}

## 4.4.2. Системы линейных уравнений

![](image/41.png){#fig:41 width=70%}

![](image/42.png){#fig:42 width=70%}

![](image/43.png){#fig:43 width=70%}

![](image/44.png){#fig:44 width=70%}

![](image/45.png){#fig:45 width=70%}

## 4.4.3. Операции с матрицами

![](image/46.png){#fig:46 width=70%}

![](image/47.png){#fig:47 width=70%}

![](image/48.png){#fig:48 width=70%}

![](image/49.png){#fig:49 width=70%}

![](image/50.png){#fig:50 width=70%}

![](image/51.png){#fig:51 width=70%}

## 4.4.4. Линейные модели экономики

![](image/52.png){#fig:52 width=70%}

![](image/53.png){#fig:53 width=70%}

![](image/54.png){#fig:54 width=70%}

![](image/55.png){#fig:55 width=70%}

![](image/56.png){#fig:56 width=70%}

![](image/57.png){#fig:57 width=70%}

# Выводы

Использую Jupyter lab повторил примеры из раздела 4.2 и выполнил задания для самостоятельной работы. Изучил возможности специальных пакетов Julia для выполнения и оценки эффективности операций над объектами линейной алгебры.