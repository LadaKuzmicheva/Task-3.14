[< Вернуться к началу](./readme.md)

## git add

**git add *[файл]*** - добавляет файл в индекс.

***Примеры использования:***

Чтобы добавить все файлы в каталоге в индекс (кроме игнорируемых),
используйте команду:
```bash=
git add .
```

`git add <file>` — добавляет конкретный файл в индекс.
```bash=
git add example.txt
```
*Добавляет файл example.txt в индекс.*

`git add <directory>` — добавляет все файлы в указанной папке.
```bash=
git add src/
```
*Добавляет все файлы из папки src в индекс.*