# 项目说明

**mini-tiny-vue** 是 pnpm 管理的 monorepo 项目，它演示如何最小的代码，实现支持跨 Vue2/Vue3 的组件库架构。

- demos 目录: 存放 Vue2/3 的示例工程
- internals 目录： 构建脚本及辅助插件
- packages 目录： 组件源码
  - renderless: 组件逻辑
  - theme: 组件样式
  - vue : 组件模板
  - vue-common: 适配层

# 项目启动

- 将代码克隆到本地之后，执行`pnpm install` 安装依赖
- 运行 `pnpm build`, 会将组件编译到 `demos` 的相应位置
- 运行 `pnpm dev2`, 启动 Vue2 的演示工程
- 运行 `pnpm dev3`, 启动 Vue3 的演示工程

# 课后练习

本次 DTT 技术公开课上，留了 2 道课后练习，完成练习的开发爱好者，可以收到 DTT 寄去的奖品哟！

题目 1： 开发一个 `Alert` 组件

- 要求使用`mini-tiny-vue`的组件规范进行开发，模板，逻辑，样式要分别写在正确的位置
- 要求实现`type` 属性和 `close` 的功能

题目 2： 开发一个`Rate`组件

- 要求使用`mini-tiny-vue`的组件规范
- 要求实现`modelValue`双向绑定，鼠标移入效果以及选择后，触发 `change`事件。

**开发完组件后，记得在 demos 中的页面上，使用一下你的新组件，一并提交哟**

# 提交办法

向本仓库提交`pr` 即可，记得备注上自己的联系方式。

# 问题、建议反馈

在 `Issues` 中反馈即可！
