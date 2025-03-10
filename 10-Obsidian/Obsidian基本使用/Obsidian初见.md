---
uid: 20230427170309
title: Obsidian 初见
description: 
author: OS
type: other
draft: false
editable: false
modified: 20230427170350
---

# Obsidian 初见

## 一些误解，一些担忧

相信来到这里的朋友，都是被网上视频、文章、同学/老师的各种美观、高效的黑科技所安利的。

放心没有错，Obsidian 确实可以做到这些，没有任何过度宣传，甚至说现在市面上的介绍，也只是 Obsidian 的冰山一角，它能做到的远比你想象的更多。

当然这需要你具有一点探索和动手能力。这个动手能力 ≠ 编程，很多时候因为网上教程的版本和细致程度，导致很多人以为这些都需要自己学习编程，放心，我们致力于解决于此问题

项目别人的效果？只有有合适的文档，当你了解 [[03、Obsidian 的目录结构]]，[[Obsidian 社区插件]] 后，这些都是同通过插件安装、勾选配置、或者黏贴别人的配置来实现，请不要看到 CSS 或者代码片段，就感到害怕，做为本库的作者之一，我最初也是和你一样的。

简单来说，这也是我们几个小伙伴设计这个保姆教程的初衷：

- 希望帮助所有人顺利渡过 Ob 的新手期
	- 可能你是个连电脑基本操作都不会的小白，没关系。欢迎你，如果文档有任何不明确之处，欢迎反馈给我们。
	- 可能你不了解 OB 的各种使用，没关系。如果你看到好的操作，心痒痒的，欢迎反馈到这里，我们增加对应的教程。
- 希望每个人在这里摸索出自己笔记和知识的沉淀方法
	- 这里有插件的使用手册
	- 也有国内外社区，最优秀的 Showcase

如果你还是感觉很难，已经有了畏惧心理，深呼一口气，就当作它是一个浏览器，记事本，很多操作的体验和方法都很相似。

## 简约

Obsidian 第一眼，嗯~简约，十分简约，但这份简约背后，是蕴含了开放性的各种可玩性。

- 忘掉 其他笔记 依赖网络的卡顿，我们支持**本地存储**，**全平台客户端支持**；
- 忘掉 其他笔记 那些固定的模块，我们**支持丰富的自定义**，社区贡献了**各种样式和功能**
- 忘掉 其他笔记 只能和自身联动的窘境，我们支持工作流，社区贡献和多种软件联动方式，我们 **All in ONE**

## 美观

完全可以，Obsidian 开放的特性，让它具有比市面上很多软件都更好的扩展性。

丰富的插件数量，支持 CSS。你甚至可以当作它是一个简易的网页制作工作。

当然一切这些，需要你有一定的动手能力，不过不用担心，我们的教程就是为了让你在这里学习后，设置出各种与众不同的 OB 效果。让你的笔记只为你而美丽。

## 可玩性高

你可以理解 Obsidian 是一个类似 Chrome 或者 Edge 的浏览器。

但它具有和你的浏览器一样丰富的扩展性（官方上架近 800 个插件），非官方可能更多。这主要依赖 Obsidian 设计原则中的 [[Obsidian 的可扩展性]]

你可以通过 设置 > 第三方插件 > 关闭安全模式后，通过访问 社区插件市场，来浏览下载社区提供的插件，这和你在 Chrome、Edge 中所作的事情一样；详见：[[Obsidian 社区插件]]


## Obsidian 设计模式和基本原则

### Obsidian 的本地化

在国内很多软件都是云端模式为主，会员付费大行其道的时代，这个软件坚持了本地化思路。

我们不好猜测这样设计的初衷，原作者们经历了如何激烈而又富有想象力的讨论。

但我们从”知识“一词出发，可以管中窥豹下。

知识是一个偏向个人私密领域的话题，每个人都会有自己的知识体系，无论它是否完整，健全，是否高效。那么这样的知识显然最开始都是停留在你的脑中，他人无法窥得的。那么自然就延伸出来知识的整理收集可能也是偏向隐私性的，需要的是牢靠的本地，才能安心。

知识的获取和整理，显然可以是一个专门的流式工作方法。从收集->整理->沉淀 的过程，这一过程中，除了收集，可能不受限于设备外。其他两个环节自然式不依赖网络，本地化的随时整理，显得格外高效。

所以 Obsidian 也提供了一个所有功能近乎免费。

### Obsidian 的可扩展性

由于和你的浏览器有相似的内核，所以 Obsidian 也支持丰富的扩展能力，或者我们可以说这是一种[[Obsidian 的插件机制]]。

这样的设计，保证了每个用户拿到的 Obsidian 都是最基本可用，保证了笔记的输入和记录基本功能。又提供了丰富的可玩性，每个人可以根据自己的喜好，寻找不同的插件，来搭建完善自己的笔记/个人知识管理系统

#### 核心插件

这是由 Obsidian 官方提供并维护的插件，Obsidian 最强大的方面之一是通过插件机制，添加新功能的能力。除了基本输入输出歪，官方自己出品的功能，都采用了插件机制，如果你不喜欢，可以在 设置 > 核心插件 中，寻找对应共功能并关闭。

#### 社区插件

官方已经有近 800 个社区扩展在架，正在开发和在试用期的插件，可能要超过1000个。

这些插件涉及到了方方面面，如果你对他们想了解他们，可以查看这里[[Obsidian 插件分类大全]]

## Obsidian 的跨平台性

Obsidian 一个很大的特点就是 **跨平台** 。 

这就方便你无论是在 办公桌前进行文字编辑；还是在沙发上浏览内容；或者是随手打开手机，都可以快速检索和编辑你的个人知识库。

> [!Note]+
> Obsidian 基于 Electron 开发构建，可以兼容 Windows ， Mac 以及 Linux 平台。
> Electron 基于 Chromium ， Nodejs ，这就让你可以用 [[HTML]]、[[CSS]]、[[JavaScript]] 构建应用。 

## Obsidian 的模块化

虽然这个听起来像是一个技术术语

>[!note]
>模块化是指解决一个复杂问题时自顶向下逐层把系统划分成若干模块的过程，有多种属性，分别反映其内部特性。

但实际上当您了解和熟悉 Obsidian 后，你会发现在用户交互和一些设计的巧思上。OB 尽可能保持了模块化特色。

比如灵活的[[面板布局]]、[[Obsidian 社区插件]]等等。

基于这样的特性，让 OB 的工作区组织更加灵活，每个人都可以根据自己的喜好来规划自己的工作区，以适应不同环境下的工作。


## Obsidian 的安装

### 官方安装包获取途径

Obsidian 的官方网站
http://obsidian.md
在这里网站会根据你的系统不同，判断你要下载的安装包

-   Obsidian官方网站：[https://obsidian.md/open in new window](https://obsidian.md/)
-   **官方发布：**[Obsidian 安装包open in new window](https://thoughts.teambition.com/share/62a131711a6baa00416a79d3#title=Obsidian_%E5%AE%89%E8%A3%85%E5%8C%85) 各平台版本、各个历史版本
-   **官方发布：** 安卓版安装包：[安卓版 (lanzoue.com)open in new window](https://wwdx.lanzoue.com/b030yr97g) 密码：9lj5
-   iOS版本：直接是应用市场搜索`obsidian`下载

### 移动端安装

安卓端 App 现已公开，下载方式可见[官方的网站](https://obsidian.md/mobile)
iOS App，可以在 Appstore 中搜索并安装。

### Obsidian 都支持哪些操作系统

- 个人电脑（台式机、笔记本电脑）：支持 Windows、Mac
- 移动端：Android（安卓手机）、iOS（iPhone，苹果手机）
- 其他：Linux

## 创建仓库

1. 安装完毕后，打开软件后，因为没有仓库，所以 Obsidian 会弹出初次创建页面。
2. 你可以选择创建全新的仓库（可以理解为工作区或者笔记本，空间）
3. 如果你之前下载过别人的示例库，或者其他基于 Markdown 笔记，也可以选择打开对应目录，作为自己的笔记。
![Pasted image 20230221095904](Resource/Images/12f857bad1199159f04e587690b3b8ee_MD5.png)

## 如何设置界面语言

1、Obsidian 在安装时，可以选择中文进行安装
2、如果没有在安装时候选择，可以在 设置 > 关于 > 语言，选择对应你习惯的语言，选择后需要重启 Obsidian 以生效。