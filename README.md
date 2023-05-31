# remote-repo
The history of my learning programming languages (html/css/javascript).

## html 語法記錄
### 網頁開頭：
一. 在 vscode 中，輸入 'htm' 會自動提示選項，選擇 'html:5' 後按下<kbd>Tab</kbd>。或自行輸入如下 共9行

```html 
<!DOCTYPE html>
<html lang="zh-tw">
    <head>
        <meta charset="UTF-8">
        <title>網頁抬頭</title>
    </head>
    <body>
    </body>
</html>
```

二.在標籤`</head>`前一行輸入 'lin'會自動提示選項，選擇 'link' 後按下<kbd>Tab</kbd>。常用的.CSS 引入如下

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link rel="stylesheet" href="css/styles.css">

<!-- 也可用 @import -->
<style>
@import "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css";
@import "css/styles.css";
</style>
```

三.依續畫分網頭、網身、及網腳。  
1. 網頭:在標籤`<body>`後一行輸入 'div.web-header' 後按下<kbd>Enter</kbd>。  
```html
    <div class="web-header">
```

2. 網身:在網頭標籤`</div>`後一行輸入 'section.section-bg' 後按下<kbd>Enter</kbd>。 
```html
    <section class="food-menu section-bg">
```

3. 網腳:在網身最後標籤 後一行輸入 'div.web-footer' 後按下<kbd>Enter</kbd>。  
```html
    <div class="web-footer"></div>
```
***
## css 語法記錄
### display: grid 用法：
一.有標籤`<img>`先設定參數。
```css
.img
{
    max-width: 100%;
    display: block;
}
```

二.先輸入`display: grid;`共同參數。
```css
.twmc-bg
{
    display: grid;
    grid-column-gap: 0px;
    grid-row-gap: 0px;
}
```

三.下面2種語法是相同的結果，依不同情況使用，*加入到二.程式碼內*。
```css
/*語法一*/
.twmc-bg
{
   grid-template-columns: auto auto;
}

.item3
{
   grid-area: 2 / 1 / span 1 / span 2; 
}
```
```css
/*語法二*/
.item3
{
  grid-area: 2 / 1 / 4 / 3;  
}

.item1
{
  grid-area: 1 / 1 / 3 / 2;  
}

.item2
{
  grid-area: 1 / 2 / 3 / 3;  
}
```
![gridsample](https://github.com/serialhon/re01/assets/8500234/7f1f5384-e4c0-4314-b3e8-267ad6d3c4a1)
