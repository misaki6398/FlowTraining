score: 10/100


修改清單
========

- `merge`  回主線：回主線三個字前的空格數 2 -> 1
- __一起開發__ -> **一起開發**
- repository 至 local -> repository 至 Local  （這個好像不能稱之為亂改，是訂正呵呵）
- 1oca1 repository -> loca1 repository
- 刪除 list 最後一項 |gitk | 神奇的東西 |

______________________________________________________________________


我在這個 task 中理解到的 git 是什麼東西
=======================================

git 是一個能夠靈活控管專案版本的版本控制系統。
---------------------------------------------

  - 能產生及跳轉至不同 branch，並可以在事件後 `merge` 回主線
  - 兩個版本 merge 時如果同一段落都被修改過，則會發生*衝突*（conflict）需要手動擇一或者另做修改
  - 結合 GitHub 方便許多人**一起開發**同一個 project
  - 妥善寫下 commit message 能夠方便日後檢視


|在 task-1 中接觸到的指令|目前理解的用途簡述 |
|-----------------------|-----------------|
|git clone| 從 GitHub 上下載 repository 至 Local |
|git status| 查看目前 Head 所處 Local repository 的狀態 |
|git log| 查看 commit 歷史紀錄 |
|git add| 從 working directory 添加/更新檔案至 staging area |
|git commit| 將 staging area 內的檔案狀態記錄到 local repository |
|git checkout| 切換 branch |
|git branch| 檢視/創建 branch |
|git remote| 檢視/設定遠端 repository |
|git push| 將 local repository 推送至遠端 repository |
|git reset| 移動 HEAD 指向指定 commit |


| 項目 | 參考來源 |
|------|----------|
| git  |[git SCM]|
|Markdown|[task_說明]|


[git SCM]: https://git-scm.com/book/zh-tw/v2/
[task_說明]: https://github.com/MontyPan/FlowTraining/blob/master/Task_1.md

 
