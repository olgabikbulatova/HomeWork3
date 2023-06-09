# _**Инструкция Git**_

![logo gb](geekbrains.png)

>В разработке программного обеспечения контроль версий представляет собой класс систем, ответственных за управление изменениями в компьютерных программах, документах, крупных веб-сайтах или других наборах информации. Контроль версий является компонентом управления конфигурацией программного обеспечения.

## *Установка*
[Git](https://git-scm.com/downloads)

[VS Code](https://code.visualstudio.com/Download)

## Начало работы

При первом использовании Git необходимо представиться.  Для этого нужно ввести в терминале 2 команды:

* git config --global user.name «Ваше имя английскими буквами»  
* git config --global user.email ваша почта@example.com

## Основные команды Git

1. **git init** – инициализация локального репозитория
2. **git status** – получить информацию от git о его текущем состоянии
3. **git add “path”**– добавить файл или файлы к следующему коммиту
3. **git add .** - добавляет все файлы в проекте в отслеживание
4. **git commit -am “message”** - git add + git commit (Работает только после 1-го ручного добавления в отслеживание)
5. **git commit** -m “message” – создание коммита.
6. **git log** – вывод на экран истории всех коммитов с их хеш-кодами
7. **git checkout** – переход от одного коммита к другому
8. **git checkout master** – вернуться к актуальному состоянию и продолжить работу (git checkout main)
9. **git diff** – увидеть разницу между текущим файлом и закоммиченным файлом

## Работа с ветками
1. **git branch** – посмотреть список веток в репозитории
2. **git branch** <название ветки> – создать новую ветку
3. **git checkout** <название ветки> – переход к другой ветке

## Прочие команды
1. **git log --graph** - визуализирует коммиты
2. **git checkout -b** <название ветки> -> Создание и переход в новую ветку
3. **git commit --amend -m “text”** - изменение текста последнего коммита
4. **git reset HEAD~**  - удаление самого последнего коммита

## Работа с удаленными репозиториями
1. **git clone <url-адрес репозитория>** – клонирование внешнего репозитория на  локальный ПК
2. **git pull** – получение изменений и слияние с локальной версией
3. **git push** – отправляет локальную версию репозитория на внешний
