# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил(а):
- Кочешков Олег Романович
- РИ-230914
  
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

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Рассмотреть работу перцептрона, настроить его работу, визуализировать его результаты.

## Задание 1
### В проекте Unity реализовать перцептрон, который умеет производить вычисления:
- OR | дать комментарии о корректности работы

![image](https://github.com/user-attachments/assets/d34a3784-9724-4164-9ce8-0625c3fc8997)

Перцептрону даётся 8 тестов, чтобы он смог правильно науиться. Как видно, уже на 4 попытке он смог научится делать OR. Работает корректно.
  
- AND | дать комментарии о корректности работы

![image](https://github.com/user-attachments/assets/e7286e06-15a3-4a16-8f2e-eb0feffadaf5)

AND перцептрон так же смог научиться за 4 попытки. Работает корректно.
  
- NAND | дать комментарии о корректности работы

![image](https://github.com/user-attachments/assets/689aae87-71e9-4d6e-9043-d7a4a3e329b4)

Как известно, как быстро учится перцептрон - это случайность, поэтому он может научиться и за 1 попытку. С NAND у меня было максимум 3 попытки. Работает корректно.
  
- XOR | дать комментарии о корректности работы

![image](https://github.com/user-attachments/assets/670ef2aa-f649-4c5f-a305-9a626a74e493)

А вот с XOR уже начали возникать проблемы с корректностью. Сколько бы тестов не давалось перцептрону, он не может корректно расcчитать XOR. Всё это из-за того, что он не может решать неленейно.

## Задание 2
### Построить графики зависимости количества эпох от ошибки обучения. Указать от чего зависит необходимое количество эпох обучения.

![image](https://github.com/user-attachments/assets/ead76e5b-77f2-4123-84cf-2cb4ff40686e)

Как и говорилось раньше, результат обучения довольно случайный. Хотя перцептрон запоминает веса, которые влияют на итоговый результат, что и позволяет ему в итоге обучаться, а не просто каждую попытку выводить случайные значения.

## Выводы

Перцептрон является "дедушкой" нейросетей. К сожалению, он не может справляться с не ленейными задачами в 1 итерацию, хотя учится он довольно быстро, по крайней мере с логическими операциями. 
В итоге, в этой работе мы научились учить перцептрона и понимать, как он учится.

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
