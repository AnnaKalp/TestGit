## Настройка
* Имя пользователя и адрес электронной почты, откройте терминал и запустите команды:

 git config --global user.name "My Name"

git config --global user.email myEmail@example.com

* Для того, чтобы посмотреть все настройки системы, используйте команду:

git config --list

* Для удобства и легкости зрительного восприятия, некоторые группы команд в Гит можно выделить цветом, для этого нужно прописать в консоли:

git config --global color.ui true

git config --global color.status auto

git config --global color.branch auto


## Создание нового репозитория
* Создайте на рабочем столе папку под названием git_exercise. Для этого в окне терминала введите:

 mkdir Desktop/git_exercise/

cd Desktop/git_exercise/

git init

## Определение состояния
$ git status

On branch master

Initial commit

Untracked files:

(use "git add ..." to include in what will be committed)

hello.txt

## Подготовка файлов
$ git add hello.txt

## Фиксация изменений

* Как сделать коммит

git commit -m 'Add some code'

*  Теперь создадим непосредственно сам коммит

 git commit -m 'Add some code'

## Как посмотреть коммиты
git log

##  Отслеживание изменений, сделанных в коммитах
* Чтобы просмотреть список всех коммитов и их идентификаторов, можно использовать команду log:

$ git log

commit ba25c0ff30e1b2f0259157b42b9f8f5d174d80d7

Author: Tutorialzine

Date: Mon May 30 17:15:28 2016 +0300

New feature complete

