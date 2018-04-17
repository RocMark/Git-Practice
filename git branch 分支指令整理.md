# git branch 分支指令整理

# 建立分支
//? 建立分支並切換
git checkout -b 分支名 

> 等同於 git branch 分支名
> git checkout

# 從指定節點 產生 分支
git branch 

# 修改分支名
git branch -m 新分支名

# 刪除分支
git branch -d 要刪分支名

一般會先合併才刪除分支，若還未合併Git會有提示，
仍要強制刪除 改成 -D 即可