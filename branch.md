## S3. ћанипул€ции через ссылки, нет ссылки Ч в мусор
#### HEAD Ч текуща€ ссылка, tag Ч фиксированна€ ссылка, branch Ч движуща€с€ за HEAD ссылка
#### checkout Ч перемещение на ветку или коммит, reset Ч перемещение с веткой на коммит
#### ¬идно то, на что есть ссылки, остальное Ч мусор
1. `git tag` Ч вывести список тегов
2. `git tag <tagname>` Ч создать тег
3. `git branch` Ч вывести список локальных веток
4. `git branch -av` Ч вывести список локальных и удаленных веток
5. `git branch <branchname>` Ч создать ветку
6. `git branch -d <branchname>` Ч удалить ветку
7. `git checkout <commit>` или `git switch --detach <commit|branch>` Ч переместить HEAD на коммит, причем получитс€ detached HEAD
8. `git checkout <branch>`или `git switch <branch>` Ч переместить HEAD на ветку
9. `git checkout -b <new_branch>` или `git switch -c <new_branch>` Ч создать ветку и перейти на нее
10. `git reset --hard <commit>` Ч переместить HEAD и текущую ветку на `<commit>`