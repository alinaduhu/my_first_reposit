# Подсказка по GIT

## Первоначальная настройка
Команда смены дирректории
```sh
cd c:\folder__name
```
Команда отображения текущей директории MacOs, Linux
```sh
pwd
```
Листинг текущей директории Windows:
```sh
dir
```
MacOs, Linux
```sh
ls
```
## Создание репозитория
```sh
git init
```
## Внесение изменений
Статус папки
```sh
git status
```
Команда для добавления и сохранения файла 
```sh
git add \file name
```
Команда для записи индексированных изменений в репозитории
```sh
git commit -m "Message text"
```

Показать журнал изменений
```sh
git log
```
## Работа с ветками
Переключение между ветками
```sh
git checkout <branch_name>
```
Отображение всех веток
```sh 
git branch
```
Создание новой ветки
```sh
git branch <branch_name>
```
Удаление выбранной ветки
```sh
git branch -d <branch_name>
```
Объединяет две ветки
```sh
git merge <branch_name>
```
## Работа изображениями
Так выглядит git 

![git](загрузка.png)
## Работа с удаленными репозиториями
Добавить удаленный репозиторий 
```sh
git remote add origin <https://github.com/name>
```
Отправить изменения в удаленный репозиторий
```sh
git push -u ogigin main
```
Извлечь и загрузить содержимое из удаленного репозитория
```sh
git pull
```
Отправить изменения в новой ветке в удаленный репозиторий
```sh
git push --set-upstream origin <branch_name>
```
Удалить ветку в удаленнои репозитории
```sh
git push origin --delete <branch_name>
```
Скачать все репозитории чтобы слить наши изменения
```sh
git pull --rebase
```
Скопировать себе на компьютер сторонний репозиторий
```sh
git clone <https://github.com/name>
```