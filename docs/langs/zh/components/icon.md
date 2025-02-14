---
title: Icon
lang: zh
---

<script setup lang="ts">
  import props from "../../../example/icon/description/zh-props.ts";
</script>

# Icon 图标

集成了[```Iconify```](https://iconify.design/) https://iconify.design/ 上千个常用的图标。


如果你想像用例一样直接使用，你需要简单操作一下，才能够直接在项目里使用。

# 安装

```
# 选择一个你喜欢的包管理器

# NPM
$ npm install fusion-ui-iconify
# Yarn
$ yarn add fusion-ui-iconify
# pnpm
$ pnpm install fusion-ui-iconify
```

# 注册图标
您需要从 ```fusion-ui-iconify``` 中导入图标并进行全局注册。

```main.ts```
```ts

import Icon form 'fusion-ui-iconify'

app.use(Icon)
```

# 使用图标

你可以在任何地方使用图标，只需要在标签中添加图标名称即可。

<demo src="../../../example/icon/icon.vue"></demo>

## 尺寸大小

图标默认尺寸 ```16``` ，你可以通过 ```size``` 属性来设置图标大小。

<demo src="../../../example/icon/size.vue"></demo>

## 颜色

你可以通过```color```属性来设置图标颜色。

<demo src="../../../example/icon/color.vue"></demo>

## 属性

<table-block type="propsZh" :data="props"></table-block>