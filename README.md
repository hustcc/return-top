
# x-return-top


> 纯javascript代码实现的“返回顶部”功能，代码非常简单，集成起来更简单，代码大小只有2.2kb，并且提供CDN，完全不会拖慢你的网站速度。

在制作网页中，经常会发现网页非常长，为了用户的方便，都会设置返回顶部的按钮，用户一键返回网页顶部；
如果你的网站中使用jquery，那么有很多的插件可以完成这个工作，可以在git中搜索很多。

然而，如果你的网页中没有使用jquery，那么如果要使用这些插件，就必须为了这一个很小的功能，加上jquery，对于网页的加载速度非常不划算。


## 使用 ##

使用非常简单，如下所示，放到Body之间即可，切勿放到head中。

	<script type="text/javascript" src="dist/x-return-top.min.js"></script>


## 配置项

 - `left`: 位置定位左侧, 默认: `'80%'` 
 - `bottom`: 位置定位右侧, 默认: `15%`
 - `text`: 显示的文本内容, 默认: `Back Top`

例如：

	<script type="text/javascript" left="80%" bottom="20%" text="返回顶部" src="dist/x-return-top.min.js"></script>


## 说明 ##

- git上大部分的“返回顶部”项目都是基于jquery，使用前必须应用jquery
- git上部分纯javascript实现的“返回顶部”，无动画，不美观
- 本项目使用纯javascript，实现动画，美观且不影响网页加载速度，不依赖任何js框架
- 压缩之后2.2kb
- 集成非常简单
- 使用部分css3动画，所以兼容性你懂的（但是不会影响使用，后续会改为js动画）
- css使用js动态加载，集成更方便，且不影响网页加载速度
- 图片使用base64加载，不会增加http请求数


## Demo ##

 - Live Demo 1: [https://aibq.cn](https://aibq.cn)
 - Live Demo 2: [http://www.atool.org](http://www.atool.org)
 - 项目代码中的index.html
![](https://raw.githubusercontent.com/hustcc/x-return-top.js/master/screenshot/shot.gif)



