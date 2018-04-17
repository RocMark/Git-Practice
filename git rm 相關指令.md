# git rm  刪除檔案相關

# 較佳解
於 folder 直接刪除 git add / commit 即可

# git rm 一般流程
git rm 檔案名
1. 先比對 index 是否有該檔
2. folder 的檔與 repo的檔是否相同
皆通過 可用 git status 檢查一下
git commit 完成刪除