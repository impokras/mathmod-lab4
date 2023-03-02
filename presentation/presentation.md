---
## Front matter
lang: ru-RU
title: Модель гармонических колебаний
subtitle: Лабораторная работа №4
author:
  - Покрас Илья Михайлович 
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 2 марта 2023

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

## Цели и задачи
Целью данной лабораторной работы является построение математических моделей гармонический колебаний.

## Задачи
Построить фазовый портрет гармонического осциллятора и решенить уравнения гармонического осциллятора для следующих случаев:
1. Колебания гармонического осциллятора без затуханий и без действий внешней силы
2. Колебания гармонического осциллятора c затуханием и без действий внешней
силы
3. Колебания гармонического осциллятора c затуханием и под действием внешней силы

## Ход Работы
Код Julia:

![Код - 1 часть](./image/codejl-1.png){#fig:001 height=85%}
![Код - 2 часть](./image/codejl-2.png){#fig:002 height=75%}

## Ход Работы
Первый случай: 

![Фазовый портрет первого случая](./image/model1_1.png){#fig:003 height=50%}
![Решение первого случая](./image/model1_2.png){#fig:004 height=50%}

## Ход Работы
Второй случай: 

![Фазовый портрет второго случая](./image/model2_1.png){#fig:004 height=50%}
![Решение второго случая](./image/model2_2.png){#fig:005 height=50%}

## Ход Работы
Третий случай: 

![Фазовый портрет третьего случая](./image/model3_1.png){#fig:006 height=50%} 
![Решение третьего случая](./image/model3_2.png){#fig:007 height=50%}

## Ход Работы
Код OpenModelica:

![Код OpenModelica для первого случая](./image/ocode-1.png){#fig:008 height=50%}

## Ход Работы

![Код OpenModelica для второго случая](./image/ocode-2.png){#fig:009 height=50%}

## Ход Работы

![Код OpenModelica для третьего случая](./image/ocode-2.png){#fig:010 height=50%}


## Ход Работы
Первый случай:

![Фазовый портрет первого случая](./image/omodel1_1.png){#fig:011 height=30%}
![Решение первого случая](./image/omodel1_2.png){#fig:012 height=30%}


## Ход Работы
Второй случай: 

![Фазовый портрет второго случая](./image/omodel2_1.png){#fig:013 height=30%}
![Решение второго случая](./image/omodel2_2.png){#fig:014 height=30%}

## Ход Работы
Третий случай:

![Фазовый портрет третьего случая](./image/omodel3_1.png){#fig:015 height=30%}
![Решение третьего случая](./image/omodel3_2.png){#fig:016 height=30%}

## Результаты

В резльтате проделанной работы был написан код на Julia и OpenModelica для решения 3 случаев движения гармонического осциллятора.