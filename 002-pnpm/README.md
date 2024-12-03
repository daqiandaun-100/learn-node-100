# pnpm

|本期版本|上期版本
|:---:|:---:
`Tue Dec  3 12:39:30 CST 2024` | -

```bash
npm install -g pnpm
```


获取当前活跃的store目录

```bash
pnpm store path
```

从store中删除当前未被引用的包来释放store的空间

```bash
pnpm store prune
```

## 设置新目录

> <https://pnpm.io/configuring>

```
pnpm config set store-dir /Volumes/THAWSPACE/.pnpm-store
pnpm store add  @babel/core @babel/cli @babel/preset-env @babel/preset-react babel-loader
pnpm store add  webpack webpack-cli 
```

## Ref

* <https://pnpm.io/>