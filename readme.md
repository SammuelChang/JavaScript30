```
此為JS30練習紀錄，每日目標進行方式如下：

1. 觀賞官方說明影片
2. 檢視Finish Code
3. 依照自己理解，參考Finish Code進行撰寫
4. 過程中如有疑問或認為當日重點，均會整理到readme中
```

### 01 - JavaScript Drum Kit
(暫略)

### 02 - JS and CSS Clock
(暫略)
### 03 - CSS Variables
- 主旨：熟悉CSS變數使用
- 相關概念：CSS變數、圖片調整、dataset、JS操作CSS
- 值得紀錄的錯誤：
  1. dataset綁定到global，因為習慣寫arrow function，導致this沒有正確指向global而無法取得dataset資料
  2. addEventListener前面應加上綁定對象，否則為全域綁定（導致我在mousemove時，整個畫面都觸發事件）
### 04 - Array Cardio Day 1
- 主旨：熟悉array操作方法
- 相關概念：filter, map, sort, reduce
- 值得紀錄的錯誤：
  1. Sort the people alphabetically by last name
     雖然知道排序是由左至右依照字母，但不太確定如何拆出來
     ※ 需再熟悉sort如何靈活運用
  2. Sum up the instances of each of these
     邏輯上大致清楚，但思考方向為array，若改以object思考則應該可以寫出。
     ※ 需再熟悉reduce如何靈活運用於資料變形