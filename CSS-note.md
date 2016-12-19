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
