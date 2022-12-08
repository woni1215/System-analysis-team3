### 專題主題 : 學餐訂餐系統

|職位|姓名|學號|任務|
|:--:|:--:|:--:|:--:|
|組長|李宜蓁|C109118138|後端|
|組員|許雅妮|C109118141|測試&維護|
|組員|林芳妤|C109118144|資料庫|
|組員|蘇翔玉|C109118103|前端&UI|
|組員|鄭祺萱|C109118153|文書|
---
### 內容
每到中午時分，學生們一窩蜂的擠進學餐進食，可能晚了一步就要等相當長的時間才能用餐。於是我們想若是能夠製作一個訂餐系統、提前點餐，店家提前製作完成，不僅可以加速取餐時間，也能取代店家人工叫號的方式，避免離開一下回去時不知道自己是否可以取餐。

---
### 甘特圖
```mermaid
gantt
    title 學餐訂餐系統
    dateFormat  YYYY-MM-DD
    section Task 1
    訂定主題 :t1 , 2022-10-03 , 1w
    section Task 2
    探討系統功能 :t2 , after t1 , 1w
    section Task 3
    蒐集店家資料 :t3 , after t1 , 1w
    section Task 4
    設計消費者UI介面 :t4 , after t2 , 2w
    section Task 5
    設計店家UI介面 :t5 , after t2 , 2w
    section Task 6
    系統功能製作 :t6 , after t4 , 3w
    section Task 7
    建構資料庫 :t7 , after t6 , 1w
    section Task 8
    功能測試 :t8 , after t6 , 1w
    section Task 9
    資料庫連線 :t9 , after t8 , 1w
    section Task 10
    資料庫測試 :t10 , after t9 , 1w
    section Task 11
    使用者測試 :t11 , after t10 , 1w
    section Task 12
    系統改良優化、完成 :t12 , after t11 , 1w
```
---
### PERT/CPM圖
![PERT/CPM圖](pert_CPM.JPG "PERT_CPM")

### 關鍵路徑
1->2->5->6->8->9->10->11->12
