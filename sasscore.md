# zzsasscore

zzsasscore参考了\[bourbon\]\([http://bourbon.io/](http://bourbon.io/)\)等sass库，结合团队项目所需，汇总而成，会陆续完善。

\#\#如何使用？

* zzsasscore主要提供rem、一些基础的样式和\`@mixin\`，\`%\`等方便调用。

\#\#\#调用

rem样式：

```
@import "~/zzsasscore/flexible";
```

reset样式：

```
@import "~/zzsasscore/reset";
```

另外，只提供功能调用，不产生任何样式：

```
@import "~/zzsasscore/mixin";
```

\#\#内容：

* zzsasscore中包含rem, setting，css3，mixin，reset，animate，font-face，btn等。

* sassCore包括三个文件夹（functions，mixins, variables\)、两个集合文件（flexible，reset）。

\#\#\#variables文件

\#\#\#\#color

团队常用的颜色变量。

\#\#\#\#zindex

常用弹窗、蒙层、loading、文档流等层级关系。

\#\#\#\#mixins

负责功能方面的文件。

\#\#\#\#center

常用的居中布局

\#\#\#\#size

常用字体大小

\#\#\#\#ellipsis

块元素省略

\#\#\#\#triangle

三角形

\#\#\#\#animate-base

动画基本属性

\#\#\#\#animate-fade

进入进出动画

\#\#\#\#animate-rotate

旋转动画

\#\#\#flexible

初始化rem布局

\#\#\#reset

一些基础样式



