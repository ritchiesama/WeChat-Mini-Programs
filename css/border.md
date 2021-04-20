
```html
一.边框：border 设置对象边框的特性。

1.语法：border：length   style  color 

2.style：none ，hidden，dotted，dashed，solid，double，groove，ridge，inset，outset。

二.相关属性。

1.border-width：设置边框宽度：常用取值：medium：默认值，相当于3px。thin：1px。thick：5px。不可以为负值。

2.border-color:设置边框颜色。

3.border-top:设置顶部边框。border-top-width,border-top-style,border-top-color 分别设置 宽度，样式以及颜色

4.border-right：设置右边框。

5.border-bottom：设置底边框。 

6.border-left：设置左边框。

7.border-radius：设置对象使用圆角边框。取值为数字或者百分比。

8.当然也可以给4个角单独的设置：

左上角：border-top-left-radius，右上角：border-top-right-radius，左下角：border-bottom-left-radius，右下角：border-bottom-right-radius

9.box-shadow:设置对象阴影。

第一个值：设置水平方向阴影偏移量。

第二个值：设置垂直方向阴影偏移量。

第三个值：设置对象的阴影模糊值。不允许为负值

第四个值：设置对象的阴影外延值，不允许为负值

第五个值：color。

第六个值：inset，阴影在左上位置，如下图：box-shadow:6rpx 6rpx 6rpx 6rpx rebeccapurple inset

10.border-image：对象的边框样式使用图片来填充。

1>border-image-source:设置图片的来源。使用绝对或者相对地址或者渐变色来确定图片。

2>border-image-slice :设置边框背景图的分隔方式。取值：数值／百分比 fill.该属性指定从上右下左来分割图片，将图像分成4个角，4条边以及中间区域。中间区域始终是透明的，除非使用关键字fill。

3>border-image-width:设置边框背景的宽度。用于指定使用多厚的边框来承载呗裁剪后的图像。

4>border-image-outset：设置对象的边框背景图的扩展，意思就是说假如设置了10rpx，那么图像就会在原来基础上外延10rpx在显示。

5>border-image-repeat：设置对象的边框图片的平铺方式。

stretch:拉伸。

repeat：平铺，碰到边界的时候截断。

round：根据边框的尺寸动态调整图片的大小，使得刚好可以铺满整个边框。

space：根据边框的尺寸动态调整图片的之间的间距，使得刚好铺满整个边框。

三.使用示例

可以生成箭头。


```
