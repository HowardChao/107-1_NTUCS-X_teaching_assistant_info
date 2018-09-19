# R Crawler 網路爬蟲

爬蟲最困難的地方不在於程式撰寫，而在於對於網站的觀察，很多網站都有超過一種以上的爬蟲方法可以爬取，而這時就要透過觀察網頁所累積的經驗來判斷用什麼方法能夠達成目標，因此學爬蟲最好的方法就是盡量多爬幾個網站，看多就變高手了。以下列出簡易的爬蟲流程給大家參考：

1. 觀察網站是靜態還是動態
2. 觀察網站的 css與 xpath結構 (靜態) 或 network活動(動態) 並進行爬取
3. 利用 dataframe等資料結構處理資料
4. 存入 csv 或 database
---

## 使用R，建構一支爬蟲!
[R語言爬蟲常用方法](https://hk.saowen.com/a/8e2d738e015011cd6648742b975022e971c17f23117b9fca4ab59b7d68c2520d)
1. rvest: 簡單好用的爬蟲套件
    * [之前自己整理的常用function~~](https://howardchao.github.io/CSX_RProject_Spring_2018/week_2/task_2_self_practice/R_crawler_rvest_document.html)
    * [rvest tutorial: scraping the web using R](https://stat4701.github.io/edav/2015/04/02/rvest_tutorial/)
    * [使用 R 與 rvest 套件擷取網頁資料](https://blog.gtwang.org/r/rvest-web-scraping-with-r/)
    * [超簡單爬蟲教學-使用R軟體的rvest套件抓網站資料(基礎篇)](http://brucehau.blogspot.com/2016/09/rrvest.html)
    * [第一次爬蟲就上手 rvest_tutorial](https://rpubs.com/SatoshiLiang/159348)
2. httr
    * [之前自己整理~~](https://howardchao.github.io/CSX_RProject_Spring_2018/week_2/task_2_self_practice/R_crawler_httr_document.html)
    * [R Crawler R爬蟲(httr package)](http://chihchengliang.github.io/DSC2015_Crawler/)
    * [SNP Annotation 網路爬蟲](https://blog.gtwang.org/r/r-httr-package-snp-annotation-examples/)
3. xml2
    * [用xml2爬美國中情局(CIA)的解密文件資料庫](https://rpubs.com/skydome20/R-Note13-Web-Crawler-on-CIA-CREST-by-xml2)
4. jsonlite
    * [R 的 JSON 格式資料處理套件](https://blog.gtwang.org/r/jsonlite-json-format-parser-generator-tutorial/)


---
## 補充資料
1. 什麼是爬蟲?
    * [網路爬蟲MBA智庫百科](https://wiki.mbalib.com/zh-tw/网络爬虫)
2. 關於request & response
    * 請搭配下述Postman與httpbin學習!
3. 關於網頁結構與爬蟲
    * [XML & HTML 差別](https://www.eztrust.com.tw/html/faq/qa_show.aspx?id=122)
    * [HTML Tutorial](https://www.w3schools.com/html/)
        * **舉例： 網頁架構會用到 html**
        * 網頁前端語言: HTML(架構、骨架), CSS(樣式), JavaScript(動態、使用者互動、邏輯判斷) 
    * [XML Tutorial](https://www.w3schools.com/xml/default.asp)
        * XML stands for eXtensible Markup Language.
        * XML was designed to store and transport data.
        * XML was designed to be both human- and machine-readable.
        * 一種儲存資料的格式
        * **舉例： android app 開發，介面排版會用到 XML**
    * [XML Path Tutorial](https://www.w3schools.com/xml/xpath_intro.asp)
> 以上不用到可以自己寫出來，不過要看的懂架構！

4. 常用爬蟲工具
    * Google Chrome: [瀏覽器內之開發人員工具介紹](http://tech-marsw.logdown.com/blog/2016/01/10/crawler-tips-mining-chrome)

    * [SelectorGadget](https://chrome.google.com/webstore/detail/selectorgadget/mhjhnkcfbdhnjickkkdbjoemdmbfginb?hl=zh-TW) or [InfoLite](https://chrome.google.com/webstore/detail/infolite/ipjbadabbpedegielkhgpiekdlmfpgal)
    以CSS結構進行網頁觀察
    * [Xpath Helper](https://chrome.google.com/webstore/detail/xpath-helper/hgimnogjllphhhkhlmebbmlgjoejdpjl?hl=zh-TW)
    以Xpath結構進行網頁觀察
    * [JsonViewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh?hl=zh-TW)
    讓json格式資料美美搭=_+
    * [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=zh-TW)
    搭配[httpbin](http://httpbin.org/#/)，快速了解關於HTTP Request、Response
