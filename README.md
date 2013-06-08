## 世界奇觀

![](http://www.hawkaoc.net/bbs/data/attachment/forum/dvbbs/20031071133156749.jpg)

###伐木工

* [littleq0903](http://about.me/littleq)
* snowmantw
* hychen
* 請自行新增

###專案簡介

~~蓋滿 180 天後獲得勝利~~，把大家需要用的共同資料整理成 Graph，讓大家自行取用

專案期限：當然是 180 天了

專案發起日期：2013/06/08

專案預測完工日期：2013/12/5

工作目標：（分成N階段）

1. 先用假資料填充，模擬 Graph API 運作情形。
1. 資料完成結構後再來寫 server
1. 後端 stream-in 跟前端 stream-out 各 API 討論
1. 各種權限控管
1. stream-out clients: 如何增加 relation, object ;以及如何管理、註冊、刪除 App
1. stream-in sources: 如何增加來源，以及來源需要的屬性設定
1. 例如該來源的資料是 mutable 或 imutable 

狀態：填充假資料中

###github repo

https://github.com/g0v/ww-simulation/

###example api call

[id:1] http://g0v.github.io/ww-simulation/api/1/this (先用 this 代替空白）

[id:1 -> relation:news]http://g0v.github.io/ww-simulation/api/1/news

###徵求夥伴

* NeedTxtHacker: 需要 txt hackers 來幫忙填充假資料
* NeedBackendDeveloper: 幫忙寫 Graph server 的 backend server