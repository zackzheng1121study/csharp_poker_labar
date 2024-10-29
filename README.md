# csharp_poker_labar
### **說明**
1. 設計一張背景圖當作表單的背景
2. 建立
    * 三個圖片方塊(picturebox)
    * 一個未按和已按拉稈圖示(picturebox)
    * 一個標籤顯示目前可投注總數量(Label)
    * 一個數字按鈕用來設定每次投注量(numericUpDown)
3. 拉霸機上三個圖示
    * 建立pictureBox陣列，儲存三種元素
    * p[1] = pic1
    * p[2] = pic2
    * p[3] = pic3
4. 計時器(timer)控制亂數取圖
    * 每隔0.1秒重新亂數取圖一次
    * 連續20次停止計時
5. 判斷中獎
    * 荔枝代碼 0
    * 星星代碼 1
    * 西瓜代碼 2
    * BAR代碼 3
6. 按下拉稈判斷
    1. 投注量是否大於0 或 投注量是否小於總數量？
    2. 啟動timer計時器，減掉本次投注量，使rndQty無法使用、BtnPic圖示紐失效、BtnPic以圖示(down.jpg)顯示
    3. 出現對話方塊並顯示 "投注有誤"

   ![image](https://github.com/user-attachments/assets/4a2cdcef-0a06-48e5-85f7-7a2161bf1955)
