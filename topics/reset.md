# git reset

**git reset** - Команда git reset, как можно догадаться из названия, используется в основном для отмены изменений. 

Она изменяет указатель HEAD и, опционально, состояние индекса. 

Также эта команда может изменить файлы в рабочем каталоге при использовании параметра --hard, что может привести к потере наработок при неправильном использовании, так что убедитесь в серьёзности своих намерений прежде чем использовать его.

```bash=

git reset [-q] [<tree-ish>] [--] <pathspec>…​
git reset [-q] [--pathspec-from-file=<file> [--pathspec-file-nul]] [<tree-ish>]
git reset (--patch | -p) [<tree-ish>] [--] [<pathspec>…​]
git reset [--soft | --mixed [-N] | --hard | --merge | --keep] [-q] [<commit>]

```

<mark>***Пример***</mark>

![git checkout](/pics/Reset.png)