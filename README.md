# Notes-nodejs

本次使用的express4.x版本，针对此版本与网上教程不同做出的笔记

> express

(express在线学习)[http://www.hubwiz.com/class/544db33888dba01ef09d0682]

***

> 路由

**所谓“路由”就是指为不同的方位路径，指定不同的处理方法**

> var root = __dirname

**__dirname在Node中是一个神奇的变量，它的值是该文件所在目录的路径**

***

> node app.js

**使用express4.x生成的框架要使用npm start来运行，不然会无响应直接跳出**

***

> req.host

**express将host改成hostname**

***

> res.send()

**请改成res.sendStatus()**
