https://github.com/yygmind/blog/issues/5

#### react 
+ React生命周期及自己的理解
+ 介绍react优化
+ React组件中怎么做事件代理
+ React组件事件代理的原理
+ React怎么做数据的检查和变化
+ React层面的性能优化
+ React中Dom结构发生变化后内部经历了哪些变化
+ React挂载的时候有3个组件，textComponent、composeComponent、domComponent，区别和关系，Dom结构发生变化时怎么区分data的变化，怎么更新，更新怎么调
度，如果更新的时候还有其他任务存在怎么处理
+ react异步渲染的概念,介绍Time Slicing 和 Suspense
+ 16.X声明周期的改变
+ 16.X中props改变后在哪个生命周期中处理
+ pureComponent和FunctionComponent区别
+ 介绍高阶组件
+ react生命周期
+ react中的key的作用
+ shouldComponentUpdate是为了解决什么问题
+ react生命周期，常用的生命周期，对应的生命周期做什么事
+ 遇到性能问题一般在哪个生命周期里解决
+ 怎么做性能优化（异步加载组件...）
+ 写react有哪些细节可以优化
+ React的事件机制（绑定一个事件到一个组件上）
+ react的理念是什么（拿函数式编程来做页面渲染）
+ 对react看法，它的优缺点
+ React的生命周期
+ componentWillReceiveProps的触发条件是什么
+ React16.3对生命周期的改变
+ 介绍下React的Filber架构，画Filber渲染树
+ 介绍React高阶组件
+ 父子组件之间如何通信

#### react-router
+ 如何配置React-Router
+ 路由的动态加载模块
+ 介绍路由的history
+ 前端怎么控制管理路由
+ 使用路由时出现问题如何解决
+ react-router怎么实现路由切换
+ react-router里的<Link>标签和<a>标签有什么区别


#### redux 
+ 介绍Redux数据流的流程
+ Redux如何实现多个组件之间的通信，多个组件使用相同状态如何进行管理
+ 多个组件之间如何拆分各自的state，每块小的组件有自己的状态，它们之间还有一些公共的状态需要维护，如何思考这块
+ 使用过的Redux中间件 
+ 介绍redux，主要解决什么问题
+ redux请求中间件如何处理并发
+ Redux中异步的请求怎么处理
+ Redux中间件是什么东西，接受几个参数（两端的柯里化函数）
+ 中间件是怎么拿到store和action，然后怎么处理
+ state是怎么注入到组件的，从reducer到组件经历了什么样的过程
+ redux的设计思想
+ 接入redux的过程
+ 绑定connect的过程
+ connect原理
+ Redux在状态管理方面解决了React本身不能解决的问题
+ Redux有没有做过封装
+ 介绍Redux工作流程

#### webpack 
+ 使用过webpack里面哪些plugin和loader
+ webpack里面的插件是怎么实现的
+ dev-server是怎么跑起来
+ 抽取公共文件是怎么配置的
+ import { Button } from 'antd' ，打包的时候只打包button，分模块加载，是怎么做到的
+ 使用import时，webpack对node_modules里的依赖会做什么
+ webpack整个生命周期，loader和plugin有什么区别
+ webpack介绍
+ webpack生命周期
+ webpack打包的整个过程
+ 常用的plugins
+ 一般怎么组织CSS（Webpack）

#### es6
+ promise、async有什么区别
+ 介绍Promise，异常捕获
+ 对async、await的理解，内部原理
+ 介绍下Promise，内部实现
+ ES6中的map和原生的对象有什么区别
+ 如何设计Promise.all()
+ 使用Async会注意哪些东西
+ Async里面有多个await请求，可以怎么优化（请求是否有依赖）
+ Promise和Async处理失败的时候有什么区别
+ Promise 和 async/await 和 callback的区别
+ Promise有没有解决异步的问题（promise链是真正强大的地方）
+ Promise和setTimeout的区别（Event Loop）
+ let、const以及var的区别
+ 浅拷贝和深拷贝的区别
+ 介绍箭头函数的this
+ 介绍Promise和then
+ 介绍Promise
+ Promise有几个状态

#### node 
+ 使用过的koa2中间件
+ koa-body原理
+ koa中response.send、response.rounded、response.json发生了什么事，浏览器为什么能识别到它是一个json结构或是html
+ koa-bodyparser怎么来解析request
+ 如何和MySQL进行通信
+ 介绍自己写过的中间件
+ 介绍pm2
+ master挂了的话pm2怎么处理
+ pm2怎么做进程管理，进程挂掉怎么处理
+ 不用pm2怎么做进程管理
+ koa原理，为什么要用koa(express和koa对比)
+ 使用的koa中间件

#### 跨域
+ 如何解决跨域的问题
+ 表单可以跨域吗
+ 跨域怎么解决，有没有使用过Apache等方案
+ 对跨域的了解
+ 介绍下浏览器跨域
+ 怎么去解决跨域问题
+ Access-Control-Allow-Origin在服务端哪里配置
+ csrf跨站攻击怎么解决

#### http
+ 常见Http请求头
+ 介绍http2.0
+ http1.1时如何复用tcp连接
+ Http报文的请求会有几个部分
+ http缓存控制
+ 介绍下HTTP状态码
+ 403、301、302是什么
+ 缓存相关的HTTP请求头
+ HTTPS怎么建立安全通道
+ 

#### 原生js
+ == 和 ===的区别，什么情况下用相等==
+ bind、call、apply的区别
+ 介绍下原型链（解决的是继承问题吗）
+ 两个对象如何比较
+ JS的原型
+ 变量作用域链
+ call、apply、bind的区别
+ JS变量类型分为几种，区别是什么
+ JS里垃圾回收机制是什么，常用的是哪种，怎么处理的

#### css
+ 移动端适配1px的问题
+ 介绍flex布局
+ 其他css方式设置垂直居中
+ 居中为什么要使用transform（为什么不使用marginLeft/Top）
+ 介绍css3中position:sticky
+ 介绍position属性包括CSS3新增
+ 清除浮动
+ 定位问题（绝对定位、相对定位等）
+ transform动画和直接使用left、top改变位置有什么优缺点

#### 动画
+ 动画的了解

#### ssr
+ 服务端渲染SSR

#### cookie
+ cookie放哪里，cookie能做的事情和存在的价值
+ cookie和token都存放在header里面，为什么只劫持前者
+ cookie和session有哪些方面的区别
+ localStorage和cookie有什么区别
