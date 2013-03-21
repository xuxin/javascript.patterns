# JavaScript Patterns

![JavaScript.patterns](http://img03.taobaocdn.com/tps/i3/T1np5gXj4nXXXXXXXX-320-420.jpg)

**“JavaScript patterns”中译本** - 《JavaScript 模式》

- 作者：[Stoyan Stefanov](http://www.phpied.com/)
- 翻译：[拔赤](http://jayli.github.com/)、[goddyzhao](http://goddyzhao.me)、[TooBug](http://www.toobug.net)

偷懒是程序员的优良品质，模式则是先人们总结的偷懒招式。Stoyan Stefanov 的这本书，从 JavaScript 的实际使用场景出发，提炼了不少可以让前端们偷懒的实用招式。模式的探索、创新，将永远是程序员自我提升的一条修炼之道。值得一读。

# 目录

## [第一章 概述](/chapter1.markdown)

- [模式](/chapter1.markdown)
- [JavaScript：概念](/chapter1.markdown#a2)
	- [面向对象](/chapter1.markdown#a3)
	- [无类](/chapter1.markdown#a4)
	- [原型](/chapter1.markdown#a5)
	- [运行环境](/chapter1.markdown#a6)
- [ECMAScript 5](/chapter1.markdown#a7)
- [JSLint](/chapter1.markdown#a8)
- [控制台工具](/chapter1.markdown#a9)

## [第二章 高质量JavaScript基本要点](/chapter2.markdown)

- [编写可维护的代码](/chapter2.markdown#a2)
- [减少全局对象](/chapter2.markdown#a3)
	- [全局对象带来的困扰](/chapter2.markdown#a4)
	- [忘记var时的副作用](/chapter2.markdown#a5)
	- [访问全局对象](/chapter2.markdown#a6)
	- [单 var 模式](/chapter2.markdown#a7)
	- [声明提前：分散的 var 带来的问题](/chapter2.markdown#a8)
- [for 循环](/chapter2.markdown#a9)
- [for-in 循环](/chapter2.markdown#a10)
- [（不）扩充内置原型](/chapter2.markdown#a11)
- [switch 模式](/chapter2.markdown#a12)
- [避免隐式类型转换](/chapter2.markdown#a13)
	- [避免使用 eval()](/chapter2.markdown#a14)
- [使用parseInt()进行数字转换](/chapter2.markdown#a15)
- [编码风格](/chapter2.markdown#a16)
	- [缩进](/chapter2.markdown#a17)
	- [花括号](/chapter2.markdown#a18)
	- [左花括号的放置](/chapter2.markdown#a19)
	- [空格](/chapter2.markdown#a20)
- [命名规范](/chapter2.markdown#a21)
	- [构造器命名中的大小写](/chapter2.markdown#a22)
	- [单词分隔](/chapter2.markdown#a23)
	- [其他命名风格](/chapter2.markdown#a24)
- [书写注释](/chapter2.markdown#a25)
- [书写API文档](/chapter2.markdown#a26)
	- [一个例子：YUIDoc](/chapter2.markdown#a27)
- [编写易读的代码](/chapter2.markdown#a28)
- [相互评审](/chapter2.markdown#a29)
- [生产环境中的代码压缩（Minify）](/chapter2.markdown#a30)
- [运行JSLint](/chapter2.markdown#a31)
- [小结](/chapter2.markdown#a32)

## [第三章 直接量和构造函数](/chapter3.markdown)

- [对象直接量](/chapter3.markdown#a2)
	- [对象直接量语法](/chapter3.markdown#a3)
	- [通过构造函数创建对象](/chapter3.markdown#a4)
	- [获得对象的构造器](/chapter3.markdown#a5)
- [自定义构造函数](/chapter3.markdown#a6)
	- [构造函数的返回值](/chapter3.markdown#a7)
- [强制使用new的模式](/chapter3.markdown#a8)
	- [命名约定](/chapter3.markdown#a9)
	- [使用that](/chapter3.markdown#a10)
	- [调用自身的构造函数](/chapter3.markdown#a11)
- [数组直接量](/chapter3.markdown#a12)
	- [数组直接量语法](/chapter3.markdown#a13)
	- [有意思的数组构造器](/chapter3.markdown#a14)
	- [检查是不是数组](/chapter3.markdown#a15)
- [JSON](/chapter3.markdown#a16)
	- [使用JSON](/chapter3.markdown#a17)
- [正则表达式直接量](/chapter3.markdown#a18)
	- [正则表达式直接量语法](/chapter3.markdown#a19)
- [原始值的包装对象](/chapter3.markdown#a20)
- [Error对象](/chapter3.markdown#a21)
- [小结](/chapter3.markdown#a22)

## [第四章 函数](/chapter4.markdown)

- [背景知识](/chapter4.markdown#a2)
	- [术语释义](/chapter4.markdown#a3)
	- [声明 vs 表达式：命名与提前](/chapter4.markdown#a4)
	- [函数的name属性](/chapter4.markdown#a5)
	- [函数提前](/chapter4.markdown#a6)
- [回调模式](/chapter4.markdown#a7)
	- [一个回调的例子](/chapter4.markdown#a8)
	- [回调和作用域](/chapter4.markdown#a9)
	- [异步事件监听](/chapter4.markdown#a10)
	- [超时](/chapter4.markdown#a11)
	- [库中的回调](/chapter4.markdown#a12)
- [返回函数](/chapter4.markdown#a12)
- [自定义函数](/chapter4.markdown#a14)
- [立即执行的函数](/chapter4.markdown#a15)
	- [立即执行的函数的参数](/chapter4.markdown#a16)
	- [立即执行的函数的返回值](/chapter4.markdown#a17)
	- [好处和用法](/chapter4.markdown#a18)
- [立即初始化的对象](/chapter4.markdown#a19)
- [条件初始化](/chapter4.markdown#a20)
- [函数属性——Memoization模式](/chapter4.markdown#a21)
- [配置对象](/chapter4.markdown#a22)
- [柯里化 （Curry）](/chapter4.markdown#a23)
	- [函数应用](/chapter4.markdown#a24)
	- [部分应用](/chapter4.markdown#a25)
	- [柯里化](/chapter4.markdown#a26)
	- [什么时候使用柯里化](/chapter4.markdown#a27)
- [小结](/chapter4.markdown#a28)

## 第五章 对象创建模式

- 命名空间模式
	- 通用的命名空间函数
- 声明依赖
- 私有属性和方法
	- 私有成员
	- 特权方法
	- 私有化失败
	- 对象直接量及其私有成员
	- 原型及其私有成员
	- 将私有函数暴露为共有方法
- 模块模式
	- 暴露模块模式
	- 创建构造器的模块
	- 在模块中引入全局上下文
- 沙箱模式
	- 全局构造函数
	- 添加模块
	- 实现这个构造函数
- 静态成员
	- 共有静态成员
	- 私有静态成员
- 对象常量
- 链式调用模式
	- 链式调用模式的利弊
- method() 方法
- 小节

## [第六章 代码复用模式](/chapter6.markdown#a1)

- [类式继承 vs 现代继承模式](/chapter6.markdown#a2)
- [类式继承的期望结果](/chapter6.markdown#a3)
- [类式继承 1  ——默认模式](/chapter6.markdown#a4)
	- [跟踪原型链](/chapter6.markdown#a5)
	- [这种模式的缺点](/chapter6.markdown#a6)
- [类式继承 2 ——借用构造函数](/chapter6.markdown#a7)
	- [原型链](/chapter6.markdown#a8)
	- [利用借用构造函数模式实现多继承](/chapter6.markdown#a9)
	- [借用构造函数的利与弊](/chapter6.markdown#a10)
- [类式继承 3 ——借用并设置原型](/chapter6.markdown#a11)
- [类式继承 4 ——共享原型](/chapter6.markdown#a12)
- [类式继承 5 —— 临时构造函数](/chapter6.markdown#a13)
	- [存储父类](/chapter6.markdown#a14)
	- [重置构造函数引用](/chapter6.markdown#a15)
- [Klass](/chapter6.markdown#a16)
- [原型继承](/chapter6.markdown#a17)
	- [讨论](/chapter6.markdown#a18)
	- [例外的ECMAScript 5](/chapter6.markdown#a19)
- [通过复制属性继承](/chapter6.markdown#a20)
- [混元（Mix-ins）](/chapter6.markdown#a21)
- [借用方法](/chapter6.markdown#a22)
	- [例：从数组借用](/chapter6.markdown#a23)
	- [借用并绑定](/chapter6.markdown#a24)
	- [Function.prototype.bind()](/chapter6.markdown#a25)
- [小结](/chapter6.markdown#a26)

## [第七章 设计模式](/chapter7.markdown#a1)

- [单例](/chapter7.markdown#a2)
	- [使用new](/chapter7.markdown#a3)
	- [将实例放到静态属性中](/chapter7.markdown#a4)
	- [将实例放到闭包中](/chapter7.markdown#a5)
- [工厂模式](/chapter7.markdown#a6)
	- [内置对象工厂](/chapter7.markdown#a7)
- [迭代器](/chapter7.markdown#a8)
- [装饰器](/chapter7.markdown#a9)
	- [用法](/chapter7.markdown#a10)
	- [实现](/chapter7.markdown#a11)
	- [使用列表实现](/chapter7.markdown#a12)
- [策略模式](/chapter7.markdown#a13)
	- [数据验证示例](/chapter7.markdown#a14)
- [外观模式](/chapter7.markdown#a15)
- [代理模式](/chapter7.markdown#a16)
	- [一个例子](/chapter7.markdown#a17)
- [中介者模式](/chapter7.markdown#a18)
	- [中介者示例](/chapter7.markdown#a19)
- [观察者模式](/chapter7.markdown#a20)
	- [例1：杂志订阅](/chapter7.markdown#a21)
	- [例2：按键游戏](/chapter7.markdown#a22)
- [小结](/chapter7.markdown#a23)

## 第八章 DOM和浏览器模式

- 分离关注点
- DOM 脚本编程
	- DOM访问
	- DOM操作
- 事件
	- 事件处理
	- 事件委托
- 长时间运行的脚本
	- setTimeout()
	- Web Workers
- 远程脚本
	- XMLHttpRequest
	- JSONP
	- Frame和Image加载指示器
- 部署JavaScript
	- 合并脚本
	- 代码减肥和压缩
	- 过期头
	- 使用CDN
- 加载策略
	- script标签的位置
	- HTTP 分块
	- 动态插入script标签非阻塞载入脚本
	- 延迟加载
	- 按需加载
	- 预加载
- 小节

## 索引

