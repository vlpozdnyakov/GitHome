# Instruction for Git

## Start using 
1 step 
* install git
* install VisualStudio

2 step
* Проверяем правильность установки с помощью git status
* Командa git init создаёт репозиторий в папке в которой мы находимся
* Нам необходимо представиться git и для этого используем :git config --global user.name "name" и git config --global user.email "mail"
* После этого нужно добавить commit (git commit -m "Text")
* git log позволяет увидеть коммиты и кем они были созданы, дату и время.


## Secondary commands

* git diff показывает разницу между последним commit и тем, что находится сейчас 
* git checkout - переходим к другому коммиту
* git checkout master - вернуться к актуальной ветке коммита и продолжить работу.

## Remote repository

* чтобы скачать репозиторий себе на комьютер используй команду git clone link_repository
* чтобы из своего репозитория скачать изменения, используй git pull     