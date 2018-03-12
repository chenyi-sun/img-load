用的5的webpack-learn里面的配置<br/>
main.js会自动选出页面中所有的img元素，并获取它的地址，在get里面。<br/>
然后不停的刷新判断图片是否加载完成，当所有的图片都加载完成，可以把图片插入到img中<br/>
<br/>
<br/>
可以通过allInit()来调用以上所有的行为<br/>
allInit的参数(a,b,c)<br/>
参数a示例<br/>
var allImages = document.getElementsByTagName('img');<br/>
参数b示例<br/>
b等于false或者true,false最后完成图片就不会加载，如果是true，图片就会加载<br/>
参数c示例<br/>
 function(){<br/>
   console.log('sss')<br/>
   }<br/>
这个function执行的是所有图片加载完成以后执行的行为函数<br/>

编译es6<br/>
生成静态文件<br/>
热加载,自动刷新<br/>
编译sass.css<br/>
<br/>
<br/>

<br/>
=================
-npm install<br/>
-npm run dev <br/>
(生产环境)
-webpack<br/>
(打包生成页面) <br/>
<br/>
<br/>
<br/>
==================
目录结构<br/>
-app<br/>
----依赖的js和less<br/>
-public<br/>
----打包好的index和js,css填充在bundle.js里面<br/>
-<br/>
<br/>
<br/>
==================
dev构建所依赖的几个文件<br/>
-public 下index.html<br/>
-app 下Main.js,greeter.js<br/>
-<br/>
打包所依赖的文件<br/>
-public 下index.html<br/>
-Public 下的bundle.js<br/>
