# pnpm

|本期版本|上期版本
|:---:|:---:
`Tue Dec  3 12:39:30 CST 2024` | -

```bash
npm install -g pnpm
```

## [`874--day50_包管理器-npx-pnpm-webpack构建工_09_(掌握)pnpm的常见命令和store存储`](https://github.com/nanana-100/coderwhy/tree/main/s05/day50/0874)


```bash
# 获取当前活跃的store目录
pnpm store path

# 从store中删除当前未被引用的包来释放store的空间
pnpm store prune
```

> <https://pnpm.io/configuring>

```bash
# 设置新目录
pnpm config set store-dir /Volumes/THAWSPACE/.pnpm-store

# webpack
pnpm store add @babel/core @babel/cli @babel/preset-env @babel/preset-react babel-loader
pnpm store add webpack webpack-cli webpack-dev-server
pnpm store add html-webpack-plugin
pnpm store add style-loader css-loader
pnpm store add sass-loader sass
pnpm store add postcss-loader postcss
```

## Ref

* <https://pnpm.io/>