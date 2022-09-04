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
