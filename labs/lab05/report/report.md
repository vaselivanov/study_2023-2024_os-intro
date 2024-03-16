---
## Front matter
title: "Отчёт по лабораторной работе №5"
subtitle: "Настройка рабочей среды"
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

Научиться настраивать рабочую среду.
# Задание

Здесь приводится описание задания в соответствии с рекомендациями
методического пособия и выданным вариантом.

# Теоретическое введение

Здесь описываются теоретические аспекты, связанные с выполнением работы.

Например, в табл. [-@tbl:std-dir] приведено краткое описание стандартных каталогов Unix.

: Описание некоторых каталогов файловой системы GNU Linux {#tbl:std-dir}

| Имя каталога | Описание каталога                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `/`          | Корневая директория, содержащая всю файловую                                                                               |
| `/bin `      | Основные системные утилиты, необходимые как в однопользовательском режиме, так и при обычной работе всем пользователям     |
| `/etc`       | Общесистемные конфигурационные файлы и файлы конфигурации установленных программ                                           |
| `/home`      | Содержит домашние директории пользователей, которые, в свою очередь, содержат персональные настройки и данные пользователя |
| `/media`     | Точки монтирования для сменных носителей                                                                                   |
| `/root`      | Домашняя директория пользователя  `root`                                                                                   |
| `/tmp`       | Временные файлы                                                                                                            |
| `/usr`       | Вторичная иерархия для данных пользователя                                                                                 |

Более подробно про Unix см. в [@tanenbaum_book_modern-os_ru; @robbins_book_bash_en; @zarrelli_book_mastering-bash_en; @newham_book_learning-bash_en].

# Выполнение лабораторной работы

Устанавливаю pass (рис. [-@fig:001]).

![Установка pass](image/1.png){#fig:001 width=70%}

Устанавливаю gopass (рис. [-@fig:002]).

![Установка gopass](image/2.png){#fig:002 width=70%}

Просматриваем список ключей и инициализируем хранилище (рис. [-@fig:003]).

![Просмотр списка ключей и инициализация хранилища](image/3.png){#fig:003 width=70%}

Создаём структуру git (рис. [-@fig:004]).

![Создание структуры git](image/4.png){#fig:004 width=70%}

Синхронизируем репозиторий следующими командами. Выполняем pass git pull(рис. [-@fig:005]).

![Pass git pull](image/5.png){#fig:005 width=70%}

Выполняем pass git push (рис. [-@fig:006]).

![Pass git push](image/6.png){#fig:006 width=70%}

Настраиваю интерфейс с броузером (рис. [-@fig:007]).

![Настройка интерфейса](image/7.png){#fig:007 width=70%}

Устанавливаю дополнительное программное обеспечение (рис. [-@fig:008]).

![Установка дополнительного программного обеспечения](image/8.png){#fig:008 width=70%}

Устанавливаю шрифты (рис. [-@fig:009]).

![Установка шрифтов](image/9.png){#fig:009 width=70%}

Устанавливаю бинарный файл и создаю свой репозиторий(рис. [-@fig:010]).

![Установка бинарного файла и создание репозитория](image/10.png){#fig:010 width=70%}

Инициализирую chezmoi со своим репозиторием (рис. [-@fig:011]).

![Инициализация chezmoi](image/11.png){#fig:011 width=70%}

Проверяю какие изменения внёс chezmoi в домашний каталог (рис. [-@fig:012]).

![Установка gopass](image/12.png){#fig:012 width=70%}


# Выводы

Я научился настраивать рабочую среду.

# Список литературы{.unnumbered}

::: {#refs}
:::
