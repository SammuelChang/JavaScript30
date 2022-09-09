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
