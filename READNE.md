# Gulp Practice 編譯範例

這是包含以下幾個套件的 **Gulp** 範例：

1. **gulp-babel**   // ES6 編譯套件

2. **gulp-uglify**  // 壓縮套件

3. **gulp-concat**  // 檔案整合套件

4. **gulp-rename**  // 檔案更名套件

5. **gulp-sass**    // 顧名思義 Sass/Scss 編譯套件

6. **browser-sync** // 模擬瀏覽器套件

7. **gulp-watch**   // 檔案監聽套件

---

## 使用方法

```
1. $ git clone https://github.com/RexHung0302/GulpPractice.git

2. $ cd GulpPractice

3. $ gulp / gulp default

4. Enjoy it!
```

---

Gulp 小筆記：

```
$ npm init & npm init -y  // 前者可以詳細配置 後者快速建置

$ npm install gulp-cli -g // 安裝全域的 gulp-cli

$ cd xxx                  // 移至至你的專案

$ npm i -D gulp           // 安裝 gulp 到專案

$ touch gulpfile.js       // 創建核心檔案

$ npm i -D gulp-babel @babel/core @babel/preset-env // 安裝 ES6 編譯工具

$ npm i -D gulp-uglify    // 安裝壓縮套件

$ npm i -D gulp-concat    // 安裝檔案整合套件

$ npm i -D gulp-rename    // 安裝檔案更名套件

$ npm i -D gulp-sass      // 安裝編譯 sass 套件 會連同 node-sass 一起安裝(編譯 scss 也可以)

$ npm i -D browser-sync   // 安裝瀏覽器同步顯示套件

$ npm i -D gulp-watch     // 安裝監聽檔案套件

// Gulp 安裝方法可繼續往下看

```

> *小知識： npm i -D 為縮寫， i 為 install 的縮寫， -D 則為 --save-dev 的縮寫。*

---

# 安裝方法：

相關配置都可以參考 **gulpfile.js**，如果有安裝流程不明白歡迎參考我的部落格 **[[Tool Notes] — 關於Gulp](https://rexhung0302.github.io/2020/05/05/20200506/)**。

關於 **HTML** 其實還能在安裝 模板，這邊就先做到基礎的自動化架構，日後再補上關於 **HTML** 的模板套件，而仔細看你會發現 **gulpfile.js** 上方引入了很多套件，其實還能安裝 **gulp-load-plugins** 來做到不需要 **require** 套件，只靠 **gulp-load-plugins** 便可以將 **package.json** 的套件全部引入進來，但這邊沒有安裝，這樣引用的套件比較明瞭，或許之後還會再更新一版上來，會再加上。

---

# 相關介紹文章

[[Tool Notes] — 關於Gulp](https://rexhung0302.github.io/2020/05/05/20200506/)

---

# 額外推薦

[[Tool Notes] — 關於Webpack #1 - 第一次就上手](https://rexhung0302.github.io/2019/06/18/20190618/)

[[Tool Notes] — 關於Webpack #2 - Babel？](https://rexhung0302.github.io/2020/03/21/20200321/)