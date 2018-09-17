### git命令详解
git clone
git status
git add .
git commit -m
git checkout -b dev
git pull origin master
git pull --rebase origin master
git rebase --continue
git rebase --abort
git pull = git fetch + git merge
git pull --rebase = git fetch + git rebase
git push origin master
git stash
git stash pop
git stash save ""
git stash list
git stash apply 0
git stash drop 0
git stash clear 删除所有缓存
git stash show 0 查看指定stash的diff