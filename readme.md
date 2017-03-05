# 作業要求

* 幫每則日記加上刪除按鈕，按下去後會從畫面刪除，同時也會更新到瀏覽器 local storage

* 為了幫助大家更熟悉 css 的使用，請參考 css/theme/default.css 和 css/theme/clear.css 的內容，自己建立一套新的主題，並加入到 select 選項中

* 挑戰題：jQuery 有非常非常多 plugin，除了課堂中提到的 jQuery UI、bootstrap 還有很多其他 plugin，請試著使用一套第三方的 jQuery datepicker 或 calendar 套件或自行手刻加入一個小的月曆在旁邊，當點選日期時，畫面上只會顯示當天的日記



## 預先 compile pug (jade) 方法


### 安裝 npm 套件

```
    npm install pug-cli --save-dev
```


### entries.pug 在 command line compile 的指令是

```
    node_modules/.bin/pug -c -D template/src/entries.pug -n entries_template -o template/dist
```
```
    pug -c -D ../../template/src/entries.pug -n entries_template -o ../../template/dist
```
