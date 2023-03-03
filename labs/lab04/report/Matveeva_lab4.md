---
## Front matter
title: "Лабораторная рбота №4"
subtitle: "Основы интерфейса взаимодействия
пользователя с системой Unix на уровне командной строки"
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


Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.




# Выполнение лабораторной работы



1. Определите полное имя вашего домашнего каталога. Далее относительно этого ката-
лога будут выполняться последующие упражнения.

![...](image/1.png){#fig:001 width=90%}

2. Перейдите в каталог /tmp.
 
![...](image/2.png){#fig:002 width=90%}

 3. Выведите на экран содержимое каталога /tmp
 
![...](image/3.png){#fig:003 width=90%}

4. пределите, есть ли в каталоге /var/spool подкаталог с именем cron? Есть.
  
![...](image/5.png){#fig:005 width=90%}  
  
5. Перейдите в Ваш домашний каталог и выведите на экран его содержимое. Опре-
делите, кто является владельцем файлов и подкаталогов


![...](image/6.png){#fig:006 width=90%}

![...](image/7.png){#fig:007 width=90%}
  
6.  В домашнем каталоге создайте новый каталог с именем newdir.
  
![...](image/8.png){#fig:008 width=90%}

7. В каталоге ~/newdir создайте новый каталог с именем morefun
  
![...](image/10.png){#fig:010 width=90%}

8. В домашнем каталоге создайте одной командой три новых каталога с именами
letters, memos, misk. Затем удалите эти каталоги одной командой.

![...](image/11.png){#fig:011 width=90%}

9. Попробуйте удалить ранее созданный каталог ~/newdir командой rm. Проверьте,
был ли каталог удалён.

![...](image/13.png){#fig:013 width=90%} 

10.  Удалите каталог ~/newdir/morefun из домашнего каталога. Проверьте, был ли
каталог удалён.

![...](image/14.png){#fig:014 width=90%}

11. С помощью команды man определите, какую опцию команды ls нужно использо-
вать для просмотра содержимое не только указанного каталога, но и подкаталогов,
входящих в него.
 CD
 
 ![...](image/16.png){#fig:016 width=90%}
  
  ![...](image/17.png){#fig:017 width=90%}
  
  PWD
  
  ![...](image/18.png){#fig:018 width=90%}
  
  ![...](image/19.png){#fig:019 width=90%}
  
 MKDIR
 
 ![...](image/20.png){#fig:020 width=90%} 
  
  ![...](image/21.png){#fig:021 width=90%}
  
  RMDIR
  
  ![...](image/22.png){#fig:022 width=90%}
  
  ![...](image/20\3.png){#fig:023 width=90%}
  
  RM
  
  ![...](image/25.png){#fig:024 width=90%}
  
  ![...](image/26.png){#fig:026 width=90%}
  
12. Используя информацию, полученную при помощи команды history, выполните мо-
дификацию и исполнение нескольких команд из буфера команд

![...](image/29.png){#fig:029 width=90%}
  
# Выводы

научились работать с системой посредством командной строки

# Список литературы{.unnumbered}

::: {#refs}
:::
