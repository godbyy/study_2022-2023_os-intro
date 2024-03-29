---
## Front matter
lang: ru-RU
title: Выполнение 2 этапа проекта
subtitle: Операционные системы
author:
  - Моргунов В. И.
institute:
  - Российский университет дружбы народов, Москва, Россия

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

  * Моргунов Владимир Иванович
  * студент 
  * НММбд-02-22
  * Российский университет дружбы народов
  * <https://godbyy.github.io/ru/>

:::
::: {.column width="30%"}


:::
::::::::::::::

# Цель работы

Целью работы является освоение новых команд терминала, связанных с конструктором статических веб-сайтов Hugo, приобретение практических навыков изменения информации о владельце сайта и добавления новых постов, а также более детальное изучение файлов директории blog персонального проекта.

# Задание

Добавить к сайту данные о себе. Разместить фотографию владельца сайта. Разместить краткое описание владельца сайта (Biography). Добавить информацию об интересах (Interests). Добавить информацию об образовании (Education). Создать два поста: о пятнице и git.

# Выполнение лабораторной работы

##

![Разместили фотографию владельца сайта](image/1.png)

##

![Указали имя владельца сайта в файле Markdown, путь которого ~/work/blog/content/authors/admin](image/2.png)

##

![Разместили краткое описание владельца сайта](image/3.png)

##

![Краткое описание владельца сайта отображается в конце постов](image/4.png)

##

![Добавили информацию об интересах](image/5.png)

##

![Добавили информацию об образовании](image/6.png)

##

![В конце файла записали полную информацию о владельце сайта](image/7.png)

##

![С помощью команды ~/bin/hugo server получили ссылку на сайт и проверили, как на нём отобразилась информация](image/8.png)

##

![С помощью команды ~/bin/hugo new post/last_week создали пост о прошедшей неделе "Пятница"](image/9.png)

##

![Посмотрели, как пост отображается, когда открываешь его по ссылке из главного сайта](image/10.png)

##

![Создали пост о прошедшей неделе "Git"](image/11.png)

##

![Посмотрели, как пост отображается на главной странице](image/12.png)

# Выводы

Освоили новые команды терминала, связанные с конструктором статических веб-сайтов Hugo, приобрели практические навыки изменения информации о владельце сайта и добавления новых постов, а также лучше познакомились с файлами в директории blog персонального проекта.
