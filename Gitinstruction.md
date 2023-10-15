![Logo](2color-lightbg@2x.png)
# Работа с Git

## 1. Проверка наличия установленнного Git 
В терминале выполнить команду `git --version`.
Есkи Git установлен, появится сообщение с информацией о версии программы, инчае будет сообщение об ошибке.

** 2. Установка. Git
Загружаем последнюю версию Git c [сайта](https://git-scm.com/downloads).
Устанавливаем с настойками по умолчанию. 

# 3. Настройка Git
При первом использовании Git необходимо представиться.
Для этого нужно ввести в терминале 2 команды:
```
git config --global user.name «Ваше имя английскими буквами»
git config --global user.email ваша почта@example.com
```

## 4. Инициализация репотозитория
Для создния репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создасться репозиторий (появится скрытая папка .git)
## 5. Запись изменений в репозиторий
Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*
## 6. Просмотр истории коммитов
Для просмотра истории коммитов используется команда *git log*
## 7. Перемещение между сохранениями(коммитами)
Перемещение между сохранениями используется команда *git checkout* <имя сохранения>

## 8. Игнорирование файлов
Для того, чтобы исключить из отслеживания в репозитории определённые файлы или папки необходмо создать там файл ***.gitignore*** и записать в него их названия или шабоны, соответствующие таким файлам или папкам.

## 9. Создание веток в Git
По умолчанию имя основной ветки в Git - **master**
Создать ветку можно команжой:
```
git branch  <имя новой ветки>
```
Список веток в репозитории можно посмотреть с помощью команды `git branch`.
Текущая ветка будет отмечена звездочкой: **\* master**
Для переключения между ветками спользуется команда 
```
gitcheckout <имя ветки>
```
## 10. Слияние веток и разрешение конфликтов
Для создания ветки необходимо набрать команду *git branch <имя ветки>*
Для слияния веток произвести команду *git merge <имя ветки>*

## 11. Удаление ветки.
Удаление ветки прозводится командой *git branch -d*. Коману необходимо выполнять из другой ветки.
// не нашёл информации по проблемам с удлениями веткок, и разрешению конфликтов (пересматривал лекции и семинары)

## 12. Работа с удалёнными репозиториями.
Для клонирования репозитория локального или удалённого импользую команду git clone <укзываю_путь>

git pull – получение изменений и слияние с локальной версией

git push – отправляет локальную версию репозитория на внешний

Создать аккаунт на GitHub
Создать локальный репозиторий
Создать удалённый репозиторий
Создать удалённый репозиторий с локальным
Добавить удалённый репозиторий к проекту:

git remote add <имя для репозитория> <url-адрес репозитория в сети>
while(count < 0)
{
   count++;
}
Для получения и слияния изменений из удалённого репозитория изпользуется команда git pull

Отправить изменения локального репозитория в удалённый git push

Список удалённых репозиториев git remote