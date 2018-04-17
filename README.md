# Git Practice
Git操作練習與筆記整理用 專案

# 待查詢
git diff P2 //! 待補
git show 用法

git stash review&可再深入

git log 6-2 review&補

# 有需要在學 List
* 自訂標籤  git tag
* 自訂指令  git config alias 
* GitStats 統計數據 6-5

# 初始化步驟
* 先建立 README.md 檔案
* 執行下列
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/RocMark/Git-Practice.git
git push -u origin master

# git 指令整理
* git help -a 完整指令清單

# HEAD
HEAD^ 等同於 HEAD~1
HEAD又可以 以 @ 當成縮寫

# git 還原
* 取消 add (用VSCode即可)
////git rm --cached 檔名
* 取消 commit 
git reset HEAD 檔案名

