# Modules: ECMAScript modules


|本期版本|上期版本
|:---:|:---:
`Tue Dec 10 15:03:51 CST 2024` | -

## [02_模块化-CommonJS和ESModule相互引用](https://github.com/nanana-100/qq-3619571/tree/main/27-02)

```javascript
const generator = require("@babel/generator").default;
```

## [861--day49_ES Module使用-原理-包管理工具npm等_05_(掌握)ESModule的默认导出和导入](https://github.com/nanana-100/coderwhy/tree/main/s05/day49/0860)

```javascript
// 方案一
function parseLyric(){}
export default parseLyric

// 方案二
export default function() {}

// 方案三
export {parseLyric as default};
```


## [860--day49_ES Module使用-原理-包管理工具npm等_04_(理解)ESModule的导入和导出结合使用](https://github.com/nanana-100/coderwhy/tree/main/s05/day49/0860)

```javascript
// 优化一
export { formatCount, formatDate } from './format.js'
export { parseLyric } from './parse.js'

// 优化二
export * from './format.js'
export * from './parse.js'
```

## Ref

* <https://nodejs.org/docs/latest-v22.x/api/esm.html>