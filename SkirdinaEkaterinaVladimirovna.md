## Работа с удаленными репозиториями.

### Основные команды

**git clone** - _составная команда:  она не только
загружает все изменения, но и пытается слить 
все ветки на локальном компьютере и в
удаленном репозитории._

**git pull** - _команда позволяет скачать все 
из текущего репозитория и автоматически
сделать merge с нашей версией._

**git push** - _команда позволяет отправить нашу
версию репозитория на внешний
репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ 
на внешнем репозитории._

### Как настроить совместную работу

1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. “Подружить” ваш локальный и удалённый репозитории.  
_GitHub при создании нового репозитория подскажет, как это можно сделать_
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно,
вам нужно будет авторизоваться на удалённом репозитории
5. Провести изменения “с другого компьютера”
6. Выкачать (pull) актуальное состояние из удалённого репозитория

### pull request

* команда для предложения изменений
* запрос на вливание изменений в репозиторий

В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду **pull request**. Предлагать изменения на GitHub нужно в отдельной ветке. Сначала пользователь копирует репозиторий на свой компьютер, делает **fork** репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой **push** в свой аккаунт на GitHub и даёт команду **pull request**.

### Как сделать pull request

* Делаем   (ответвление) репозитория **fork**
* Делаем **git clone**  СВОЕЙ версии репозитория
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку **pull request**