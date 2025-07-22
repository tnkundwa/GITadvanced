#Git advanced exercises

##Challenge 1

```bash
$ touch test{1..4}.md
$ git add test1.md
$ git commit -m "chore: Create initial file"
$ git add test2.md
$ git commit -m "chore: Create another file"
$ git add test3.md
$ git commit -m "chore: Create third and fourth files"
$ git add test4.md
$ git commit -m "chore: Create fourth file"
```
##Challenge 2

```bash
$ git log --oneline
$ git rebase -i 9ceedc3
$ git rebase -i 27a47bc
$ git commit --amend
$ git status
$ git rebase --continue
$ git status
$ git log
$ git log --oneline
```

##Challenge 3

```bash
$ git log
$ git rebase -i HEAD~3
$ git log
$ git log --oneline
$ git rebase -i HEAD~6
$ git rebase -i HEAD~4
$ git rebase --abort
$ git rebase -i --root
$ git log
$ git log --oneline
```

