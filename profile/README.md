# Taiwan Carbon Map

可以讓使用者查詢往年以及預測未來台灣各縣市碳排放量的APP

## 亮點功能

1. 互動式台灣地圖\\
   使用者可以透過點選台灣地圖來選擇想要查詢區域
   
2. 碳排放查詢與預測\\
   選取想要的地區後可以選擇想要查詢的日期區間(以月分為單位)
   接著我們會以折線圖的形式來呈現統計數據
   對於未來的碳排放量，我們使用**季節性的差分移動回歸模型**來預測

## 技術架構
* App: Flutter, Vue.js
* Database: MySQL
* Backend: Golang
* Forecast Model: SARIMAX with PyTorch

