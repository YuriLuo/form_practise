# 前端技术

## 1、html

常用标签，超文本标记语言，网页的基本结构。

```html
<!DOCTYPE html>
<!--html5的声明，记住就行-->
<html>
<!--页面的根元素-->
<head>
<!--包含文档的元（meta）数据，比如下面的编码-->
<meta charset="UTF-8">
<title>页面标题</title>
</head>
<body>
 <!--这里是指页面中能够看到的内容-->
<h1>我的第一个标题</h1>
 
<p>我的第一个段落。</p>
 
</body>
</html>
```

html：一个网站基本上10个标签左右就ok

html文档 = 标签+文本内容

html通过浏览器内核来解析，不用解释器或者浏览器

## 2、css

常用样式，网页的显示效果

CSS3被拆分为"模块"。旧规范已拆分成小块，还增加了新的。

css3的圆角

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"> 
<title>菜鸟教程(runoob.com)</title> 
<style> 
#rcorners1 {
    border-radius: 25px;
    background: #8AC007;
    padding: 20px; 
    width: 200px;
    height: 150px;    
}

#rcorners2 {
    border-radius: 25px;
    border: 2px solid #8AC007;
    padding: 20px; 
    width: 200px;
    height: 150px;    
}

#rcorners3 {
    border-radius: 25px;
    background: url(/images/paper.gif);
    background-position: left top;
    background-repeat: repeat;
    padding: 20px; 
    width: 200px;
    height: 150px;    
}
</style>
</head>
<body>

<p> border-radius 属性允许向元素添加圆角。</p>
<p>指定背景颜色元素的圆角:</p>
<p id="rcorners1">圆角</p>
<p>指定边框元素的圆角:</p>
<p id="rcorners2">圆角</p>
<p>指定背景图片元素的圆角:</p>
<p id="rcorners3">圆角</p>

</body>
</html>
```



一些最重要CSS3模块如下：

- 选择器
- 盒模型
- 背景和边框
- 文字特效
- 2D/3D转换
- 动画
- 多列布局
- 用户界面

## 3、Js

用户的交互效果，动态效果

## 4、Jquery

Js的一个框架，简化原生JS操作

进入jquery页面，右键“检查”，找到network中的jquery.版本号.js文件，保存并放入项目文件夹中

项目文件夹的前端部分由html、css、js、image等组成，把js文件放入指定文件夹内，并在html文件中引用jquery.js即可使用此框架。

jquery.js一定要放在index.js之前。

## 5、Ajax

异步数据交互，让页面不刷新的情况下进行数据交互

## 6、Bootstrap

前端UI框架，快速搭建静态页面并支持不同设备







