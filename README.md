# 上課心得


老師真的好有愛心，感覺就是個好主管，很注意學習進度。



# 上課筆記


```bash=
$ git clone 載下來
$ git init 本地創建

$ git status 看狀態

$ git add <檔案> -> $ git commit -m "內容" ->$git push
本地                  本地                  github
完整一套流程 

$ git diff 比較

$ git restore --staged 取消add

$ git branch
# 檢視分支
# * 是標注你所在的分支


$ git branch <branch-name>
# 建立分支 

$ git switch <branch-name>
# 切換分支

$ git checkout HEAD
回到現在版本

$ git switch main
$ git merge feature-login
# 如果兩個分支有提交過同一個檔案的修改，那就有可能發生衝突 confict
# 就只能人工修改，可能需要跟同事討論
# 解完衝突之後，就要再 commit 一次