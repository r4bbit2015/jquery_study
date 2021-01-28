JQuery学习笔记

###### 在编写jQuery代码的时候debug方法

```javascript
        //原生js固定写法
        windows.onload = function(ev){}
        //2.jqeury固定写法
        $(document).ready(function(){
            alert("hello world");
            console.log("hello jquery");
        });

```

运行的时候浏览器没有任何提示，需要使用控制台查看是否有报错

![image-20210129022938789](https://raw.githubusercontent.com/r4bbit2015/picgo/main/image-20210129022938789.png)

#### jquery入口函数与js入口函数的区别

- js中多个入口函数会相互覆盖，jquery的多个入口函数不会相互覆盖

- js中入口函数会等待图片加载完毕后在运行，jquery的入口函数不会等待图片加载完毕后运行



