## Git使用

找到一個空的資料夾
> git init

新增一個檔案之後，把所有檔案加進去
> git add .

接著提交變更
> git commit -m '版本1_測試'

---

git功能|指令
-|-
初始化專案|git init
查看狀態|git status
檢查差異|git diff 
將變更檔案放入暫存區|git add index.py
將所有檔案放入暫存區|git add .
提交變更|git commit -m '版本備註(不可空)'
查看commit log歷史|git log
放棄已經 commit 的檔案重回暫存區|git reset HEAD index.py
放棄檔案變更(commit的變成沒commit)|git checkout -- index.py
新增分支|git branch 分支名
切換到分支|git checkout -b 分支名 (-b可省略)
切換到master|git checkout master
合併ooxx|git merge ooxx
將ooxx的變更變成master的並commit|git checkout ooxx & git rebase master
 

---

## pull、clone差別
#### clone:專案第一次看到下載請用git clone

#### pull:clone之後的更新並且與本地的merge，請用git pull

- git clone url
- git pull url
