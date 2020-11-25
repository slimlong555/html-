# HTML的入门博客
# 目录
1. HTML是谁发明的？
2. HTML起手应该写什么？
3. 常用的表示章节的标签有哪些？分别是什么意思。
4. 全局属性？
5. 常用的表示内容的标签有哪些？分别是什么意思。
---
## 1.HTML的发明者：HTML是由Web的发明者 Tim Berners-Lee和同事 Daniel W. Connolly于1990年创立的一种标记语言
---
## 2.HTML的起手式：!+tab
~~~ html
<!DOCTYPE html>   文档类型
<html lang="zh-CN">
<head>
    <meta charset="UTF-8"> 文件的字符编号，一般是utf-8
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  禁止缩放，兼容个手
    <title>我的网页</title>
</head>   head中一般写看不见的东西
<body>
    
</body>
</html>
~~~
---
## 3. 常用的表示章节的标签有哪些？分别是什么意思。
* **h1**至**h6** 不同层级的标题
* **section** 文章的章节
* **article** 文章
* **p** 段落
* **header** 页面的头部
* **footer** 页面的底部 &copy;表示版权标志
* **main**   页面的主要内容
* **aside** 页面的次要内容，侧边栏
* **div** 通用的容器


## 4.全局属性
* **class**赋值，可单个属性值也可以多个
* **contenteditable** 内容可编辑的
* **hidden**让一个东西看不见、
* **id**可以给东西加边框颜色等
   * **不到万不得已不要用**因为不报错
   * 与css相关
   * 与js相关，可以在js里直接调用id(同名id只能有一个，不然js找不到)

* **style**属性优先级高于css，但是js是最高的。
* **tabindex**页面上的东西可以用tab访问。
   * 访问的顺序是按数字的大小顺序来的，但是不需连号
   * tabindex = 0 是最后访问的
   * 负数是不访问的

* **title**将鼠标悬停在一个标签上方时，浏览器会将详细的信息展示出来。
    * white-space;表示不换行
    * text-overflow: ellipsis;
    overflow:hidden；超出部分隐藏

## 5.常用的表示内容的标签有哪些？分别是什么意思。
* **ol+li** 有序列表 如：1.----2.-----
* **ul+li** 无序列表 如  *.---- *.-----
* **dl+dt+dd** 描述列表，dt是表述对象，dd是描述内容
* **pre** preview,pre标签中的空格，回车和tab。因为HTML中的空格，回车和tab不会合并
* **hr** 分割线，写在代码或内容的下面
* **br** 用来换行，写在需要换行的代码前
* **a** 超链接，可以加target="_blank"新建页面来打开
* **em** 主观语气上的强调
* **strong** 客观上的重要内容
* **quote** 引用(不换行)
* **blockquote** 换行的引用

  