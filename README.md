# ORDERLY Python / Django Interview
Python / Django Web Developer

Hi,

感謝您

這是根據您的回覆所訂製的問題，大約會花費 3- 5 小時的挑戰時間

若您決定要開始這項挑戰，請 fork 此專案，並將每個問題的答案放至對應的資料夾

完成後，請發個PR到此專案

### 挑戰一: OO觀念運用 (folder: x_1)

> 現在您的手上有 3 支手機，手機來自不同品牌，其規格屬性大同小異，但各自擁有一項特殊功能，請使用OO繼承及如下的規格，設計出這三支手機的class。

```
手機共通屬性: price, camera_count, screen_size
特殊功能: special_freature() 

手機一 google phone:
price=10, camera_count=3, screen_size=5
special_freature 輸入一個int list, 回傳偶數且大於10的元素，並由大至小進行排序
例如: 輸入 [3, 43, 62, 15, 18, 22] 回傳 [62, 22, 18]

手機二 taiwan phone:
price=20, camera_count=1, screen_size=3
special_freature
輸入一個數字自動計算Fibonacci斐波那契數列的運算結果，並取最後二位(十位為 x、個位為 y)數字進行 p x 取 y (排序組合) 計算。
例如: ---

```


### 挑戰二: pip 及 Django 實作  (folder: x_3)

> 請參考 https://github.com/twtrubiks/django-tutorial 的教學，將您的Django 運行起來，並進行以下步驟:

1) 使用 pip 將你安裝的所有 python 模組及其版本變成一個 requirement 檔案
2) 將 Django 後台路徑從 /admin 修改成 /superadmin 
3) 新增一個 django app "ilovecoffee", 並於settings.py啟用它
4) 在 ilovecoffee 中，新增 models.py 檔 ，並創建一個 Coffee class, 不需要任何屬性和功能 (請注意這不代表class code裡面沒東西)
5) 在當前的虛擬環境中使用 python manage.py shell，並將 Coffee import 進來，將結果截圖放至此資料夾，取名為 coffee.jpg


### 挑戰三: 開發分配 (folder: x_3)
> 現在有一個商用軟體產品，該產品剛上線滿一年，已有一定的客戶量體，但系統穩定度不足，且功能仍然簡陋，因此產品開始有許多的需求要被分配開發資源，假設現在是星期三早上10點鐘，請您針對以下狀況進行思考，並說明每一項的應對方式:
```
(A) 重量級客戶10天前提出的改進需求，需耗時6小時完成，此需求你評估認為非常實用。
(B) 昨天晚上系統發出的 alert, 警示訊息為客戶操作出錯
(C) 早上九點系統發出的 alert, 警示訊息為DB異常
(D) 剛剛你無意中注意到的前台破圖，大約20分鐘可搞定
(E) 近三天專注開發的一項功能，如果現在不接著工作，很可能會忘記重要事項
(F) 昨天寫程式時，無意中發現的程式bug，但不在自已掌管範圍內
.....
````


## 當您挑戰結束時，請在您的最後一次 commit 中輸入您對此份工作，在程式上的期待，謝謝您。

