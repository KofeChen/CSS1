# 静态页面挑战项目代码

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>我的项目</title>
    <style>
        h3,p,ul,li,body{
            margin: 0;
            padding: 0;
        }
        ul>li{
            list-style: none;
        }
        a{
            text-decoration:none;
        }
        body{
            font: 14px/1.4 Arial;
            background:#fff2e3;
            text-align: center;
        }
        .title{
            margin-top:40px;
            font-size: 40px;
            color: #87968e;
            font-weight: bold;
        }
        .introduce{
            margin-top: 30px;
            color: #87968e;
        }
        .btn-ct{
            margin-top: 40px;
        }
        .btn-ct>li{
            display: inline-block;
            margin: 0 7px;
        }
        .btn{
            display: inline-block;
            color: #ffffff;
            padding: 4px 15px;
            background: #72b890;
            border-radius: 4px;
        }
        .btn:hover{
            opacity: 0.7;
        }
        .btn :active{
            opacity: 1 ;
        }
        .img{
            margin-top: 30px;
        }
        .opr-ct{
            margin-top: 30px;
        }
        .opr-ct>li{
            display: inline-block;
            margin: 0 9px;
        }
        .writer{
            margin-top: 40px;
            margin-bottom: 30px;
        }
        .writer a{
            color:#72b890;
        }
    </style>
</head>
<body>
    <div>
        <h3 class="title">静态页面挑战</h3>
        <p class="introduce">饥人谷学习CSS基本样式练习</p>
        <ul class="btn-ct">
            <li><a class="btn" href="#">项目1</a></li>
            <li><a class="btn" href="#">项目2</a></li>
            <li><a class="btn" href="#">项目3</a></li>
            <li><a class="btn" href="#">项目4</a></li>
            <li><a class="btn" href="#">项目5</a></li>
        </ul>
        <img class="img" src="http://cdn.jscode.me/65d4aba2-a097-4b24-aaa0-ebbaf7eedab2" alt="项目图片">
        <ul class="opr-ct">
            <li><a class="btn" href="#">查看源码</a></li>
            <li><a class="btn" href="#">使用说明</a></li>
        </ul>
        <p class="writer">作者：<a href="#">我</a></p>
    </div>
</body>
</html>
```
