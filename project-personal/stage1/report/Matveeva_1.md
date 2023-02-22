---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 1"
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

Первоэтапная настройка личнного сайта

# Выполнение лабораторной работы

1. Скачиваем исполняемый файл HUGO через гитхаб

![HUGO](image/1.png){#fig:001 width=90%}

2. Оставляем только исполняемый файл 

![.](image/2.png){#fig:002 width=90%}

3. Создаем репозиторий  при помощи шаблона 

![HUGO](image/3.png){#fig:003 width=90%}

4. Клонируем репозиторий  

![HUGO](image/4.png){#fig:004 width=90%}

5. переходим в каталог и  проверяем файлы 

 ![HUGO](image/5.png){#fig:005 width=90%}
 
6. Прописываем команду и удаляем каталог public

![HUGO](image/6.png){#fig:006 width=90%}
 удалиляем
![HUGO](image/7.png){#fig:007 width=90%}

7. Выполням hugo server и там получаем ссылку на сайт 

![HUGO](image/9.png){#fig:009 width=90%}
 переходим на сайт 
![HUGO](image/66.png){#fig:066 width=90%}

8. Создаем еще один репозиторий с специальным названием ваше имя.гитхаб.ио

![HUGO](image/88.png){#fig:088 width=90%}

9. проверяем блок "ls"

![HUGO](image/13.png){#fig:013 width=90%}

10. клонируем репозиторий 

![HUGO](image/12.png){#fig:012 width=90%}

11. Проверяем 

![HUGO](image/13.png){#fig:013 width=90%}

12. переходим в каталог. используем команду checkout с ее помощью мы создаем ветку main. Дальше создаем файл README.md. И добовляем в гитхаб

![HUGO](image/14.png){#fig:014 width=90%}

13. Проверяем ветку 

![HUGO](image/15.png){#fig:015 width=90%}

14. прикрепряем его к нашемк репозиторию, так же автоматически создаеться каталог public

![HUGO](image/16.png){#fig:016 width=90%}

15. В гитигнор добавляем перед public "#"

![HUGO](image/17.png){#fig:017 width=90%}

16. повторяем команду из пункта 14

17. Синхронизировать файлы с нашем репозиторием 

![HUGO](image/18.png){#fig:018 width=90%}
![HUGO](image/19.png){#fig:019 width=90%}

18. Проверяем наш сайт и на этом конец 


# Выводы

Мы создали свой сайт 

# Список литературы{.unnumbered}

::: {#refs}
:::
