---
## Front matter
title: "Отчёт по дабораторной работе №4"
subtitle: "Продвинутое использование git"
author: "Селиванов Вячеслав Алексеевич"

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


Получение навыков правильной работы с репозиториями git.


# Задание


Выполнить работу для тестового репозитория.
Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.


# Выполнение лабораторной работы

Устанавливаю git-flow (рис. [-@fig:001]).

![Установка git-flow](image/1.png){#fig:001 width=70%}

Устанавливаю node.js (рис. [-@fig:002]).

![Установка node.js](image/2.png){#fig:002 width=70%}

Устанавливаю pnpm (рис. [-@fig:003]).

![Установка pnpm](image/3.png){#fig:003 width=70%}

Запускаю pnpm (рис. [-@fig:004]).

![Запуск pnpm](image/4.png){#fig:004 width=70%}

Перелогиниваюсь (рис. [-@fig:005]).

![Перелогиниваюсь](image/5.png){#fig:005 width=70%}

Устанавливаю скрипт git-cz, который мы и будем использовать для коммитов (рис. [-@fig:006]).

![Установка скрипта git-cz](image/6.png){#fig:006 width=70%}

Создаю репозиторий на GitHub (рис. [-@fig:007]).

![Создание репозитория](image/7.png){#fig:007 width=70%}

Делаю первый коммит (рис. [-@fig:009]).

![Первый коммит](image/9.png){#fig:009 width=70%}

Выкладываю первый коммит на github (рис. [-@fig:008]).

![Выкладываю коммит](image/8.png){#fig:008 width=70%}

Редактирую файл package.json (рис. [-@fig:011]).

![Редактирую файл](image/11.png){#fig:011 width=70%}

Выполняю коммит (рис. [-@fig:012]).

![Выполняю коммит](image/12.png){#fig:012 width=70%}

Отправляю на github (рис. [-@fig:013]).

![Отправка на github](image/13.png){#fig:013 width=70%}

Инициализирую git-flow (рис. [-@fig:014]).

![Инициализация git-flow](image/14.png){#fig:014 width=70%}

Загружаю весь репозиторий в хранилище (рис. [-@fig:015]).

![Загрузка репозитория](image/15.png){#fig:015 width=70%}

Устанавливаю внешнюю ветку как вышестоящую для этой ветки и создаю релиз с версией 1.0.0 (рис. [-@fig:016]).

![Устанаваливаю ветку как вышестоящую и создаю релиз](image/16.png){#fig:016 width=70%}

Отправляю данные на github (рис. [-@fig:017]).

![Отправка данных на github](image/17.png){#fig:017 width=70%}

Создаю релиз на github (рис. [-@fig:019]).

![Создание релиза на github](image/19.png){#fig:019 width=70%}

Разрабатываю новую функциональность. Создаю релиз с версией 1.2.3. Обновляю номер версии в файле package.json (рис. [-@fig:020]).

![Обновление версии](image/20.png){#fig:020 width=70%}

Создаю журнал изменений и добавляю его в индекс. Заливаю релизной ветки в основную ветку. Отправляю данные на github. Создаю релиз на github с комментарием из журнала изменений (рис. [-@fig:021]).

![Создание релиза](image/21.png){#fig:021 width=70%}















# Выводы

Я получил навыки правильной работы с репозиториями git.

# Список литературы{.unnumbered}

::: {#refs}
:::
