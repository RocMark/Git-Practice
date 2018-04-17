# git revert vs git reset

* git reset 
會刪除所有節點，直到該節點

* git revert 
//?則是會創造一個新節點，將目前 folder檔案與該節點合併
git revert 並不會刪除節點

# 注意點
git revert HEAD
> 使 folder 狀態回到 //* HEAD^ 狀態
> 使 folder 狀態回到 //? '前一個節點狀態!'
且 新增一個節點

git revert commitID
使 folder狀態回到 該commitID的 //?'前一個'節點狀態!

git reset commitID 
//* 則是回到 '該節點' 狀態
