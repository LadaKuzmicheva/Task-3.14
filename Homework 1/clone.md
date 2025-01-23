[< Вернуться к началу](./readme.md)

## git clone

**git clone** - служит для создания копии репозитория.

Клонировать можно как локальный (находящийся на вашем компьютере), так и удалённый (находящийся в сети) репозиторий.

***Примеры использования:***

`git clone <url>` — клонирует удалённый репозиторий по указанному URL.
```bash=
git clone https://github.com/user/repository.git
```
*Эта команда создаст локальную копию репозитория repository в текущем каталоге.*

`git clone <url> <directory>` — клонирует репозиторий в указанный каталог.
```bash=
git clone https://github.com/user/repository.git my_project
```
*Репозиторий будет скопирован в папку my_project.*

`git clone --branch <branch> <url>` — клонирует только указанную ветку.
```bash=
git clone --branch dev https://github.com/user/repository.git
```
*Клонируется только ветка dev, без других веток репозитория.*