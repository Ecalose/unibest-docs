# 代码块

`VS Code` 的 `Code Snippets` 代码块可以大大加快 `vue` 文件页面结构的生成。

## `v3` 代码块

在新建的 `vue` 文件中输入 `v3` 即可触发代码块，操作 `gif` 如下:

![snippets3](./gifs/snippets3.gif)

## 代码块配置

除了 `v3` 代码块，我们还可以添加 `te` (template) 代码块，`sc` (script) 代码块，`st` (style) 代码块。

代码块完整配置如下：

:::code-group

```json [.vscode/vue3.code-snippets]
{
  "Print unibest Vue3 SFC": {
    "scope": "vue",
    "prefix": "v3",
    "body": [
      "<route lang=\"json5\" type=\"page\">",
      "{",
      "  style: { navigationBarTitleText: '$1' },",
      "}",
      "</route>\n",
      "<template>",
      "  <view class=\"\">$2</view>",
      "</template>\n",
      "<script lang=\"ts\" setup>",
      "//$3",
      "</script>\n",
      "<style lang=\"scss\" scoped>",
      "//",
      "</style>\n"
    ]
  },
  "Print unibest style": {
    "scope": "vue",
    "prefix": "st",
    "body": ["<style lang=\"scss\" scoped>", "//", "</style>\n"]
  },
  "Print unibest script": {
    "scope": "vue",
    "prefix": "sc",
    "body": ["<script lang=\"ts\" setup>", "//$3", "</script>\n"]
  },
  "Print unibest template": {
    "scope": "vue",
    "prefix": "te",
    "body": ["<template>", "  <view class=\"\">$1</view>", "</template>\n"]
  }
}
```

:::
