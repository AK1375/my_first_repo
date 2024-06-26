# Подсказка по Git

Создание репозитория:
```sh
git init
```

Добавить файл:
```sh
git add <filename>
```

Сохранить файл:
```sh
git commit -m "message"
```

Журнал изменений:
```sh
git log
```

Журнал изменений (короткая версия):
```sh
git log --oneline
```

Журнал изменений (короткая версия с отрисовкой работты в ветках):
```sh
git log --oneline --graph
```

Переход к указанной версии:
```sh
git checkout <id_версии (код)>
```

Посмотреть разницу текущей и указанной версии:
```sh
git diff <id_версии (код)>
```

Просмотр существующих веток:
```sh
git branch
```

Создание новой ветки:
```sh
git branch <имя_ветки>
```

Слияние веток (указанной с текущей):
```sh
git merge <имя_ветки>
```

Переход к другой ветке:
```sh
git checkout <имя_ветки>
```

Удаление ветки:
```sh
git branch -d <имя_ветки>
```

Загрузить репозиторий из сервиса:
```sh
git clone <ссылка на репозиторий>
```

Сменить директорию:
```sh
cd <имя папки>
```

Листинг текущей директории:
```sh
ls
```

Создать директорию:
```sh
mkdir <имя папки>
```

Сменить директорию на уровень выше:
```sh
cd ..
```

Установка репозитория по ссылке в качестве репозитория по умолчанию:
```sh
git remote add origin <ссылка>
```

Отправка репозитория для записи на сервере:
```sh
git push
```

Подтягивание репозитория с сервера:
```sh
git pull
```