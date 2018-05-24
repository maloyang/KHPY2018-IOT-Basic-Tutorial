# KHPY2018 IOT Basic Tutorial

## 課程目標

希望大家可以透過課程學到：
- MicroPython的硬體基本知識
- 使用Python做基本的IOT應用
- 把sensor資料送上雲端，並用手機監控(Android)
- MicroPython硬體結合Line的應用
- MicroPython單晶片的環境下建立網頁


## 課前提醒事項
- 上課學員需自備筆電
- 硬體將於上課時發放，學員不需要自行準備
- 建議在課前先在電腦安裝Anaconda、VSCode


## 本課程適合對象
- 至少會安裝Python，並用Python執行"Hello World!"程式
- 已經稍微了解 Python 的基本語法，想要進一步了解如何用Python和單晶片硬體互動者
- 對Python在IOT的應用有興趣者
- 對基本語法還不夠熟的朋友，可以先參考：https://github.com/victorgau/Python_Basics


## 課程大綱

- 簡介 (10分鐘)  
    - 說明課程含蓋的主題
    - 說明一下硬體背景

- MicroPython 基本硬體介紹 (50分鐘)
    - 連線方式、腳位說明
    - 以操作Led為練習

- 蜂鳴器 (Buzzer, 無源) (45分鐘)
    - 基本Do, Re, Mi
    - 練習寫歌 (小星星、小蜜蜂)

- 練習、休息 (15分鐘)

- 溫溼度感測器 (50分鐘)
    - 基本量測練習 (10分鐘)
    - 溫度鴨實作 (溫度感測器+蜂鳴器) (40分鐘)
    ![溫度鴨](https://s.yimg.com/ut/api/res/1.2/kpDKLsamvN5nuUvAiaFXsg--~B/YXBwaWQ9eXR3bWFsbDtjYz0zMTUzNjAwMDtoPTYwMDtxPTgxO3c9NjAw/https://s.yimg.com/sw/ps_image_prod/item/p09073350080-item-1515xf3x0270x0270-m.jpg)

- ----中餐 12:00~13:00 ----

- 雲端應用教學 (80分鐘)
    - 雲端介紹(MQTT)
    - 手機設定方式(先讓學員連講師的資料)
    - 溫溼度資訊上雲端
    - 手機控制Led
    - 手機加入自己的點位

- 休息 (10分鐘)
   
- 溫度警報器 (line訊息警報) (50分鐘)
    - line 訊息機制說明
    - line警報訊息實作

- 網頁實作 (40分鐘)
    - 單晶片如何實作網頁伺服器
    - 練習題：製作網頁顯示溫溼度資訊
    - 練習題：製作網頁控制蜂鳴器發聲
