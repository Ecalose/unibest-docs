# 简介

<div class="md-center" style="margin-top: 20px;">

[![GitHub Repo stars](https://img.shields.io/github/stars/codercup/unibest?style=flat&logo=github)](https://github.com/codercup/unibest)
[![GitHub forks](https://img.shields.io/github/forks/codercup/unibest?style=flat&logo=github)](https://github.com/codercup/unibest)
[![star](https://gitee.com/codercup/unibest/badge/star.svg?theme=dark)](https://gitee.com/codercup/unibest)
[![fork](https://gitee.com/codercup/unibest/badge/fork.svg?theme=dark)](https://gitee.com/codercup/unibest)
![node version](https://img.shields.io/badge/node-%3E%3D18-green)
![pnpm version](https://img.shields.io/badge/pnpm-%3E%3D7.30-green)
![GitHub License](https://img.shields.io/github/license/codercup/unibest)

</div>

`unibest` 是一个 uniapp 跨端解决方案，由 `uniapp` + `Vue3` + `Ts` + `Vite4` + `UnoCss` + `VSCode`(可选 `webstorm`) 实现。它使用了最新的前端技术栈，无需依靠 `HBuilderX`，通过命令行方式运行 `web`、`小程序` 和 `App`。

`unibest` 内置了 `约定式路由`、`layout布局`、`请求封装`、`请求拦截`、`登录拦截`、`UnoCSS`、`i18n多语言` 等基础功能，提供了 `代码提示`、`自动格式化`、`统一配置`、`代码片段` 等辅助功能，让你编写 `uniapp` 拥有 `best` 体验 （ `unibest 的由来`）。

## ✨ 特性

- ⚡️ [Vue 3](https://github.com/vuejs/core), [Vite](https://github.com/vitejs/vite), [pnpm](https://pnpm.io/), [esbuild](https://github.com/evanw/esbuild) - 就是快！
- 🔥 最新语法 - `<script lang="ts" setup>` 语法
- 🎨 [UnoCSS](https://unocss.dev/) - 高性能且极具灵活性的即时原子化 CSS 引擎
- 😃 [UnoCSS Icons](https://unocss.dev/presets/icons) & [icones](https://icones.js.org/) - 海量图标供你选择
- 🍍 [pinia](https://pinia.vuejs.org/) & [pinia-plugin-persistedstate](https://prazdevs.github.io/pinia-plugin-persistedstate/zh/guide/) - 全端适配的全局数据管理
- 🗂 `uni.request` 请求封装 - 一键引入，快捷使用
- 🗂 `路由拦截` 基础封装，支持扩展，快捷使用，拒绝黑盒
- 📦 `组件自动化加载` - 可配置化的组件加载方式，轻松加载组件
- 📥 [API 自动加载](https://github.com/antfu/unplugin-auto-import) - 直接使用 Composition API 无需引入
- 🎉 `v3` Code Snippets 加快你的页面生成
- 🦾 [TypeScript](https://www.typescriptlang.org/) & [ESLint](https://eslint.org/) & [stylelint](https://stylelint.io/) - 保证代码质量
- 🌈 [husky](https://typicode.github.io/husky/) & [lint-staged](https://github.com/lint-staged/lint-staged) + [commitlint](https://commitlint.js.org/) - 保证代码提交质量
- 💡 `ES6 import` 自动排序，`css 属性` 自动排序，增强编码一致性

- 🖥 `多环境` 配置分开，想则怎么配置就怎么配置

## 👍 实用功能

- [x] 页面下拉刷新（全局+局部）
- [x] 页面上拉加载
- [x] 路由拦截
- [x] 请求拦截
- [x] 页面离开前拦截
- [x] 页面离开后，旧页面的弹窗还出现 BUG
- [x] 导航栏返回 or 去首页
- [x] 导航栏渐变（微信+h5+App)
- [x] 自定义导航栏顶部机型适配
- [x] 微信小程序分享（好友+朋友圈）
- [x] 微信登录
- [ ] 非微信登录（h5 和 App)
- [ ] 微信一键登录（基于手机号）- 需要非个人认证用户
- [x] 微信小程序获取头像昵称+隐私协议
- [x] 微信小程序 vconsole 调试
- [x] 多语言模板
- [x] 页面悬浮球(floating bubble)
- [x] 多 tab 列表功能
- [x] 瀑布流
- [x] 大转盘抽奖
- [x] 九宫格抽奖
- [ ] 登陆模板（APP）
- [ ] 登陆模板（H5）

::: tip

问：为什么 `UI库` 从 `uv-ui` 改为了 `wot-ui` ？

答：`wot-ui`(`wot-design-uni`) 是 `vue3 + ts` 开发的 `UI库` ，[wot-design-uni 官网链接](https://wot-design-uni.gitee.io/)。

UI 选型文章请看 [【unibest】 uniapp + vue3 模板 UI 框架选型](https://juejin.cn/spost/7337513012393607207).

:::

## 各端产物

![Alt text](image.png)
