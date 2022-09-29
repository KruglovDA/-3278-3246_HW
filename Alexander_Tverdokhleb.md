# Основные команды Git

**Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git.**

---

_Изученно на первом уроке:_

+ **git init** - инициализация локального репозитория

+ **git status** - получить информацию от git о его текущем состоянии

+ **git add** - добавить файл или файлы к следующему коммиту

+ **git commit -m “message”** - создание коммита.

+ **git log** - вывод на экран истории всех коммитов с их хеш-кодами

+ **git checkout** - переход от одного коммита к другому

+ **git checkout master** - вернуться к актуальному состоянию и продолжить работу

+ **git diff** - увидеть разницу между текущим файлом и закоммиченным файлом

---

_Изученно на втором уроке:_

+ **git branch** - Выводим список веток в репозитории

+ **git branch new_branch_name** - Создаем новую ветку с именем new_branch_name

+ **git branch -d branch_to_delete** - Удаляем ветку с именем new_branch_name

+ **git checkout branch_name** - Переходим на ветку branch_name

+ **git log –graph** - Выводим список коммитов в виде красивого графа/дерева

+ **git merge branch_name** - Сливает ветку branch_name с текущей веткой

---

_Изученно на третьем уроке:_

+ **git clone** - Эта команда позволяет склонировать внешний репозиторий на наш ПК 

+ **git pull** - Эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией 

+ **git push** - эта команда позволяет отправить нашу версию репозитория на внешний
репозиторий. **ТРЕБУЕТ АВТОРИЗАЦИИ** на внешнем репозитории

## Как сделать pull request
+ Делаем fork репозитория
+ Делаем clone СВОЕЙ версии репозитория
+ Создаем новую ветку и в НЕЕ вносим свои изменения
+ Фиксируем изменения (делаем коммиты)
+ Отправляем свою версию в свой GitHub
+ На сайте GitHub нажимаем кнопку pull request 