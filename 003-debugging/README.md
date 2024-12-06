# Debugging Node.js

|本期版本|上期版本
|:---:|:---:
`Fri Dec  6 10:04:08 CST 2024` | -

```bash
node --inspect-brk=0.0.0.0:9229 app.js
chrome://inspect
```

```javascript
(function(exports, require, module, __filename, __dirname) {
  console.log("Hello World!");
});
```

## Ref

* [3-1 环境 & 调试 ——CommonJS1](https://github.com/nanana-100/imooc-146/tree/main/03-01)
* <https://nodejs.org/en/learn/getting-started/debugging>
* [Nodejs 之 exports, require, module, \_\_filename, \_\_dirname](https://juejin.cn/post/6844903551534104590)
* [Node 调试工具入门教程](http://www.ruanyifeng.com/blog/2018/03/node-debugger.html)