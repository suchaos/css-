# 一些常用的css代码

### 1. 让浮动元素的父元素“自清除”, 添加class = "clearfix"
```css
/* html5boilerplate.com Clearfix
--------------------------------- */
.clearfix:before,
.clearfix:after {
  content: " ";
  display: table;
}

.clearfix:after {
  clear: both;
}
```
### 2. 防止图片等溢出
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
```css
img, embed, object, video {
  max-width: 100%
}
```
### 3. 点按目标大小
```css
nav a, button {
  min-width: 48px;
  min-height: 48px;
}
```
