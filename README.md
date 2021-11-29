# F2E-WEEK1 台灣旅遊景點導覽
## [GitPage頁面連結](https://th1230.github.io/F2E-WEEK1/)

## 使用的相關工具以及框架

#### 框架
* angular 

#### github上傳工具
* angular-cli-ghpages [npm連結](https://www.npmjs.com/package/angular-cli-ghpages)

#### 使用的OpenAPI 
* TDX運輸資料流通服務 [API連結](https://tdx.transportdata.tw/api-service/swagger)

## 網頁結構

#### 頁面簡介

1. home(為主頁顯示部分活動以及餐飲，可透過點擊城市圖片跳轉至活動和景點的搜尋頁面)
2. foodandlive(為餐飲以及住宿的搜尋頁面)
3. bus-traffic(搜尋公車資料)

#### 組件分類

1. components-----主要放通用的header/navbar/footer組件
2. exceptComponents-----放置error/loading組件
3. shareComponents-----放置各個搜尋頁面通用的組件
  1. straight-card-----為垂直顯示card(單個)組件
  2. thward-card-----為水平顯示card(單個)組件
  3. page-bar-----為搜尋頁底下的換頁組件
  4. detail-card-----顯示card的詳細資料的組件
  5. hot-activity-----顯示熱門活動的組件，包含多個thward組件
  6. hot-straight-list-----用於包含多個straight組件的list組件，用於顯示搜尋結果
  7. hot-city-slider-----為主頁上城市跳轉頁面的card集合
  
#### service分類

1. data-service-----存放所有http api
2. detail-status-----管理有關detail-card2的資料
3. form-data-manage-----管理搜尋form的資料
4. page-controler-----管理page-bar組件的資料
5. traffic-form-manager-----管理公車的form資料

#### interceptor

* 主要為所有api加上header

#### 圖片

* 所有靜態圖片放置在assets/images中

## 心得

##### 第一次參加這次f2e活動，在非常驚險得情況下交出了我得第一份實作，說實在並不簡單，不過熟能生巧麻，希望之後的兩週能做得更好!!!
