# git rebase

**git rebase** -  это «автоматизированный» cherry-pick. 
Он выполняет ту же работу, но для цепочки коммитов, тем самым как бы перенося ветку на новое место.

```bash=

git rebase [-i | --interactive] [<options>] [--exec <cmd>]
	[--onto <newbase> | --keep-base] [<upstream> [<branch>]]
git rebase [-i | --interactive] [<options>] [--exec <cmd>] [--onto <newbase>]
	--root [<branch>]
git rebase (--continue | --skip | --abort | --quit | --edit-todo | --show-current-patch)

```

<mark>***Пример***</mark>

![git checkout](/pics/Rebase.png)