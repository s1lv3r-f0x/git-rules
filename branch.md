## S3. ћанипул€ции через ссылки, нет ссылки Ч в мусор
#### HEAD Ч текуща€ ссылка, tag Ч фиксированна€ ссылка, branch Ч движуща€с€ за HEAD ссылка
#### checkout Ч перемещение на ветку или коммит, reset Ч перемещение с веткой на коммит
#### ¬идно то, на что есть ссылки, остальное Ч мусор
- `git tag` Ч вывести список тегов
- `git tag <tagname>` Ч создать тег
- `git branch` Ч вывести список локальных веток
- `git branch -av` Ч вывести список локальных и удаленных веток
- `git branch <branchname>` Ч создать ветку
- `git branch -d <branchname>` Ч удалить ветку
- `git checkout <commit>` или `git switch --detach <commit>` Ч переместить HEAD на коммит, причем получитс€ detached HEAD
- `git checkout <branch>`или `git switch <branch>` Ч переместить HEAD на ветку
- `git checkout -b <new_branch>` или `git switch -c <new_branch>` Ч создать ветку и перейти на нее
- `git reset --hard <commit>` Ч переместить HEAD и текущую ветку на `<commit>`
- `git reflog show <ref>` Ч показать лог действий со ссылкой
- `git reflog` = `git reflog show HEAD` Ч показать лог действий с HEAD
- `git gc` Ч удалить ненужные файлы и оптимизировать локальный репозиторий