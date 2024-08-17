### *HTML元素*

##### 页头区域

页头区域包括在 head 元素中，以 <head>标记开始，以</head>>标记结束。页头区域应至少包括一个 title 元素和一个 meta 元素。

##### title 元素

页头区域第一个标记是title元素，包含要在浏览器窗口标题栏显示的文本。<title>和</title>之间的文本是网页的标题。

##### meta元素

meta元素描述网页特征，比如字符编码。字符编码是指字母、数字和符号在文件中的内部表示方式。有很多种字符编码，网页一般使用 utf-8 ，它是 Unicode 的一种形式。meta标记独立使用，而不是使用一对起始和结束标记。我们说它是一种独立或“自包容”标记，在HTML5中称为“void元素”。meta标记使用charset属性指定字符编码，如下例所示。

<meta charset=utf-8>
</meta>
### *第一个网页*

The First Web Page.html

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My First Web Page</title>
        <meta charset="UTF-8">
    </head>
    <body>
        Hello,World!
    </body>
</html>
```

### *标题元素*

标题（heading）元素从 h1 到 h6 共六级。标题元素包含的文本被浏览器渲染为“块”（block）。标题上下自动添加空白（white space）。<h1>字号最大，<h6>最小。

heading.html

```html
<!DOCTYPE html>
<html>
    <head>
        <title>
            Heading Example
        </title>
        <meta charset="UTF-8">
    </head>
    <body>
        <h1>Heading Level 1</h1>
        <h2>Heading Level 2</h2>
        <h3>Heading Level 3</h3>
        <h4>Heading Level 4</h4>
        <h5>Heading Level 5</h5>
        <h6>Heading Level 6</h6>
    </body>
</html>
```

### *段落元素*

段落元素组织句子或文本。<p>和</p>之间的文本显示成段落，上下留空。

paragraph.html

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Paragraph Example</title>
        <meta charset="UTF-8">
    </head>
    <body>
        <h1>Heading Level 1</h1>
        <p>
            This is a sample paragraph.Heading tags can help to make your pages more
            accessible and usable.It is good coding practice to use heading to use heading tags to outline
        </p>
        <h2>Heading Level 2</h2>
        <h3>Heading Level 3</h3>
        <h4>Heading Level 4</h4>
        <h5>Heading Level 5</h5>
        <h6>Heading Level 6</h6>
    </body>
</html>
```

### *对齐*

测试网页时，会注意到标题和文本都是从左边开始显示的，这称为左对齐，是网页的默认对齐方式。在以前版本的HTML中，想要让段落或标题居中或右对齐可以使用align属性

### *换行元素*

换行元素  <br>造成浏览器跳到下一行显示下一个元素或文本。

linebreak.html

```html
<body>
    <h1>Heading Level 1</h1>
    <p>This is a sample paragraph.<br>Heading tags can help to make your pages more
    accesible and usable.It is good coding practice to use heading tags to outline
    the structure of your web page content.
    </p>
    <h2>Heading Level 2</h2>
    <h3>Heading Level 3</h3>
    <h4>Heading Level 4</h4>
    <h5>Heading Level 5</h5>
    <h6>Heading Level 6</h6>
</body>
```

### *块引用元素*

除了用段落和标题组织文本，有时还需要为网页添加引文。<blockquote>标记以特殊方式显示引文块-------左右两边都缩进。

blockquote.html

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Blockquote Example</title>
        <meta charset="UTF-8">
    </head>
    <body>
        <h1>The Power of the Web</h1>
        <p>
            According to Tim Berners-Lee,the inventor of the World Wide Web,at
            http://www.w3.org/WAI/:
        </p>
        <blockquote>
            The power of the Web is in its universality.Access by everyone
            regardless of disability is an essential aspect.
        </blockquote>
    </body>
</html>
```

| 标签     | 描述                                                         |
| :------- | :----------------------------------------------------------- |
| <em>     | 呈现为被强调的文本。                                         |
| <strong> | 定义重要的文本。                                             |
| <dfn>    | 定义一个定义项目。                                           |
| <code>   | 定义计算机代码文本。                                         |
| <samp>   | 定义样本文本。                                               |
| <kbd>    | 定义键盘文本。它表示文本是从键盘上键入的。它经常用在与计算机相关的文档或手册中。 |
| <var>    | 定义变量。您可以将此标签与 <pre> 及 <code> 标签配合使用。    |

| <cite> | 定义引用。可使用该标签对参考文献的引用进行定义，比如书籍或杂志的标题。 |
| ------ | ------------------------------------------------------------ |
|        |                                                              |

### *有序列表*

有序列表以<ol>标记开始，</ol>标记结束；每个列表项以<li>标记开始，</li>标记结束。

##### type属性、start属性 和 reversed属性

| 值   | 描述                                |
| :--- | :---------------------------------- |
| 1    | 默认。十进制数字（1、 2、 3、 4）   |
| a    | 字母有序列表，小写（a、 b、 c、 d） |
| A    | 字母有序列表，大写（A、 B、 C、 D） |
| i    | 罗马数字，小写（i、 ii、 iii、 iv） |
| I    | 罗马数字，大写（I、 II、 III、 IV） |

ol.html

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Heading and List</title>
        <meta charset="UTF-8">
    </head>
    <body>
        <h1>My Favorite Colors</h1>
        <ol>
            <li>Blue</li>
            <li>Teal</li>
            <li>Red</li>
        </ol>
    </body>
</html>
```

### *无序列表*

无序列表在列表的每个项目前都加上列表符号。

无序列表以 <ul> 标记开始，</ul> 标记结束。ul 元素是块显示元素，上下自动添加空白。每个列表项都以 <li> 标记开始，</li> 标记结束。

ul.html

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Heading and List</title>
        <meta charset="UTF-8">
    </head>
    <body>
        <h1>My Favorite Colors</h1>
        <ul>
            <li>Blue</li>
            <li>Teal</li>
            <li>Red</li>
        </ul>
    </body>
</html>
```

###### 可不可以改变无序列表的列表符号

HTML5已经弃用无序列表的type属性，因为它只有装饰性，无实际意义。但可以用 CSS 技术配置列表符号来显示图片和形状。

### *描述列表*

描述列表用于组织术语及其定义。术语单独显示，对它的描述根据需要可以无限长。术语独占一行并顶格显示，描述另起一行并缩进。

描述列表以 <dl> 标记开始，</dl>标记结束；每个要描述的术语以 <dt></dt> ;每项描述内容以 <dd> </dd> 标记。

description.html

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Description List</title>
        <meta charset="UTF-8">
    </head>
    <body>
        <h1>Sample Description List</h1>
        <dl>
            <dt>TCP</dt>
            <dd>
                Transmission Control Protocal is a method (protocal) used along<br>
                with the Internet Protocal (IP) to send data in the form of message units,<br>
                called packets,between computers over the Internet.
            </dd>
            <dt>IP</dt>
            <dd>
                Internet Protocal is the method or protocal by which data is sent<br>
                from one computer to another on the Internet.Each computer on the Internet
                is uniquely identified by an IP address.
            </dd>
            <dt>FTP</dt>
            <dd>
                File Transfer Protocal is a protocal used to exchange files between computers 
                on the Internet.
            </dd>
            <dt>HTTP</dt>
            <dd>
                Hypertext Transfer Protocal is the protocal used for exchanging text,graphic images,
                sound,video,and other multimedia files on the Web.
            </dd>
        </dl>
    </body>
</html>
```

### *特殊字符*

​	为了在网页文档中使用诸如引号、大于号（>）、小于号（<）和版权符（©）等特殊符号，需要使用特殊符号，或者称为实体符号。例如，要在网页中添加以下版权行：

###### © Copyright 2020  我的公司，保留所有权利。

可使用特殊字符 **&copy** ；显示版权符，代码如下：

###### &copy ;Copyright 2020 我的公司。保留所有权利。

​	另一个有用的特殊字符是 &nbsp；，它代表 不间断空格 。你也许已经注意到，不管多少空格，网页浏览器都只视为一个。要在文本中添加多个空格，可连续使用 &nbsp；。

| 显示结果 | 描述              | 实体名称          | 实体编号 |
| :------- | :---------------- | :---------------- | :------- |
|          | 空格              | &nbsp;            | &#160;   |
| <        | 小于号            | &lt;              | &#60;    |
| >        | 大于号            | &gt;              | &#62;    |
| &        | 和号              | &amp;             | &#38;    |
| "        | 引号              | &quot;            | &#34;    |
| '        | 撇号              | &apos; (IE不支持) | &#39;    |
| ￠       | 分（cent）        | &cent;            | &#162;   |
| £        | 镑（pound）       | &pound;           | &#163;   |
| ¥        | 元（yen）         | &yen;             | &#165;   |
| €        | 欧元（euro）      | &euro;            | &#8364;  |
| §        | 小节              | &sect;            | &#167;   |
| ©        | 版权（copyright） | &copy;            | &#169;   |
| ®        | 注册商标          | &reg;             | &#174;   |
| ™        | 商标              | &trade;           | &#8482;  |
| ×        | 乘号              | &times;           | &#215;   |
| ÷        | 除号              | &divide;          | &#247;   |

design.html

```html
<h1>Web Design Steps</h1>
<ul>
    <li>
        <strong>Determine the Internet Audience</strong>
        <br>The colors ,images, fonts, and layout should be tailed to the
        <em>preferences of your audience.</em> The type of sites content
        (reading level,amount of animation,etc.) should be appropriate for 
        your chosen audience.
    </li>    
</ul>
<p>
    <small>
        Copyright &copy; 2020 Your name.All Rights Reserved.
    </small>
</p>
```

### *结构元素*

这些新的 HTML5 header, nav, main 和 footer元素旨在和div以及其他元素配合使用，通过一种更有意义的方式阐述结构区域，从而对网页文档进行更好的结构化。如图展示了如何使用 header , nav , main , div 和 footer元素建立网页结构，这种图称为 **线框图**。

![img](https://i-blog.csdnimg.cn/blog_migrate/75c29c0811b06cd765679fe9ad513ef6.jpeg)

![img](https://i-blog.csdnimg.cn/blog_migrate/e3b3e92aaad8e830df8bbd6e138c7f31.png)

##### *div元素*

div 元素在网页中创建一个常规结构区域（称为“ division ”）。作为块显示元素，它上下会自动添加空白。 div 元素标记 <div></div> 。div 元素适合定义包含了其他块显示元素（标题、段落、无序列表 以及 其他 div 元素）的区域。本书以后会用层叠样式表（CSS）配置HTML元素的样式、颜色、字体以及布局。

##### *header元素*

HTML5 header元素的作用是包含网页文档或文档区域（比如section 和 aarticle）的标题。header元素标记 <header></header>。header 元素是块显示元素，通常包含一个或多个标题元素（ h1 到 h6 ）.

##### *nav元素*

HTML5 nav元素的作用是建立一个导航链接区域。nav 是块显示元素，标题 <nav></nav>

##### *main 元素*

HTML 5 main 元素的作用是包含网页文档的主要内容。每个网页只应有一个 main 元素。main是块显示元素，标记 <main></main> 。

##### footer 元素

HTML 5  footer 元素的作用是为网页或网页区域创建页脚。footer 是块显示元素，标记 <footer></footer> 。



练习使用结构元素

structure.html

```html
<header>
    <h1>Trillium Media Design</h1>
</header>
<nav>
    <b>Home &nbsp; Services &nbsp; Contact</b>
</nav>
<main>
    <h2>New Media and Web Design</h2>
    <p>
        Trillium Media Design will bring your company&rsquo;s Web
        presence to the next level.We offer a comprehensive range of
        services.
    </p>
    <h2>Meeting Your Business Needs</h2>
    <p>Our expert designers are creative and eager to work with you.</p>
</main>
<footer>
    <small>
        <i>Copyright &copy; 2020 Your Name Here</i>
    </small>
</footer>
```

casita.html

```html
<!DOCTYPE html>
<title>Casita Sedona Bed &amp; Breakfast</title>
<header>
    <h1>
        Casita Sedona Bed &amp; Breakfast
    </h1>
</header>
<nav>
    <b>
        Home &nbsp;
        Rooms &nbsp;
        Events &nbsp;
        Contact
    </b>
</nav>
<main>
    <h2>Stay in the Heart of Sedona</h2>
    <p>
        At Casita Sedona Bed &amp; Breakfast you&rsquo;ll be close to
        art galleries ,shops ,restaurants ,hiking trails ,and tours .
        Ride the free trolley shops and galleries .
    </p>
</main>
<div>
    <strong>Casita Sedona Bed &amp; Breakfast</strong><br>
    612 Tortuga Lane<br>
    Sedona, AZ 86336<br>
    928-555-5555<br>
</div>
<footer>
    <small><i>Copyright &copy; 2020 Your Name Here</i></small>
</footer>
```

##### *section 元素*

包含文档的 “区域” ，比如章节或主题。 setion 元素是块显示元素，以 <section></section>标记，可包含 header, footer, section, article, aside, figure, div 和其他内容配置元素。

##### *article 元素*

包含一个独立条目，比如博客文章、评论或电子杂志。article元素是块显示元素，以<article></article>为标记，可包含 header,footer,section,aside,figure,div 和其他内容配置元素。

##### *aside 元素*

aside元素代表旁注或其他补充内容。aside是块显示元素，以<aside></aside>标记，可包含 header，footer，section，aside，figure，div 和 其他内容配置元素。

##### *time 元素*

代表日期或时间。虽然不是结构元素，但之所以把它列出来，是因为它特别适合标注内容（网页或博客文章）的创建日期。time是内联元素，以<time></time>>标记。使用可选的 datetime 属性，可通过一种机器能识别的格式来显示日历日期和 / 或时间。日期用YYYY-MM-DD ，时间用 HH：MM（24小时制）。

blog.html

```html
<!DOCTYPE html>
<html lang="en">
    <title>Lighthouse Bistro Blog</title>
    <header>
        <h1>Lighthouse Bistro Blog</h1>
        <nav>
            <b>Home &nbsp; Menu &nbsp; Blog &nbsp; Contact &nbsp; </b>
        </nav>
    </header>
    <main>
        <aside>
            <p>
                <i>Watch for the March Madness Wrap next month !</i>
            </p>
        </aside>
        <section>
            <h2>Bistro Blog</h2>
            <article>
                <header><h3>Valentine Wrap</h3></header>
                <time datetime="2024-08-17">August 17,2024</time>
            </article>
            <article>
                <header><h3>New Coffee of the Day Promotion</h3></header>
                <time datetime="2024-08-15">August 15,2024</time>
                <p>
                    Enjoy the best coffee on the coast in the comfort of your
                    home. We will feature a different flavor of our gourmet,
                    locally roasted coffee each day with free bistro tastings and 
                    a discount on one-pound bags.
                </p>
            </article>
        </section>
    </main>
</html>
```

### *超链接*

##### a 元素

a 元素作用是定义超链接，它指向想要显示的另一个网页或文件。锚元素以 <a></a>。两个标记之间是可以点击的链接文本或图片。

##### href 属性

用 href 属性配置链接引用，即要访问（链接到）的文本的名称和位置。锚标记的代码案例如下：

<a href="http://webdevbasics.net">Basics of Web Design Textbook Companion</a>

```html
<a href="http://webdevbasics.net">Basics of Web Design Textbook Companion</a>
```

anchor.html

```html
<!DOCTYPE html>
<html lang="en">
    <header>
        <title>Anchor Example</title>
        <meta charset="UTF-8">
    </header>
    <body>
        <a href="http://webdevbasics.net">Basics of Web Design Textbook Companion</a>
    </body>
</html>
```

##### *绝对链接*

绝对链接指定资源在Web上的绝对位置。用绝对链接来链接其他网站上的资源。这种链接的href值包含协议名称 http:// 和域名。下面是指向本书网站的绝对链接：

<a href ="http://webdevfoundations.net">Web Development &amp; Design Foundation</a>

```html
<a href ="http://webdevfoundations.net">Web Development &amp; Design Foundation</a>
```

##### *相对链接*

链接到自己网站内部的网页时可以使用相对链接。这种链接的 href 值不以 http：// 开头，也不含域名，只包含想要显示的网页的文件名（或者文件夹和文件名的组合）。链接位置相对于当前显示的网页。

contact.html

<a href ="contact.html">Contact Us</a>

```html
<a href ="contact.html">Contact Us</a>
```

##### *站点地图*

站点地图描述网站结构。网站的每个网页都显示成站点地图中的一个框。

##### *target属性*

可以在锚标记中使用target属性配置 target = “ ___blank ” 在新浏览器窗口或新标签页中打开网页。例如打开Google主页：

<a href="http://google.com"  target="__blank">Search Google</a>

```html
<a href="http://google.com"  target="__blank">Search Google</a>
```

