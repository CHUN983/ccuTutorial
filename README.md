# HTML 基礎課程 - 網頁設計入門

## 課程目標
本課程將介紹如何建立一個基本的網頁結構，並涵蓋 HTML、CSS 和 JavaScript 的基礎知識。學生將學習如何設計網頁，並學會如何使用 CSS 製作美觀的版面布局。

## 課程大綱

1. **HTML 基礎結構**
   - 介紹 HTML 標籤
   - `<html>`, `<head>`, `<body>` 的結構
   - 使用 `<meta>` 設定字符編碼
   - 引入外部資源（如：Font Awesome 圖標庫）

2. **HTML 元素**
   - `<header>`, `<main>`, `<aside>`, `<footer>` 的用途
   - 連結與圖片標籤 `<a>`, `<img>`
   - 使用 `<ul>`, `<li>` 標籤創建導航列

3. **CSS 樣式設計**
   - 設定元素的樣式：`color`, `background-color`, `font-size`
   - 了解盒子模型（Box Model）
   - 使用 `position` 屬性設計固定與浮動元素
   - 設定頁面佈局：`float`, `clear`
   - 使用 `hover` 效果來增加互動性

4. **JavaScript 基礎**
   - 使用 `fetch()` 方法載入外部 HTML 內容
   - 如何處理 `then()` 和 `catch()` 來處理異步請求

## 詳細內容

### 1. HTML 基礎結構
HTML 是用來設計網頁結構的標記語言。它由一系列標籤組成，通常包括 `<!DOCTYPE html>`，`<html>`，`<head>` 和 `<body>`。

```html
<html>
    <head>
        <meta charset="UTF-8">
        <!-- 引入 Font Awesome 圖標庫 -->
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    </head>
    <body>
        <header>
            <img src="01.png" height="150px" width="100%">
        </header>
        <!-- 主體內容區域 -->
        <main>
            <iframe  name="contentFrame" src="main.html" width="100%" height="100%" style="border:none;"></iframe>
        </main>
    </body>
</html>
