git log –graph

git clone

git pull

git push

# Инструкция по работе с GIT.

## Инструкция по работе с git в виде цитат.

 Для создания локального репозитория нужно запустить команду:
> git init

 Для добавления файла к следующему комиту:

> git add

 И фиксируем эти файлы:

> git commit

Для отслеживания состояния репозитария, можно ввести команду:
> git status

Чтобы посмотреть все комиты:
> git log

Для просмотра разницы между закомичанными и текущеми изменениями:
> git diff 

Для перехода к прошлым комитам (с кодед commit_code) можно использовать:
> git checkout commit_code

Чтобы вернуться:
> git checkout msster

Для просмотра всех веток:
> git branch

Чтобы создать ветку, нужнл:
> git branch branch_name

Для совмещения текущей ветки с веткой branch_name:
> git merge branch_name

Изменения добавятся в текущую
Для перехода к ветке branch_name:
> git checkout branch_name

Для визуализации веток можно использовать:
>git log --graph

Для того, чтобы удалить ветку branch_name, нужно написать:
> git branch -d branch_name

если ветка не полность юзамерджена, то с поьощью тега -d удалить её не получится, тогда надо использовать тег -D
> git branch -D branch_name

Чтобы создать и сразу переходить на ветку, можно использовать:
> git checkout -b branch_name

## gitHub инструция:

1. Создали аккаунт на GitHub.com
2. Создать локальный репозиторий
3. "Подружить" ваш локальный и удалённый репозиторий. GitHub при создании нового репозитория подскажит как это можно сделать)
4. Отправить(push) ваш локальный репозиторий в удалённый (на GitHub) при этом вам, возможно, нужно авторизироваться на удалённом репозитории.
5. Провести изменения "с другого компьютера".
6. Выкачать (Pull) актуальное состояние из удолённого репозитория. 

## Работа с удаленными репозиториями в git
# Как сделать pull request

* Делаем fork репозитория
* Делаем clone СВОЕЙ версии репозитория
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты) 
* Отправляем свою версию в свой GitHub 
*  На сайте GitHub нажимаем кнопку pull request 
