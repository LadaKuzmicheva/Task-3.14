[< Вернуться к началу](./readme.md)

## git merge

**git merge** - команда, которая сливает изменения из указанной ветки в текущую ветку. Она объединяет два набора изменений в один, создавая новый коммит, если это необходимо.

***Один из основных вариантов использования:***

`git merge <branch>` — сливает указанную ветку с текущей.
```bash=
git checkout main
git merge feature
```
*Эта команда объединяет изменения из ветки feature в ветку main.*