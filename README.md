Инструмент контроля версий Git

1. создать локальный репозиторий git init
2. создать файл README touch README.md
3. проверить состояние репозитория git status
4. подготовить файл для сохранения git add README.md
5. проверить статус файла git status -- должен быть зеленый
если файлов несколько и нужно сохранить все git add --all
6. сделать коммит git commit -m "описание коммита"
7. создать новый репозиторий на github
8. при помощи подсказки с github связать локальный репозиторий с удаленным по SSH (ранее должен быть создан ключ для SSH и добавлен в профиль github)
git remote add origin git@github.com:AlexBalyanov/git-helper.git
git branch -M main
git push -u origin main

9. запушить измененные файлы из локального репозитория в удаленный 
git push -u origin main
