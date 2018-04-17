# Git Practice

# 步驟
* 先建立 README.md 檔案
* 執行下列
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/RocMark/Git-Practice.git
git push -u origin master

# 記憶帳號
會要求輸入帳密，上傳後，執行下列進行記憶帳密
* git config credential.helper store
//? 執行此行後，之後只需要 git push 即可
* remove 帳號記憶
git config --local -e
//* 刪除以下兩行
[credential]
	helper = store

# 設置 Commit Editor
> 原文 http://t.cn/RmnzKQG
1. vscode 終端機  code --help
> 若無出現提示，見原文 
2. git config --global core.editor "code --wait"
3. git config --global -e  (此為全域設定)
//? 此會自動打開 .gitconfig 檔 設定在裡面
4. git config --local -e (此為本專案設定)
可查看 remote & 是否儲存帳號

5. git commit 不加 -m 會自動打開

# 設置 .gitmessage 模板

1. 建立 .gitmessage file
2. 內文撰寫 Template
3. 設定template
git config commit.template "補上資料夾位置"/.gitmessage
4. git commit 即可 進入編寫

//* 取消設定 git config --unset ~
//? git config -l 可查看有哪些設定可用

<!-- C:\\Users\\RocMark\\Desktop\\Git Prac\\.gitmessage -->