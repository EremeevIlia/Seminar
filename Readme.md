# Система контроля версий Git и ветки


## Что такое Git?
Git - одна из  распределённых систем контроля версий. Позволяет управлять версионностью файлов, откатываться до версий, создавать ветки и их сливать 

## Подготовка репозитория 
**Репозиторий** - это хранилище файлов,поддерживающее версионность.
Создать репозиторий можно с помощью команды *git init*, применённой в папке с будущим репозиторием. Для добавления версионности к файлу используется команда *git add <имя файла>*

## Создание "сохранений"
Для создания "сохранения" необходимо выполнить фиксацию, она же коммит. Это можно сделать с помощью команды *git commit* следующим образом: *git commit -a -m "<сообщение>"*

##  Перемещение между сохранениями
Перемещаться на тот или иной комит можем с помощью команды *git checkout*. Для этого нужно написать *git checkout <номер коммитф из истории>*.Для возврата к самому последнеу коммиту нужно написать *git checkout <название ветки>* По умолчанию это ветка *master*.
Отменять изменения можно с помощью команд *git rever* и *git reset*.
Для этого нужно написать команду *git rever(reset) <номер коммита>*

## Ветки в git
Новую ветку мы можем создавать с помошью команды *git branch*.Применяется она так:*git branch <название ветки>*. **Название ветки должно быть уникальным и не повторяться  с уже имеющимися ветками**, также можно использовать команду *rebase*, она совмещает ветки более плавно и линейно.
Пишется так: **git rebase<название ветки>**

## Cкачивание удаленного репозитория
Скачивание удаленного репозитория происходит с помощью команды git clone. Она применяется в удобной Вам папке и пишется git clone <адрес репозитория>. После чего Вашей папке создается папка, название которой точно совпадает с названием репозитория,а её содержание является содержимое репозитория.

## Отправка изменений в удалённый репозиторий 
Для того, чтобы отправить изменения в удалённый репозиторий используется команда *git push*. Пишется это так *git push origin <название ветки>*,чаще всего в качестве названия ветки используется **master**

## Журнал изменений
Журнал изменений можно просмотреть с помощью команды *git log*. Необходимо выполнить команду *git log* в папке с нашим репозиторием.Можно использовать команду *git log --graph* для просмотра репозитория.

## Подключение Github
Для того чтобы подключить Github нужно создать на Githube новый репозиторий.Скопировать ссылку репозитория.Далее в Gite написать *git clone <ссылка репозитория>*.

