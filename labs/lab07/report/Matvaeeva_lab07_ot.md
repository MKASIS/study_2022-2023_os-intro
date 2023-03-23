---
## Front matter
title: "Лабораторная рбота №7"
subtitle: "Анализ файловой системы Linux.Команды для работы с файлами и каталогами"
author: "Матвеева Анастасия Сергеевна"

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


Познакомиться с операционной системой Linux. Получить практические навыки рабо-
ты с редактором vi, установленным по умолчанию практически во всех дистрибутивах.



# Выполнение лабораторной работы

0. Изучите информацию о mc, вызвав в командной строке man mc. Запустите из командной строки mc, изучите его структуру и меню

![...](image/1.png){#fig:001 width=90%}

![...](image/2.png){#fig:002 width=90%}

1. Создайте текстовой файл text.txt.Откройте этот файл с помощью встроенного в mc редактора

![...](image/3.png){#fig:003 width=90%}


2. Вставьте в открытый файл небольшой фрагмент текста, скопированный из любого другого файла или Интернета.
 
![...](image/7.png){#fig:007 width=90%}
 
3. Проделайте с текстом следующие манипуляции, используя горячие клавиши
 
 выделите фрагмент текста и скопируйте его на новую строку.
 
![...](image/8.png){#fig:008 width=90%}

Выделите фрагмент текста и перенесите его на новую строку.

![...](image/9.png){#fig:009 width=90%}

Сохраните файл

  ![...](image/6.png){#fig:006 width=90%}
  
  Перейдите в конец файла (нажав комбинацию клавиш) и напишите некоторый
текст.
  Перейдите в начало файла (нажав комбинацию клавиш) и напишите некоторый
текст.
 
![...](image/10.png){#fig:010 width=90%}
 
 ![...](image/11.png){#fig:011 width=90%}
 


 ![...](image/12.png){#fig:012 width=90%}
 
 5. Откройте файл с исходным текстом на некотором языке программирования (напри-
мер C или Java
 
 ![...](image/13.png){#fig:013 width=90%} 
 
  ![...](image/14.png){#fig:014 width=90%}
  


# Выводы

...


# Список литературы{.unnumbered}

::: {#refs}
:::
