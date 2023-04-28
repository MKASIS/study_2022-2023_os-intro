---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 4"
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

Зарегестрироваться на сайтах и написать пост 

# Выполнение лабораторной работы

0. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте

1. eLibrary : https://elibrary.ru/;

![HUGO](image/1.png){#fig:001 width=90%}

2. Google Scholar : https://scholar.google.com/;

![.](image/2.png){#fig:002 width=90%}

3. ORCID : https://orcid.org/;

![HUGO](image/3.png){#fig:003 width=90%}

4. Mendeley : https://www.mendeley.com/;

![HUGO](image/4.png){#fig:004 width=90%}

5. ResearchGate : https://www.researchgate.net/;

 ![HUGO](image/5.png){#fig:005 width=90%}
 
6. Academia.edu : https://www.academia.edu/;ъ

![HUGO](image/6.png){#fig:006 width=90%}
 
7. arXiv : https://arxiv.org/;
 
![HUGO](image/7.png){#fig:007 width=90%}

8. github : https://github.com/.

![HUGO](image/8.png){#fig:008 width=90%}

9. Сделать пост по прошедшей неделе

![HUGO](image/9.png){#fig:009 width=90%}


# Выводы

Мы все сделали

# Список литературы{.unnumbered}

::: {#refs}
:::
