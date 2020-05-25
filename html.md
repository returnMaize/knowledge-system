### 定义
- 是web世界的一砖一瓦 它定义了网页内容的含义和结构
- html不是一门编程语言 而是一种用来告诉浏览器如何组织页面的标记语言

### 组成
- 开始标签
- 开始标签中可包含属性
- 内容
- 结束标签
- 以上四者构成一个html元素
```
<p class="text">我是一段内容</p>
```

### 规则
- html标签不区分大小写
- html中不包含 ASCII 空格（以及 " ' ` = < > ）的简单属性值可以不使用引号 但建议都用引号 方便阅读
- html元素内容中的空格 （无论使用多少空格 当渲染这个元素时 这些空格都会减少成一个空格）
- html实体 （html中的特殊字符 ```&lt;``` = <）

### html元素
- 空元素 （没有结束标签 如：img）
- 块级元素
- 内联元素

### html文档详解
- ```<!DOCTYPE html>```— 文档类型。混沌初分，HTML 尚在襁褓（大约是 1991/92 年），DOCTYPE 用来链接一些 HTML 编写守则，有点像自动校正等。然而现在已经没有人关心这些，只是因为历史原因必须将它们保留，但没有实际作用。
- ```<html></html>``` 包含页面整个内容 也被称为根元素
- ```<head></head>``` 放一些用户看不到的东西 如搜索引擎关键字 页面描述 链接样式表...
- ```<meta charset="utf-8">```包含页面中的一些元数据 这个元素设置文档使用utf-8字符集编码
- ```<title></title>``` 页面的标题 
- ```<body></body>``` 放一些用户可以看到的东西 如文本 图片 视频...

### html属性
语法：属性名=引号 + 属性值 + 引号（引号可以是单引号也可以是双引号 风格问题 个人喜欢双引号）
- 布尔属性 没有值的属性 他们只有和属性名相同的值 （例如：disabled）

### meta元素
元数据就是用来描述数据的数据
```
<meta charset="utf-8">
```
指定文档字符编码——在这个文档中运行被使用到的字符集
- meta元素包含name 和 content
- ```<meta name="author" content="hjx">``` 一些内容管理系统能够自动获取页面作者信息
- ```<meta name="description" content="xxx">``` seo
- ```<meta property="og:image" content="http://xxx.com/img.jpg>```
- ```<meta property="og:description" content="xxxx">```
- ```<meta property="og:title" content="Mozilla Developer Network">```

### link元素
- 自定义图标
- 加载css

### 语义化标签

### 多媒体与嵌入

#### img元素

#### video元素

容器格式
- MP3
- MP4
- WebM 所有现在浏览器都支持的视频容器格式

MP3和MP4容器格式被广泛支持 但是需要高额的专利费 MP3容器格式2017年专利解除 MP4在2027年解除



