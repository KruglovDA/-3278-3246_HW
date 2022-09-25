# Руководство по Git

## git version

Показывает версию Git

## git init   

init Создает репозиторий

## git status

**Показывает модифицированные файлы, ждущих commit'a**

## git add [file] 

**Добавить указанный файл к следующему commit**

## git reset

[Смотреть](https://techrocks.ru/2020/10/16/git-reset-explained/)

## git diff

Показывает изменения между не стэджнутыми файлами

## git commit -m "...."

**Проще говоря сделать коммит с комментарием**

## git config --global user.name “[firstname lastname]”

Установить имя и фамилию

## git config --global user.email “[valid-email]”

Установить Адрес электронной почты

## git clone [url]

Клонировать репозиторий по url

## git branch

Просмотр веток

## git log

Просмотр истории commit'ов в текущей ветке

![Альтернативный текст](.\Screenshot_1.png)
![Альтернативный текст](.\Screenshot_2.png)


git remote add <repository_name> link
Вместо repository_name нужно дать имя удаленному репозиторию. Далее в инструкции вместо этого параметра мы будем использовать origin, так как чаще всего используют это имя.

Вместо link — ссылка на удаленный репозиторий, она может выглядеть по-разному в зависимости от того используется ssh или https. 

git push origin <branch> 
Вместо branch — имя ветки, которую надо отправить. Чаще всего используется master или main: 


git push origin master 
