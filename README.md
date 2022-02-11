由于[原作者](https://github.com/xiaomuzhu)不维护了，所以自己修改进行保存方便日后回顾

建议选择基于VuePress的在线文档阅读方式: https://xypisces.github.io/

## 目录

- [目录](#目录)
  - [前言](#前言)
  - [面试技巧](#面试技巧)
  - [推荐书籍](#推荐书籍)
  - [前端基础](#前端基础)
  - [前端笔试](#前端笔试)
  - [前端原理](#前端原理)
  - [计算机基础](#计算机基础)
  - [数据结构与算法](#数据结构与算法)
  - [前端框架](#前端框架)
  - [框架原理](#框架原理)
  - [UI组件](#ui组件)
  - [性能优化](#性能优化)
  - [工程化](#工程化)
  - [工程化原理](#工程化原理)
  - [前端安全](#前端安全)
- [说明](#说明)
  - [关于读者](#关于读者)
  - [关于内容](#关于内容)
  - [关于后续](#关于后续)

### 前言

* [项目阅读指南](docs/guide/README.md)
* [为什么会有这个项目](docs/guide/preface.md)

### 面试技巧

* [面试官到底想看什么样的简历？](docs/guide/resume.md)
* [面试回答问题的技巧](docs/guide/project.md)
* [如何通过HR面](docs/guide/hr.md)

### 推荐书籍

* [书籍推荐](docs/guide/book.md)

### 前端基础

* [前端基础](docs/guide/htmlBasic.md)
* [CSS基础](docs/guide/cssBasic.md)
* [JavaScript基础](docs/guide/jsBasic.md)
* [浏览器面试题](docs/guide/browser.md)
* [DOM面试题](docs/guide/dom.md)

### 前端笔试

* [HTTP笔试部分](docs/guide/httpWritten.md)
* [书籍推荐](docs/guide/book.md)

### 前端原理

* [JavaScript的『预解释』与『变量提升』](docs/guide/hoisting.md)
* [Event Loop详解](docs/guide/eventLoop.md)
* [实现不可变数据](docs/guide/immutable.md)
* [JavaScript内存管理](docs/guide/memory.md)
* [实现深克隆](docs/guide/deepclone.md)
* [如何实现一个Event](docs/guide/event.md)
* [JavaScript的运行机制](docs/guide/mechanism.md)

### 计算机基础

* [HTTP面试题](docs/guide/http.md)
* [TCP面试题](docs/guide/tcp.md)

### 数据结构与算法

* [算法面试题](docs/guide/algorithm.md)

### 前端框架

* [关于前端框架的面试须知](docs/guide/framework.md)
* [Vue面试题](docs/guide/vue.md)
* [React面试题](docs/guide/react.md)

### 框架原理

* [虚拟DOM原理](docs/guide/virtualDom.md)
* [Proxy比defineproperty优劣对比?](docs/guide/devsProxy.md)
* [setState到底是异步的还是同步的?](docs/guide/setState.md)
* [前端路由的实现](docs/guide/router.md)
* [redux原理全解](docs/guide/redux.md)
* [React Fiber 架构解析](docs/guide/fiber.md)
* [React组件复用指南](docs/guide/abstract.md)
* [React-hooks 抽象组件](docs/guide/reactHook.md)

### UI组件

* [如何搭建一个组件库的开发环境](docs/guide/componentCli.md)
* [组件设计原则](docs/guide/component.md)
* [实现轮播图组件](docs/guide/carousel.md)

### 性能优化

* [前端性能优化-加载篇](docs/guide/load.md)
* [前端性能优化-执行篇](docs/guide/execute.md)

### 工程化

* [webpack面试题](docs/guide/webpack.md)
* [前端工程化](docs/guide/engineering.md)

### 工程化原理

* [如何写一个babel](docs/guide/ast.md)
* [Webpack HMR 原理解析](docs/guide/WebpackHMR.md)
* [webpack插件编写](docs/guide/webpackPlugin.md)
* [webpack 插件化设计](docs/guide/webpackPluginDesign.md)
* [Webpack 模块机制](docs/guide/webpackMoudle.md)
* [webpack loader实现](docs/guide/webpackLoader.md)
* [如何开发Babel插件](docs/guide/babelPlugin.md)

### 前端安全

* [前端安全面试题](docs/guide/security.md)

## 说明

### 关于读者

本项目一开始并没有要做一个仅仅面向面试的项目,而是希望借助面试的形式进一步巩固、完善自身的知识，同时为初学者提供一个参考路径。


### 关于内容

本项目的主要内容来源由三部分组成:

* 作者手打: 主要搜集了近几年的主流面试题,并针对每个面试题进行回答
* 作者之前的博客: 部分比较长篇的原理详解来源于作者之前的博客内容
* 转载: 一些面试题在网上已经有非常好的对应文章,没有必要进行二次创作,因此作者按照转载规范进行了转载,如有侵权立即删除

### 关于后续

本项目的主体内容基本完成,但是依然缺乏校审和拓展内容,例如[JavaScript的运行机制](docs/guide/mechanism.md)这篇文章虽然是作者花费了大量精力完成的,主要参照的就是[ECMA规范](https://www.ecma-international.org/publications/standards/Ecma-262.htm),但是经过反复考证依然无法保证作者理解的规范是否正确,而且在网络上搜索不到基于最新规范的文章与作者的文章对应,所以需要更多的人参与进来来验证文章的正确性.

面试题部分作者分为了七大模块,虽然大体完成了,但是依然有几个重要的模块需要打磨:

* 数据结构与算法: 这部分仅仅列举了一些非常常见的查找、排序算法，还没有更深入的讲解,也缺少数据结构部分的内容
* TypeScript: 这部分我另开了一个项目,已经脱离面试的范畴了,更像是一本深入浅出的手册,但是只完成了一半
* 细分领域: 这部分其实难度更大一些,如果说上述各部分属于前端范畴的通用知识的话,这部分就更加专业化也更加细分,也是我认为的前端岗位未来的进化方向,由于可视化和图形这两个领域相对更冷门、专业化程度更高,所以排期更靠后,我们会优先更新移动端和Node的内容,也欢迎各个领域的专业开发者贡献内容

当然,除此之外其他已经完成的内容难免有需要补充和拓展的地方.

