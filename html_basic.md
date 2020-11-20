## 簡介
```
網頁前端:
HTML：網頁內容的描述語言  (標記語言)
CSS：網頁外觀形態的描述語言  (標記語言)
JavaScript：一門函式先行的直譯式程式語言，經常用在呈現網頁動態效果。
```
###### HTML5
```
優點:
1. 網頁結構強化
2. 畫面以及多媒體播放強化
3. 可新增API
4. 支援跨載具
缺點:
1.各瀏覽器支援程度不一
主要在於HTML是由全球資訊網協會（W3C）完成的標準制定，並由各瀏覽器、網路平台以及開發者滿足其規則。也因為各家爭鳴的關係，導致同樣的描述語言所支援的效果不同，或是根本沒有支援。
舉例來說，各瀏覽器對HTML、CSS以及JavaScript支援的程度或呈現方式就有所不同。
光是一個下拉選單的HTML描述語言，在不同的瀏覽器內呈現的效果就有所不同。
```
########### ie
![image](https://github.com/kampfcl3/html/blob/main/pic/IE.png)
########### chrome
![image](https://github.com/kampfcl3/html/blob/main/pic/google.png)
```
其中以舊版的IE 6存在最多問題，存在元素堆疊Bug、幽靈字元（字在IE瀏覽器上消失）、元素的消失（陰影或漸層效果看不到）。
為了讓網頁在各瀏覽器呈現效果盡可能一致，開發者往往被迫寫出繁瑣的程式碼來「正確顯示原本的設計」。

2.特定效能仍無法取代
Facebook創辦人兼執行長Mark Zuckerberg就曾發表過，用HTML5寫出的Facebook App無法達到他們想要的品質，
所以最後還是選擇用Object-C進行開發（一種開發Apple iOS的程式語言）。

主要原因在於HTML5對動畫以及影音上的技術支援仍不夠成熟。
```


## 網頁架構
```
<HTML>
　<HEAD>
　　<TITLE>網頁製作教學</TITLE>
　　<Meta>
　</HEAD>
　<BODY>
　　BODY之間則為主要語法所在，也是網頁的主要呈現部分。
　</BODY>
</HTML>
```
```
1.<TITLE></TITLE>這裡面的文字會出現在瀏覽器視窗最上頭藍色部份裡
2. <HTML></HTML>表示標籤內檔案為html檔
3.<HEAD></HEAD> 表示此網頁的基本
<head>
  <meta charset="utf-8">
  <meta name="description" content="Free Web Tutorial">
  <meta name="keywords" content="HTML,CSS,JavaScript">
  <meta name="author" content="Mike">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
 # <meta> : tag 用來描述 HTML 文件 (document) 的元資訊 (metadata)，透過 <meta> 我們可以設定很多不同類型的網頁資訊。
4.<BODY></BODY>裡為程式本體
```
#### 分隔標籤 
```
1. <br> 強制斷行標籤 效果:空上一行
2. <p> 強制分段標籤  效果:上下各空一行
3. <hr> 分隔線 
   a. <hr color="顏色碼或顏色名稱">
      ex: <hr color="#ff8000">
   b. <hr width="寬度"> 其單位為px（像素），寬度亦可用百分比來作設定，如50%即意為寬度佔螢幕50%。
      ex:<hr width="240">  
      寬度為240px的分隔線
   c. <hr size="厚度"> 
      ex:<hr size="5">
   d. <hr align="水平對齊位置">
      ex:<hr align="right">
      3個屬性:置左align="left"、置中align="center"、置右align="right"
4.文字置左、置中、置右
   a. <p align="left">text left</p> 
      text left
   b. <p align="center">text mid</p>
                text mid
   c. <p align="right">text right</p>
                         text right
   # align=對齊位置
   
   <center>this is mid</center>
          this is mid
   任何可以顯現在網頁上的東西都可以置中
5.<blockquote></blockquote>
   可以將其包起來的文字，全部往右縮排。而且加一組標籤，往右縮排一單位，加兩組
   標籤，往右縮排兩單位，依此類推。
   ex1:<blockquote>縮排1單位</blockquote>
        縮排1單位
   ex2:<blockquote><blockquote>縮排2單位</blockquote></blockquote>
        縮排2
        單位
6.<pre></pre>
   這個標籤可以將其包起來的文字排版、格式，原封不動的呈現出來
   ex: <pre>
       文　字
　       格　式
       </pre>
   文　字
　   格　式
7.<h1>標題內容</h1>
<h1>到<h6>，<h1>最大，<h6>最小。使用標題標籤時，該標籤會將字體變成粗體字，並且會自成一行。
```
![image](https://github.com/kampfcl3/html/blob/main/pic/h1.png)
```
<font size=3>文字內容</font>
```

#### 參考
```
http://www.dlps.tc.edu.tw/html_teach/#t3
https://www.fooish.com/html/meta-tag.html
https://www.w3schools.com/html/default.asp
```
