# html 語法記錄
## 網頁開頭：
一. 在 vscode 中，輸入 'htm' 會自動提示選項，選擇 'html:5' 後按下 TAB鍵。  或自行輸入如下 共9行

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

二.在標千'</head>'前一行輸入 'lin'會自動提示選項，選擇 'link' 後按下 TAB鍵。  常用的.CSS 引入如下

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link rel="stylesheet" href="css/styles.css">
```

三.依續畫分網頭、網身、及網腳。
1.網頭:在標千'<body>'後一行輸入 'div.web-head' 後按下 Enter鍵。  範例  

```html
    <div class="web-head">
```

2.網身:在網頭標千'</div>'後一行輸入 'section.section-bg' 後按下 Enter鍵。  範例
```html
    <section class="food-menu section-bg">
```

3.網腳:在網身最後標千 後一行輸入 'div.web-footer' 後按下 Enter鍵。  範例
```html
    <div class="web-foot"></div>
