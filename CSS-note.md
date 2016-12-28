# CSS note

2016-12-19
```
一般而言，所有的样式会根据下面的规则层叠于一个新的虚拟样式表中，其中数字 4 拥有最高的优先权。
1. 浏览器缺省设置
2. 外部样式表
3. 内部样式表（位于 <head> 标签内部）
4. 内联样式（在 HTML 元素内部）

```
![](http://www.w3school.com.cn/i/ct_css_selector.gif)
```
请注意，当使用 RGB 百分比时，即使当值为 0 时也要写百分比符号。但是在其他的情况下就不需要这么做了。比如说，当尺寸为 0 像素时，0 之后不需要使用 px 单位，因为 0 就是 0，无论单位是什么。

派生选择器
类名的第一个字符不能使用数字！它无法在 Mozilla 或 Firefox 中起作用。

favicon图标：
<link rel="icon" href="favicon.ico" type="image/x-icon" /> 
```

2016-12-28
```
div布局时遇到margin-top嵌套问题，查到：块级元素的垂直相邻外边距会合并。
解决办法：
1、在父层div加上：overflow:hidden； 
2、把margin-top外边距改成padding-top内边距 ； 
3、父元素产生边距重叠的边有不为 0 的 padding 或宽度不为 0 且 style 不为 none 的 border。 父层div加： padding-top: 1px; 
4、让父元素生成一个 block formating context，以下属性可以实现 * float: left/right * position: absolute * display: inline-block/table-cell(或其他 table 类型) * overflow: hidden/auto 父层div加：position: absolute;
```
