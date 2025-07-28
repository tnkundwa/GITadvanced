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

##Challenge 4
```bash
$ git log --oneline
$ git rebase -i --root
$ git reset HEAD~1
$ git status
$ git add test3.md 
$ git commit -m "Create third commit"
$ git rebase --continue
$ git rebase --skip
$ git log --oneline
```

##Challenge 5
```bash
LONOVO@toussaintn23 MINGW64 ~/GITadvanced (main)
$ git rebase -i --root
$ git rebase --continue
$ git log --oneline
```
##Challenge 6
```bash
$ touch unwanted.txt
$ git add unwanted.txt 
$ git commit -m  "Unwanted commit"
$ git status
$ git rebase -i --root
$ git rebase --continue
$ git log --oneline
```

##Challenge 8
```bash
$ git checkout -b ft/branch
$ git branch
$ git status
$ touch test5.md
$ git status
$ git add test5.md 
$ git commit -m "Implemented test 5"
$ git log --oneline
$ git checout main
$ git checkout main
$ git cherry-pick cc33ad5
$ git status
$ git cherry-pick --continue
$ git log --oneline
```

#Part 2
##Challenge 1
```bash
$ git checkout -b ft/new-feature
```
##Challenge 2
```bash
$ touch feature.txt
$ git add feature.txt 
$ git commit -m "Implemented core functionality for new feature"
```
##Challenge 3
```bash
$ git checkout main
$ touch readme.txt
$ git add readme.txt
$ git commit -m "Updated project readme"
```
##Challenge 5
```bash
$ git merge ft/new-feature
$ git status
$ git log --oneline
$ git reflog
$ git branch -d ft/new-feature
```
##Challenge 6
```bash
$ git log --oneline --graph
$ git log --oneline --root
$ git checkout -b ft/new-branch-from-commit 171dee6
$ git checkout main
```

##Challenge 7
```bash
$ git merge ft/new-branch-from-commit
$ git status
```

##Challenge 8
```bash
$ git status
$ git pull
$ git branch
$ git checkout ft/new-branch-from-commit 
$ git status
$ git pull
$ git rebase main
$ git status
$ git checkout main
$ git status
```
##Challenge 9
```bash
$ git branch -m ft/new-branch-from-commit ft/improved-branch-name
$ git branch
```