---
## Front matter
title: "Отчет по лабораторной работе №1"
subtitle: "Операционные системы"
author: "Дмитрий Павлович Стрижов"

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

Целью данной работы является приобретение практических навыков
установки операционной системы на виртуальную машину, настройки ми-
нимально необходимых для дальнейшей работы сервисов.

# Задание

1. Установка Rocky Linux на виртуальную машину
2. Проверка параметров системы через консоль


# Выполнение лабораторной работы

Указываю папку, в которой будет находится виртуальная машина, выбираю необходимый образ (рис. [-@fig:001]).

![Настройки места установки виртуальной машины](image/1.png){#fig:001 width=70%}


Ставлю необходимое наименование хоста и пользователя (рис. [-@fig:002]).

![Наименование хоста и пользователя](image/2.png){#fig:002 width=70%}


Указываем количество оперативной памяти и ядер процессора (рис. [-@fig:003]).

![Оперативная память и количество ядер процессора](image/3.png){#fig:003 width=70%}

Выбираем диск, куда будет устанавливатся ОС (рис. [-@fig:004]).

![Выбор диска](image/6.png){#fig:004 width=70%}

Выбираю нужный регион (рис. [-@fig:005]).

![Выбор региона](image/7.png){#fig:005 width=70%}

Настраиваем соединение интернета (рис. [-@fig:006]).

![Настройка интернета](image/8.png){#fig:006 width=70%}

Устанавливаем пароль для администратора (рис. [-@fig:007]).

![Пароль для администратора](image/9.png){#fig:007 width=70%}

Настройка пользователя (рис. [-@fig:008]).

![Настройка пользователя](image/10.png){#fig:008 width=70%}

Проверяем версию Линукса (рис. [-@fig:009]).

![Проверка версии ОС](image/16.png){#fig:009 width=70%}

Проверяем процессор (рис. [-@fig:010]).

![Проверка процессора](image/17.png){#fig:010 width=70%}

Провераем Hypervisor (рис. [-@fig:011]).

![Проверка Hypervisor](image/18.png){#fig:011 width=70%}

Провераем корневую систему (рис. [-@fig:012]).

![Проверка корневой системы](image/19.png){#fig:012 width=70%}

# Выводы

В ходе данной лабораторной работы я приобрел практические навыки по уставке операционной системы на виртуальную машину.
