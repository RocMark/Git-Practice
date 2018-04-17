# git commit 相關指令

# 修改上一個 commit 記錄
* git commit --amend -m '新commit'

# 查詢過往 commit 記錄
* git log  
git log --oneline 只顯示title
git show 快速查詢上一次commit msg
git log -1 上一次
git log -2 上上次
//* 指呈現 msg,不顯示其他
git log -2 --pretty=%B  