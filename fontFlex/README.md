## JQuery 自动改变文字大小插件fontFlex

> fontFlex是一个轻量级jQuery插件,根据屏幕/浏览器宽度动态更改字体大小。多用于响应或自适应的CSS布局。

- ### 使用方法

```
<script src="jQuery.min.js"></script>  
<script src="jQuery.fontFlex.js"></script>
```

**定义一个默认CSS字体通过设置字体大小:1em和line-height:150%在body或预期的元素。将字体大小设置可选的，但是强烈建议在javascript被禁用。最后调用插件元素。**

```
$(function() {
  // All elements
  $('body').fontFlex(14, 20, 70);
  // H1 only
  $('h1').fontFlex(24, 36, 70); 
}
```

