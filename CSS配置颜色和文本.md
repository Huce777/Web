### *层叠样式表概述*

**样式表**（ style  sheet ）的作用是将排版样式和间距指令应用于出版物。CSS 为 web 开发者提供了这一功能（ 以及其他更多功能 ），允许 web 开发人员将排版样式 （ 字体和字号等 ）、颜色和页面布局指令应用于网页。

#### *配置层叠样式表*

有4种不同的方法将 CSS 技术集成到网站：内联、嵌入、外部 和 导入。

●  **内联样式** ：内联样式是指将代码直接写入网页的主体区域，作为HTML标记的属性。只适合提供了样式属性的特定元素。

●  **嵌入样式** ：嵌入样式在网页的页头区域 （ <header></header> 之间 ）进行定义。应用于整个网页文档。

●  **外部样式** ：外部样式用单独文件编码。网页在页面区域使用 link 元素链接到文件。

●  **导入样式** ：导入样式与外部样式很相似，同样是将包含了样式定义的文本文件与网页文档链接。但是，是用 @import 指令将外部样式导入嵌入式样式，或导入另一个外部样式表。

#### *CSS 选择符和声明*

CSS 规则集（rule-set）由选择器和声明块组成：

![CSS 选择器](https://www.w3school.com.cn/i/css/selector.gif)

选择器指向您需要设置样式的 HTML 元素。

声明块包含一条或多条用分号分隔的声明。

每条声明都包含一个 CSS 属性名称和一个值，以冒号分隔。

多条 CSS 声明用分号分隔，声明块用花括号括起来。

#### *background-color 属性*

配置元素背景颜色的 CSS 属性是 background-color 。以下样式规则将网页背景色配置成黄色：

```css
body { background-color : yellow }
```

注意，声明要包含在一对大括号中，冒号（ : ）分隔一个声明中的属性和值。

#### *color 属性*

用于配置元素的文本颜色的 CSS 属性是 color 。以下 CSS 样式规则将网页上的文本的颜色配置成蓝色：

```css
body { color : blue }
```

#### *配置背景色和文本色*

一个选择符要配置多个属性，请用分号（ ; ）。以下 CSS 样式规则将网页配置成紫底白字；

```css
body { color:white ; background-color:orchid; }
```

声明中的空格可有可无。结束分号（ ; ）同样可选，但以后需要添加其他样式规则时就有用了。

##### 背景属性(Background)

| 属性                    | 描述                                 |
| :---------------------- | :----------------------------------- |
| `background`            | 在一个声明中定义各种背景属性。       |
| `background-attachment` | 指定背景图像是在视口中固定还是滚动。 |
| `background-clip `      | 指定背景的绘制区域。                 |
| `background-color`      | 定义元素的背景色。                   |
| `background-image`      | 定义元素的背景图像。                 |
| `background-origin `    | 指定背景图像的定位区域。             |
| `background-position`   | 定义背景图像的原点。                 |
| `background-repeat`     | 指定是否/如何平铺背景图像。          |
| `background-size `      | 指定背景图像的大小。                 |

##### 边框属性(Border)

| 属性                          | 描述                                         |
| :---------------------------- | :------------------------------------------- |
| `border`                      | 设置元素边框所有四个侧面的宽度，样式和颜色。 |
| `border-bottom`               | 设置元素底部边框的宽度，样式和颜色。         |
| `border-bottom-color`         | 设置元素底部边框的颜色。                     |
| `border-bottom-left-radius `  | 定义元素的左下边界角的形状。                 |
| `border-bottom-right-radius ` | 定义元素右下边界的形状。                     |
| `border-bottom-style`         | 设置元素底部边框的样式。                     |
| `border-bottom-width`         | 设置元素底部边框的宽度。                     |
| `border-color`                | 设置元素所有四个侧面的边框颜色。             |
| `border-image `               | 指定如何使用图像代替边框样式。               |
| `border-image-outset `        | 指定边框图像区域超出边框超出范围的数量。     |
| `border-image-repeat `        | 指定图像边框应重复，四舍五入还是拉伸。       |
| `border-image-slice `         | 指定图像边框的向内偏移。                     |
| `border-image-source `        | 指定要用作边框的图像的位置。                 |
| `border-image-width `         | 指定图像边框的宽度。                         |
| `border-left`                 | 设置元素左边框的宽度，样式和颜色。           |
| `border-left-color`           | 设置元素的左边框的颜色。                     |
| `border-left-style`           | 设置元素左边框的样式。                       |
| `border-left-width`           | 设置元素左边框的宽度。                       |
| `border-radius `              | 定义元素边界角的形状。                       |
| `border-right`                | 设置元素右边框的宽度，样式和颜色。           |
| `border-right-color`          | 设置元素右边框的颜色。                       |
| `border-right-style`          | 设置元素右边框的样式。                       |
| `border-right-width`          | 设置元素右边框的宽度。                       |
| `border-style`                | 在元素的所有四个面上设置边框的样式。         |
| `border-top`                  | 设置元素顶部边框的宽度，样式和颜色。         |
| `border-top-color`            | 设置元素顶部边框的颜色。                     |
| `border-top-left-radius `     | 定义元素左上角的形状。                       |
| `border-top-right-radius `    | 定义元素的右上边界角的形状。                 |
| `border-top-style`            | 设置元素顶部边框的样式。                     |
| `border-top-width`            | 设置元素顶部边框的宽度。                     |
| `border-width`                | 设置元素所有四个侧面的边框宽度。             |

##### 颜色属性(Color)

| 属性       | 描述                 |
| :--------- | :------------------- |
| `color`    | 指定元素文本的颜色。 |
| `opacity ` | 指定元素的透明度。   |

##### 尺寸属性(Size)

| 属性         | 描述                 |
| :----------- | :------------------- |
| `height`     | 指定元素的高度。     |
| `max-height` | 指定元素的最大高度。 |
| `max-width`  | 指定元素的最大宽度。 |
| `min-height` | 指定元素的最小高度。 |
| `min-width`  | 指定元素的最小宽度。 |
| `width`      | 指定元素的宽度。     |

##### 内容属性(Content)

| 属性      | 描述                 |
| :-------- | :------------------- |
| `content` | 插入生成的内容。     |
| `quotes`  | 指定嵌入引号的引号。 |

##### 字体属性(Fonts)

| 属性                | 描述                                         |
| :------------------ | :------------------------------------------- |
| `font`              | 在一个声明中定义各种字体属性。               |
| `font-family`       | 定义元素的字体列表。                         |
| `font-size`         | 定义文本的字体大小。                         |
| `font-size-adjust ` | 发生字体回退时，保留文本的可读性。           |
| `font-stretch `     | 从字体中选择一个普通的，压缩的或扩展的字体。 |
| `font-style`        | 定义文本的字体样式。                         |
| `font-variant`      | 指定字体变体。                               |
| `font-weight`       | 指定文本的字体粗细。                         |

##### 视觉格式属性

| 属性          | 描述                                             |
| :------------ | :----------------------------------------------- |
| `display`     | 指定元素在屏幕上的显示方式。                     |
| `position`    | 指定如何定位元素。                               |
| `top`         | 指定所定位元素的上边缘的位置。                   |
| `right`       | 指定所定位元素的右边缘的位置。                   |
| `bottom`      | 指定所定位元素底边的位置。                       |
| `left`        | 指定定位元素左边缘的位置。                       |
| `float`       | 指定一个框是否应该浮动。                         |
| `clear`       | 指定相对于浮动元素的元素位置。                   |
| `z-index`     | 指定定位元素的分层或堆叠顺序。                   |
| `overflow`    | 指定对溢出元素框的内容的处理。                   |
| `overflow-x ` | 指定当内容超出元素内容区域的宽度时如何管理内容。 |
| `overflow-y ` | 指定当内容超出元素内容区域的高度时如何管理内容。 |
| `resize `     | 指定元素是否可由用户调整大小。                   |
| `clip`        | 定义裁剪区域。                                   |
| `visibility`  | 指定一个元素是否可见。                           |
| `cursor`      | 指定游标的类型。                                 |
| `box-shadow ` | 将一个或多个阴影应用于元素的框。                 |
| `box-sizing ` | 更改默认的CSS框模型。                            |

#### *十六进制颜色值*

十六进制基本数位包括 0、1、2、3、4、5、6、7、8、9、A、B、C、D、E、F。用十六进制值表示 RGB 颜色需使用三对十六进制数位。每一对值的范围是 00~FF （ 十进制0~255 ）

这三对值分别代表红、绿、蓝的颜色强度。采用这种表示法，红色将表示为 #FF0000 ，蓝色 #0000FF 。# 符号 表明该值是十六进制的。可在十六进制颜色值中使用大写或小写字母

---- #FF0000 和 #ff0000 都表示红色。

![CMYK色值表与RGB色值表对照图 十六进制颜色对应的CMYK颜色表 - 系统之家](https://img-blog.csdn.net/2018091621203411?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0hCX1Byb2dyYW1tZXI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![常用十六进制颜色对照表_十六进制颜色表-CSDN博客](https://img-blog.csdn.net/20180622161605328?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2hzbDQxNjYwNDA5Mw==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

#### *CSS 颜色语法*

CSS 语法允许通过多种方式配置颜色：

●  颜色名称

●  十六进制颜色值

●  十六进制短颜色值

●  十进制颜色值（ RGB 三元值 ）

●  HSL（ Hue, Saturation, and Lightness ，色调/饱和度/亮度 ）颜色值

```css
/* 命名颜色 */
rebeccapurple
aliceblue

/* RGB 十六进制 */
#f09
#ff0099

/* RGB（红、绿、蓝） */
rgb(255 0 153)
rgb(255 0 153 / 80%)

/* HSL（色相、饱和度、明度） */
hsl(150 30% 60%)
hsl(150 30% 60% / 0.8)

/* HWB（色相、白度、黑度）*/
hwb(12 50% 0%)
hwb(194 0% 0% / 0.5)

/* LAB（亮度、A 轴、B 轴） */
lab(50% 40 59.5)
lab(50% 40 59.5 / 0.5)

/* LCH（亮度、色度、色相） */
lch(52.2% 72.2 50)
lch(52.2% 72.2 50 / 0.5)

/* Oklab（亮度、A 轴、B 轴） */
oklab(59% 0.1 0.1)
oklab(59% 0.1 0.1 / 0.5)

/* Oklch（亮度、色度、色相） */
oklch(60% 0.15 50)
oklch(60% 0.15 50 / 0.5)

```

一个 `<color>` 值可以以如下方式定义：

- 通过关键字：[``](https://developer.mozilla.org/zh-CN/docs/Web/CSS/named-color)（例如 `blue` 和 `pink`）、[``](https://developer.mozilla.org/zh-CN/docs/Web/CSS/system-color) 和 [`currentcolor`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value#currentcolor_关键字).

- 通过十六进制标记：[``](https://developer.mozilla.org/zh-CN/docs/Web/CSS/hex-color)（例如 `#ff0000`）。

- 通过使用函数标记的颜色空间的参数：

  - [sRGB](https://zh.wikipedia.org/wiki/SRGB色彩空间) 颜色空间：[`hsl()`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value/hsl)、[`hwb()`](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/hwb)、[`rgb()`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value/rgb)；
  - [CIELAB](https://zh.wikipedia.org/wiki/CIELAB色彩空间) 颜色空间：[`lab()`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value/lab)、[`lch()`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value/lch)；
  - [Oklab](https://bottosson.github.io/posts/oklab/) 颜色空间：[`oklab()`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value/oklab)、[`oklch()`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value/oklch)；
  - 其他颜色空间：[`color()`](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/color)。

- 通过混合两个颜色：[`color-mix()`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value/color-mix)。

  ### [currentcolor 关键字](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value#currentcolor_关键字)

  `currentcolor` 关键字表示元素的 [`color`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color) 属性的值。这可以在默认情况下不接收 `color` 值的属性上使用 `color` 值。

  如果 `currentcolor` 用于 `color` 属性的值，那么会给元素继承 `color` 属性的值。

```html
<div style="color: blue; border: 1px dashed currentcolor;">
  这个文本的颜色是蓝色。
  <div style="background: currentcolor; height:9px;"></div>
  这个块的边框也是蓝色。
</div>

```

### *用 style 属性配置内联 CSS*

#### *style 属性*

内联样式通过 HTML 标记的 style 属性实现。属性值是样式规则声明。记住，每个声明都由属性和值构成。属性和值以冒号分隔。例子如下：

```css
<h1 style="color:#cc0000">该标题显示红色</h1>
```

属性不止一个，就用分号（ ; ）分隔。以下代码将标题文本设为红色，背景设为灰色：

```css
<h1 style="color:#cc0000;background-color:#cccccc">该标题显示显示成灰底红色</h>
```

inline.html

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <h1 style="color:#cc0000;">该标题显示红色</h1>
        <h1 style="color:#cc0000;background-color:#cccccc;">该标题显示显示成灰底红字</h1>
        <meta charset="UTF-8">
    </head>
    <body style="background-color: #F5F5F5;color:#008080;">
        <h1 style="background-color: #008080;color:#F5F5F5;">Inline</h1>
        <p>This paragraph inherits the styles applied to the body tag.</p>
    </body>
    <footer>
        <p style="color:#333333;">This paragraph overrides the text color style applied
            to the body tag.
        </p>
    </footer>
</html>
```

###### *内联样式不常用，效率不高，会为网页文档带来额外的代码，而且不便维护。但内联样式在某些情况下好用。例如，通过内容管理系统或博客发表文章时，可能需要对站点级的默认样式进行少许调整，从而更好地表达自己的想法。*



#### `*CSS 不起作用怎么办？*`

`CSS 编码要细心。一些常见错误会造成浏览器无法向网页正确应用 CSS 。参考以下几点检查代码，使 CSS 能正常工作。`

1. `冒号（ : ）要和分号（ ; ）用在正确的地方，它们很容易混淆。冒号分隔属性及其值；而每一对  “ 属性：值 ” 用分号分隔。`
2.  `确定属性及其值之间使用的是 冒号（ : ）而不是 等号（ = ）。`
3.  `确认每个选择符的样式规则都在一对 { } 之间`
4.  `检查选择符语法、它们的属性以及属性的值都正常使用。`
5.  `如果部分 CSS 能正常工作，部分不能，就从头检查 CSS ，找到没有正确应用的第一个值。一般是没有正常工作的规则上方的那个规则则存在错误。`
6.  `用程序检查 CSS 代码。W3C 的 CSS  validator（ http://jigsaw.w3.org/css-validator ）可以帮助你找到语法错误。稍后将描述如何用该工具校验CSS。`

#### *CSS字型*

在CSS中，有两种类型的字体系列名称：

- **通用字体系列** - 拥有相似外观的字体系统组合（如 "Serif" 或 "Monospace"）
- **特定字体系列** - 一个特定的字体系列（如 "Times" 或 "Courier"）

| Generic family | 字体系列                   | 说明                                        |
| :------------- | :------------------------- | :------------------------------------------ |
| Serif          | Times New Roman Georgia    | Serif字体中字符在行的末端拥有额外的装饰     |
| Sans-serif     | Arial Verdana              | "Sans"是指无 - 这些字体在末端没有额外的装饰 |
| Monospace      | Courier New Lucida Console | 所有的等宽字符具有相同的宽度                |
