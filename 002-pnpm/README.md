# pnpm

|本期版本|上期版本
|:---:|:---:
`Sat Mar 15 12:06:16 CST 2025` | `Tue Dec  3 12:39:30 CST 2024`


> <https://pnpm.io/configuring>

```bash
npm install -g pnpm

mkdir -p /Volumes/THAWSPACE/.pnpm/store/v3
pnpm config set store-dir /Volumes/THAWSPACE/.pnpm/store/v3
# 获取当前活跃的store目录
pnpm store path
```

```bash
# pnpm setup
set -gx PNPM_HOME "/Volumes/THAWSPACE/.pnpm"
fish_add_path  $PNPM_HOME

pnpm add -g create-vue
```




## [`874--day50_包管理器-npx-pnpm-webpack构建工_09_(掌握)pnpm的常见命令和store存储`](https://github.com/nanana-100/coderwhy/tree/main/s05/day50/0874)


```bash
# 从store中删除当前未被引用的包来释放store的空间
pnpm store prune

pnpm store add @vue/cli
```

## Ref

* <https://pnpm.io/>