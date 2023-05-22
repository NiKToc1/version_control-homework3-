# Git для новичков

## Что такое Git и зачем он нужен?
Git - это консольная утилита, для отслеживания и ведения истории изменения файлов, в вашем проекте. Чаще всего его используют для кода, но можно и для других файлов. Например, для картинок - полезно для дизайнеров.

## Базовые команды
* ### *git init* - команда создаёт новый репозиторий Git
* ### *git add* - команда сохраняет текущее состояние проекта в истории коммитов
* ### *git commit* - команда, которая берёт все подготовленные изменения и отправляет их в репозиторий.
* ### *git diff* - команда инициирует сравнения источников данных - коммитов, веток, файлов и т.д.
* ### *git log* - команда показывает историю коммитов
* ### *git checkout* - команда, позволяющая переключаться между различными версиями 

## Ветки
Ветка - это набор коммитов, которые идут друг за другом. У ветки есть название, основную ветку чаще всего называют master. Если говорить простыми словами, то ветка master - это наш проект.
Другие ветки - это отдельное место для реализации нового функционала или исправление багов нашего проекта. То есть, с отдельной веткой вы делаете что угодно, а затем сливаете эти изменения в основную ветку master.

* ### *git branch* - команда позволяет посмотреть существующие ветки
* ### *git branch <название ветки>* - комадна позволяет создать эту ветку
* ### *git checkout <название ветки>* - команда позволяет переключиться на эту ветку
* ### *git merge <название ветки>* - команда позволяет слить ветку

## Изображения
Чтобы вставить изображения, достаточно написать следующее:
![Ваш текст](kartinka.jpg)

## Управление удалёнными репозиториями 
Для того, чтобы внести вклад в какой-либо Git-проект, вам необходимо уметь работать с удалёнными репозиториями. Удалённые репозитории представляют собой версии вашего проекта, сохранённые в интернете или ещё где-то в сети.

* ### *git pull*
* ### *git push*
