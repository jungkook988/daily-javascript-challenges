# daily-javascript-challenge

### 2022/12/28

> easy-deep-shallow-clone

- shallowClone in JavaScript
- - Object.assign
- - Array.prototype.slice()
- - Array.prototype.concat()
- - [...old]

- deepClone in JavaScript
- - \_.cloneDeep(old)（lodash）
- - $.extend(Boolean, new, old)（jquery）
- - JSON.parse(JSON.stringify(old))（会忽略函数、symbol 和 undefined）
- - deepClone(old, hash = new WeakMap())

### 2022/12/29

> easy-module-type

- CommonJS
- - 面向服务端 node 以及 webpack
- - 同步加载，磁盘读取速度快
- AMD
- - 面向浏览器，属于 CommonJS 的浏览器端实现
- - 异步加载，速度快；依赖预加载，浪费资源
- CMD
- - 面向浏览器，根据 CommonJS 和 AMD 共同实现
- - 异步加载、按需加载，导致速度性能差
- ES Module
- - 面向浏览器，属于当前浏览器默认标准
- - 静态编译，编译时就能确定依赖关系

### 2022/12/30

> medium-iterator-generator

- Iterator 的作用
- Symbol.iterator 是一个接口，用于生成 Iterator
- Generator 的作用
- Generator 的用法
- - 1. 函数前面加星号
- - 2. yield 关键字控制流程
- Generator 实现状态机
- Generator 实现异步代码