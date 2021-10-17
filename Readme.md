# Система контроля версий git band Github


## Что такое git?
Git - одна из  распределённых систем контроля версий. Позволяет управлять версионностью файлов, откатываться до версий, создавать ветки и их сливать 

## Подготовка репозитория 
**Репозиторий** - это хранилище файлов,поддерживающее версионность.
Создать репозиторий можно с помощью команды *git init*, применённой в папке с будущим репозиторием. Для добавления версионности к файлу используется команда *git add <имя файла>*

## Создание "сохранений"
Для создания "сохранения" необходимо выполнить фиксацию, она же коммит. Это можно сделать с помощью команды *git commit* следующим образом: *git commit -a -m "<сообщение>"*

##  Перемещение между сохранениями
Перемещфться на тот или иной комит можем с помощью команды *git checkout*. Для этого нужно написать *git checkout <номер коммитф из истории>*.Для возврата к самому последнеу коммиту нужно написать *git checkout <название ветки>* По умолчанию это ветка *master*.

## Журнал изменений

## Ветки в git

## скачивание удаленного репозитория