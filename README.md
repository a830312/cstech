cstech
======
1. 下載程式zip檔: https://github.com/a830312/cstech


2. 安裝apache

3. 修改httpd.conf中的DocumentRoot: 多加一層/cstech
    (httpd.conf說明: http://www.twisu.com.tw/5/linset/www1.htm)
    a. (修改點一)
    DocumentRoot "系統預設值/cstech"
    b. (修改點二)
     This should be changed to whatever you set DocumentRoot to.
    <Directory "系統預設值/cstech">

4. 將解壓縮後的cstech資料夾加入DocumentRoot的系統預設值目錄中 

5. 檢視畫面: 打開瀏覽器輸入localhost/index

6. 檢視畫面: 打開瀏覽器輸入localhost/main

======

require:
composer
http://getcomposer.org/

template:
mustache
https://github.com/bobthecow/mustache.php/wiki/Mustache-Tags

theme:
bootstrap
http://getbootstrap.com/getting-started/

js:
jquery
http://api.jquery.com/
