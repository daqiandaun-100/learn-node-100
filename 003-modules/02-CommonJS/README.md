# CommonJS

|本期版本|上期版本
|:---:|:---:
`Fri Dec  6 12:57:30 CST 2024` | -

## coderwhy

* [`850--day48_邂逅Node-Node安装-前端模块化_09_(掌握)Node中常见的全局对象`](https://github.com/nanana-100/coderwhy/tree/main/s05/day48/0850)
* [`854--day48_邂逅Node-Node安装-前端模块化_13_(掌握)Node中module的exports属性本质`](https://github.com/nanana-100/coderwhy/tree/main/s05/day48/0854)
* [`855--day48_邂逅Node-Node安装-前端模块化_14_(理解)Node中require查找模块的细节`](https://github.com/nanana-100/coderwhy/tree/main/s05/day48/0855)
* [`01_模块化-commonjs中require细节`](https://github.com/nanana-100/qq-3619571/tree/main/26-01)

```javascript
console.log(module.paths)
```

```javascript
require('axios')

// axios/index.js
module.exports = require('./lib/axios')
```


## 146 Node.js入门到企业Web开发中的应用 - 慕课网

* [`3-1 环境 & 调试 ——CommonJS1`](https://github.com/nanana-100/imooc-146/tree/main/03-01)
* [`3-5 环境 & 调试——module.exports 与 exports 的区别`](https://github.com/nanana-100/imooc-146/tree/main/03-05)

```javascript
(function(exports, require, module, __filename, __dirname) {
  console.log("Hello World!");
});
```

## Ref

* [The module wrapper](https://nodejs.org/docs/latest-v22.x/api/modules.html#the-module-wrapper)
* [All together](https://nodejs.org/docs/latest-v22.x/api/modules.html#all-together)
* [Nodejs 之 exports, require, module, \_\_filename, \_\_dirname](https://juejin.cn/post/6844903551534104590)