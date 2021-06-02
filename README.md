# markdown
git config --global url."https://github.com.cnpmjs.org/".insteadOf "https://github.com/"

git checkout -b develop
git branch -a
git add .
git commit -m "finished markdown"
git checkout main
git  merge develop
git push origin main

git reset --hard bc5c(绝对版本号)
git reste --hard head~1(上一个版本)

向后穿梭
git reflog 查看命令历史，确定后向的版本号
git reset --hard 1d115

工作区变化了，想撤销
git checkout --