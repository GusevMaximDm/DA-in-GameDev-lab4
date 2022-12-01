# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил(а):
- Гусев Максим Дмитриевич
- РИ211121
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Познакомиться с программными средствами реализации "глубокого обучения" и его интеграции в Unity.

## Задание 1
### В проекте Unity реализовать перцетрон, который умеет производить вычисления OR, AND, NAND, XOR.
-Ход работы: Создать проект, проверить перцетрон на: OR, AND, NAND, XOR. 

### -OR: На четвертом шаге результат был достигнут, пробем не возникло.
![Image alt](https://github.com/GusevMaximDm/DA-in-GameDev-lab4/blob/main/OR%20first%20slide.png)
![Image alt](https://github.com/GusevMaximDm/DA-in-GameDev-lab4/blob/main/Or%20second%20slide.png)

### -AND: Потребовалось 8 шагов для реализации, проблем не возникло.
![Image alt](https://github.com/GusevMaximDm/DA-in-GameDev-lab4/blob/main/AND%20first%20slide.png)
![Image alt](https://github.com/GusevMaximDm/DA-in-GameDev-lab4/blob/main/AND%20second%20slide.png)

### -NAND: Так же как и для AND потребовалось 8 шагов для достижения цели.
![Image alt](https://github.com/GusevMaximDm/DA-in-GameDev-lab4/blob/main/NAND%20first%20slide.png)
![Image alt](https://github.com/GusevMaximDm/DA-in-GameDev-lab4/blob/main/NAND%20second%20slide.png)

### -XOR: Даже при 100000 шагов результат оказался отрицательным, перцетрон не справился.
![Image alt](https://github.com/GusevMaximDm/DA-in-GameDev-lab4/blob/main/XOR.png)



## Задание 2
### Построить графики зависимости количества эпох от ошибки обучения. Указать от чего зависит необходимое количество эпох обучения.
-Как мы могли выяснить, чем больше количество эпох (итераций) тем меньше вероятность ошибки. Это потому-что увеличивается количество попыток на обучение. Следовательно график убывающий. Ближе будет к первому графику (плавно убывающему). 
![Image alt](https://github.com/GusevMaximDm/DA-in-GameDev-lab4/blob/main/график.png))

-кол-во эпох зависит от-кол-ва ошибок во время обучения, чем проще функция, тем меньше ошибок.


## Задание 3
### Построить визуальную модель работы перцетрона на сцене Unity.


## Выводы
Перцептрон использует перебор вариантов и приходит к наилучшему решению оталкиваясь от них, иногда быстрее иногда не успешно. Зависит от сложности фунции.
## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
