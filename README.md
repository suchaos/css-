# css-
一些常用的css代码
=======
让浮动元素的父元素“自清除”, 添加class = "clearfix"
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
