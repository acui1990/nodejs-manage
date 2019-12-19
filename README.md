# nodejs-manage
## nodejs后台开发方向
-使用nodejs+express起个web服务，前端可以用熟悉的js，自己编写一些接入层的逻辑。诸如：实现页面路由，定义Restful API，访问数据的统计，也可以在服务端进行数据直出，优化页面性能等等
### 目录介绍：
	-node_modules, 存放所有的项目依赖库。(每个项目管理自己的依赖，与Maven,Gradle等不同)
	-package.json，项目依赖配置及开发者信息
	-app.js，程序启动文件
	-public，静态文件(css,js,img)
	-routes，路由文件(MVC中的C,controller)
	-Views，页面文件(Ejs模板)
### Nodejs有关的开发姿势与技巧
#### Express
```
这是我在开发项目中经常使用的nodejs Web应用框架，
简单实用，提供了一系列强大特性帮助你创建各种 Web 应用，和丰富的 HTTP 工具。
使用 Express 可以快速地搭建一个完整功能的网站
```
#### eggjs
```
Eggjs是一套基于koa实现的企业级的web server框架
基于Koa.js的基础框架，特点是高度可扩展，通过框架聚合各种插件，可以轻松的实现各种后端功能开发，
例如使用 egg-mysql 插件可以快速的开发基于Mysql操作的业务逻辑接口。
```
#### Time
```
Moment
JavaScript 日期处理类库
[学习网址](http://momentjs.cn/)
```
#### 日志log
```
morgan：一个node.js关于http请求的日志中间件
log4js：在Nodejs中使用express框架并没有自带的日志模块，
我们可以选择log4js来完成日志记录的功能。简单高效，容易上手。
学习的网址：[https://nomiddlename.github.io/log4js-node/]
```
#### 异步解决方案
```
promise:Promise 对象用于一个异步操作的最终完成（或失败）及其结果值的表示。
有了Promise对象，就可以将异步操作以同步操作的流程表达出来，避免了层层嵌套的回调函数。
学习网址：https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Promise
Async/Await：目前流行的简单异步解決方案，以同步的方式解决异步的烦恼
学习的网址：[http://www.ruanyifeng.com/blog/2015/05/async.html]
```
#### http请求
```
request:Request模块封装了http请求，使你可以用很简单的方式处理http请求，同时也支持HTTPS和请求重定向。
学习的网址：[https://itbilu.com/nodejs/npm/NJLUyVB7.html]
```
#### 加密算法
```
crypto模块：是Nodejs的一个基本模块，提供了加密功能，包括对 OpenSSL 的哈希、HMAC、加密、解密、签名、以及验证功能的一整套封装。
使用Nodejs的crypto模块，可以支持常见的加解密方法，以提高我们项目的安全性。
学习的网址：[https://www.liaoxuefeng.com/wiki/1022910821149312/1023025778520640]
```


