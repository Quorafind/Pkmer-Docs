---
uid: 20230513221420
title: Obsidian 插件：Custom State For Task List 优化你的任务样式
description: Obsidian 插件：Custom State For Task List 优化你的任务样式
author: Bon
type: other
draft: false
editable: false
modified: 20230514131237
---

# Obsidian 插件：Custom State For Task List 优化你的任务样式

## 概述

Obsidian 本来已经有很多种利用任务标签符号，来添加不同的待办任务样式的插件，例如 Minimal 主题就自带了各种特殊的状态：`- [>]` 、`- [-]`、`- [!]` 等，诸如此类的样式能让我们在使用待办任务的时候，根据任务的不用状态有更多适用场景（除了完成，未完成，有时候还有疑问，停止等状态）。

这个插件的主要作用则是更进一步加强了这个自定义的效果，你能用插件来实现更多的自定义样式。

> [!Note] 插件名片
> - 插件名称：Custom State for Task List
> - 插件作者：Okami Wong
> - 插件说明：自定义任务状态样式。
> - 插件项目地址：[点我跳转](https://github.com/OkamiWong/obsidian-custom-state-for-task-list)

## 效果&特性

![image.png](https://cdn.pkmer.cn/images/20230514130843.png!pkmer)

## 使用

- 在你开启插件以后，你可以先到设置添加或者删除其默认存在的一些设置。
- 在你确定好哪个文本对应哪个样式以后，你就可以回到自己的笔记中，写入对应的内容（以下是一个对应的样例）：

假设我们预设了 doing 为 🎉，那 `- [doing]` 在**渲染模式**下就会转变成 `🎉` ，

```markdown
- [doing] 这是一个 Doing 的任务，其在渲染模式下就会变成下边的样子：

🎉 这是一个 Doing 的任务，其在渲染模式下就会变成下边的样子
```

  - 你每次更新了任务标签后，需要重新开关阅读和编辑模式使其生效。

![image.png](https://cdn.pkmer.cn/images/20230514130402.png!pkmer)

### 预设内容

- 插件提供了一些预设内容
	- `committed` ➡ 📌
	- `doing` ➡ 🚧
	- `deferred` ➡ 😴
	- `removed` ➡ 🗑

>[!Tip] 提示
>- 任务标签内的内容不支持中文，需要使用 doing，removed 这样的英文单词或者字符。