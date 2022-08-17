# git add

**git add *[файл]*** - добавляет файл в индекс.

Чтобы добавить все файлы в каталоге в индекс (кроме игнорируемых), используйте команду: 

```bash=

git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive | -i] [--patch | -p]
	  [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update | -u]] [--sparse]
	  [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-missing] [--renormalize]
	  [--chmod=(+|-)x] [--pathspec-from-file=<file> [--pathspec-file-nul]]
	  [--] [<pathspec>…​]

```
<mark>***Пример***</mark>

![git add](/pics/Add.png)


**Info**: В дополнении можно запустить $git status для того, чтобы проверить добавился ли новый файл. В нашем примере мы так и сделали.