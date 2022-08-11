---
title: LiteFlowX IDEA Plugin
date: 2022-07-12 00:57:00
permalink: /pages/liteflowx/
author:
 name: 码农小易
 link: https://gitee.com/liupeiqiang/
---

:::warning Notice
- The LiteFlowX plugin version from `v1.0.0` will no longer support the features of LiteFlow `2.7.X` and below.

- If you are using an older version of the LiteFlow framework, please [download the plugin jar package](https://gitee.com/liupeiqiang/LiteFlowX/releases/0.1.1) to install it yourself.

- The plugin will focus on making changes and improvements to the latest version of the LiteFlow framework in the future. Please make sure you are using the latest LiteFlow framework before using this plugin.
:::

![封面](/img/liteflowx/cover.jpg)

LiteFlowX is an IDEA plugin that can greatly improve your work efficiency when developing with the LiteFlow framework.

<p align="left">

<a href="https://www.github.com/Coder-XiaoYi/LiteFlowX" target="_blank">
<img class="no-zoom" src="https://img.shields.io/badge/Github-blue?logo=github&logoColor=white&style=for-the-badge"/>
</a>

<a href='https://gitee.com/liupeiqiang/LiteFlowX/' target="_blank">
<img class="no-zoom" src="https://img.shields.io/badge/Gitee-red?logo=gitee&logoColor=white&style=for-the-badge"/>
</a>

</p>

::: tip 😋 Support project
The LiteFlowX plug-in is completely free and open source. In order to allow you to use better plug-in functions, you can file issues in the warehouse!

If the plugin is easy to use, please give this plugin a [five-point praise](https://plugins.jetbrains.com/plugin/19145-liteflowx/)!

If the plugin source code is helpful for your development, please [point a star](https://www.github.com/Coder-XiaoYi/LiteFlowX) for this repository!
:::

## 🍬 LiteFlowX Features

::: cardList 3
```yaml
- name: Support ELF syntax
  desc: Autocomplete, syntax highlighting, lexical analysis
  bgColor: '#F0DFB1'
  textColor: '#242A38'
- name: Syntax injection
  desc: ELF syntax is automatically injected into the chain of .el.xml
  bgColor: '#718971'
  textColor: '#fff'
- name: LiteFlow Toolbox
  desc: The Component and Chain of the project project are very clear
  bgColor: '#DFEEE7'
  textColor: '#2A3344'
```
:::

- Support LiteFlow 2.8.x new regular expression syntax (auto-suggestion, syntax highlighting, syntax detection)
- Specific file Svg icons for easy identification of LiteFlow elements
- Able to identify Component, Chain
- Java code and Chain jump to each other
- Jump between Xml files and LiteFlow elements
- Provide LiteFLow toolbox, Component and Chain of the whole project, and support double-click jump
- Support file jump to liteflow.ruleSource property
- ...more features to come

## 🎉 Install LiteFlowX
There are three ways to install the LiteFlowX plugin into IDEA
::: tip
Versions that support the LiteFlowX plugin are:
- IntelliJ IDEA Educational — 2020.1 — 2022.1.2
- IntelliJ IDEA Ultimate — 2020.1 — 2022.1.3
- IntelliJ IDEA Community — 2020.1 — 2022.1.3
:::
### Method 1: Click here to install (recommended)

After the page is loaded, an install button will appear below

<iframe frameborder="none" width="245px" height="48px" src="https://plugins.jetbrains.com/embeddable/install/19145"></iframe>

### Method 2: Install the plugin from the Marketplace (recommended)
1. Press the key combination `Ctrl + Alt + S` to open the IDE settings and select **Plugins**
2. Search `LiteFlowX` in **Marketplace** and click install

![Install via Marketplace](/img/liteflowx/installByMarketplace.png)


### Method 3: Import the JAR package for installation
1. Download the latest plugin Jar package at [Releases](https://gitee.com/liupeiqiang/LiteFlowX/releases)
2. Press Ctrl+Alt+S to open IDE settings and select **Plugins**
3. On the Plugin page, click ⚙ and then click **Install Plugin from Disk...**
4. Select the plugin downloaded in the first step and click **OK**
5. If prompted to restart the IDE, click **OK** to apply the changes

## 🌈 Demo
![智能提示ComponentChain](/img/liteflowx/chaincomponent.gif)

![预检测Chain未命名或重复](/img/liteflowx/chaindep.gif)

![自定义elf语法关键字颜色](/img/liteflowx/changecolor.gif)

![支持Component和Chain跳转](/img/liteflowx/componentjump.gif)

![支持局部变量](/img/liteflowx/localvar.gif)

![支持.el.xml的chain标签自动注入elf语法](/img/liteflowx/newelxml.gif)

![LiteFlow 工具箱](/img/liteflowx/toolbox.gif)

## 💬 Questions
### Q: Why can't the related ELF expressions be highlighted after installing the LiteFlowX plug-in?
A: First, make sure you have installed the latest version of the LiteFlowX plugin, and be sure to restart IDEA after the installation is complete. If the above operation still does not solve the problem, consider that the third-party theme you installed affects the highlighting, please go to `File -> Settings -> Editor -> Color Scheme -> General -> Code -> Injected language fragment` and tick the right Uncheck the `Foreground` checkbox and press to confirm the changes.

![无高亮解决方法](/img/liteflowx/nohighlight.png)

### Q: Why does the comment written in the expression report an error, sometimes not?
A: Pay special attention here. If you need to write comments in expressions, you can only write them before `reference components` or `ELF keywords`, as shown in the following figure.

![允许的注释](/img/liteflowx/yescomment.png)

![不允许的注释](/img/liteflowx/nocomment.png)

### Q: My problem is not resolved in the troubleshooting, what should I do?
A: The LiteFlowX plugin is still growing, and it is inevitable that you will encounter strange things during use, but it does not matter, you can [contact the author](https://gitee.com/liupeiqiang) or [Gitee repository]( https://gitee.com/liupeiqiang/LiteFlowX), put forward your valuable comments or ISSUES, and I will answer your questions as soon as possible. 💖

## 💖 List of authors
::: cardList
```yaml
- name: 铂赛东
  desc: LiteFlow author
  avatar: /img/liteflowx/avator/bryan31.webp
  link: https://gitee.com/bryan31
  bgColor: '#d7d7d7'
  textColor: '#000000'
- name: 码农小易
  desc: LiteFlowX author
  avatar: /img/liteflowx/avator/liupeiqiang.webp
  link: https://gitee.com/liupeiqiang
  bgColor: '#ffe3d8'
  textColor: '#444452'
- name: chenglitao521
  desc: Contributor
  avatar: /img/liteflowx/avator/chenglitao521.jpg
  link: https://github.com/chenglitao521
  bgColor: '#f5efbd'
  textColor: '#3d6328'
```
:::
