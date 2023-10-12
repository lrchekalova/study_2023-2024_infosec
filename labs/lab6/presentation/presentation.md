---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №6
subtitle: Информационная безопасность
author:
  - Чекалова Л. Р.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 12 октября 2023

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

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Чекалова Лилия Руслановна
  * студент 4 курса группы НФИбд-02-20
  * ст. б. 1032201654
  * Российский университет дружбы народов
  * [1032201654@pfur.ru](mailto:1032201654@@pfur.ru)

:::
::::::::::::::

# Вводная часть

## Цели и задачи

- Приобретение навыков администрирования в Linux
- Изучение SELinux и веб-сервера Apache
- Работа с лог-файлами

## Материалы и методы

- Веб-сервис `GitHub` для работы с репозиториями
- Программа для виртуализации ОС `VirtualBox`
- Процессор `pandoc` для входного формата Markdown
- Результирующие форматы
	- `pdf`
	- `docx`
- Автоматизация процесса создания: `Makefile`

# Ход работы

## Проверка режима работы SELinux

![](image/1.png){width=70%}

## Запуск веб-сервера

![](image/3.png)

## Просмотр контекста процесса веб-сервера

![](image/4.png){width=70%}

## Просмотр статистики по политике

![](image/6.png){width=70%}

## Просмотр контекстов папок и создание Html-файла

![](image/7.png){width=70%}

![](image/8.png){width=70%}

## Отображение файла в браузере

![](image/10.png){width=70%}

## Изменение контекста и просмотр файла в браузере

![](image/11.png){width=70%}

![](image/12.png){width=70%}

## Просмотр лог-файлов

![](image/13.png){width=70%}

## Изменение порта и перезапуск сервера

![](image/15.png){width=70%}

## Просмотр списка портов

![](image/17.png){width=70%}

## Возвращение контекста и просмотр в браузере

![](image/18.png){width=70%}

![](image/19.png){width=70%}

## Удаление порта и файла

![](image/21.png){width=70%}

# Результаты

## Результаты работы

- Получены базовые навыки администрирования в Linux
- Рассмотрены принципы работы SELinux
- Изучены принципы работы веб-сервера Apache