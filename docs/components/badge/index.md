# Badge 徽章

按钮和图标上的数字或状态标记。

## 基础用法

可以用来展示新消息的数量。

显示值可接受 `Number` 或 `String`。

:::demo

```vue
<template>
  <W2Badge :value="7" type="info" class="item">
    文本
  </W2Badge>
  <w2Badge :value="12" type="primary" class="item">
    数字
  </w2Badge>
  <W2Badge value="hot">
    文本
  </W2Badge>
</template>

<style scope>
.item {
  margin-right: 40px;
}
</style>
```

:::

## 最大值

自定义最大值，由`max`属性决定。请注意，仅在值为`Number`时起作用。

:::demo

```vue
<template>
  <W2Badge :value="666" :max="99" class="item">
    comments
  </W2Badge>
</template>

<style scope>
.item {
  margin-right: 40px;
}
</style>
```

:::

## 封顶的数字
使用`is-dot`属性，通过一个小红点来标记来告知用户有新内容。

:::demo

```vue
<template>
  <W2Badge is-dot class="item">
    message
  </W2Badge>
</template>

<style scope>
.item {
  margin-right: 40px;
}
</style>
```

:::

## 数值为0时是否展示

TODO

## 动画效果

TODO

## API

TODO
