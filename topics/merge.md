# git merge

**git merge** - команда git merge используется для слияния одной или нескольких веток в текущую. Затем она устанавливает указатель текущей ветки на результирующий коммит.

Мы познакомили вас с этой командой в разделе Основы ветвления главы 3. И хотя git merge встречается в этой книге повсеместно, практически все использования имеют вид git merge <branch> с указанием единственной ветки для слияния.

```bash=

git merge [-n] [--stat] [--no-commit] [--squash] [--[no-]edit]
	[--no-verify] [-s <strategy>] [-X <strategy-option>] [-S[<keyid>]]
	[--[no-]allow-unrelated-histories]
	[--[no-]rerere-autoupdate] [-m <msg>] [-F <file>]
	[--into-name <branch>] [<commit>…​]
git merge (--continue | --abort | --quit)

```


``Пример``


![git checkout](/pics/Merge.png)