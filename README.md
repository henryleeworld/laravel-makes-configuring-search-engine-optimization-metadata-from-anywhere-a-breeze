# Laravel 11 輕鬆從任何地方設定搜尋引擎最佳化（SEO）中繼資料

引入 honeystone 的 laravel-seo 套件來擴增輕鬆從任何地方設定搜尋引擎最佳化中繼資料，不僅讓使用者更容易理解網頁的主要內容，同時也讓搜尋引擎的爬蟲能夠更有效地解析和索引網站資訊。

## 使用方式
- 把整個專案複製一份到你的電腦裡，這裡指的「內容」不是只有檔案，而是指所有整個專案的歷史紀錄、分支、標籤等內容都會複製一份下來。
```sh
$ git clone
```
- 將 __.env.example__ 檔案重新命名成 __.env__，如果應用程式金鑰沒有被設定的話，你的使用者 sessions 和其他加密的資料都是不安全的！
- 當你的專案中已經有 composer.lock，可以直接執行指令以讓 Composer 安裝 composer.lock 中指定的套件及版本。
```sh
$ composer install
```
- 產生 Laravel 要使用的一組 32 字元長度的隨機字串 APP_KEY 並存在 .env 內。
```sh
$ php artisan key:generate
```
- 在瀏覽器中輸入已定義的路由 URL 來訪問，例如：http://127.0.0.1:8000。
- 你可以經由 `/` 來進行歡迎頁面瀏覽。

----

## 畫面截圖
![](https://i.imgur.com/EkPT0p9.png)
> 提升了網站內容的組織性，也為網站帶來了更多的機會，讓其在競爭激烈的網路世界中脫穎而出
