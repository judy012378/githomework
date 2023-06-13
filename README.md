# GIT作業

## 操作方式 
### 先點右上角 Fork 按鈕，把這個 repo，叉回去自己的 github 帳號
### git clone 叉回去自己 github 帳號的 repo
### 按下述作業要求進行操作

## 作業1 - cherry pick
1. 以分支: **dev** 為基底，建立一個分支: **cp** 
2. 切換到分支: **cp**
3. 使用 **cherry-pick** 把 "**cherry-pick測試**" 這個 commit 從 來源分支: **master** 撿到 目標分支: **cp** 上
4. 處理衝突
5. 把處理好的分支: **cp** push 到 github 上

## 作業2 - merge
1. 以分支: **dev** 為基底，建立一個分支: **mg**
2. 切換到分支: **mg**
3. 使用 **merge master**
4. 處理衝突
5. 把處理好的分支: **rb** push 到 github 上

## 作業3 - rebase
1. 以分支: **dev** 為基底，建立一個分支: **rb**
2. 切換到分支: **rb**
3. 使用 **rebase master**
4. 處理衝突
5. 把處理好的分支: **rb** push 到 github 上

## 作業4 - reset
1. 以分支: **master** 為基底，建立一個分支: **rs**
2. 切換到分支: **rs**
3. 使用 **reset** 把分支恢復到 "**reset測試**" 這個 commit
4. 把處理好的分支: **rs** push 到 github 上

## 寫完作業，把你叉回去的這個 github repo link 發給 Claude 檢查
