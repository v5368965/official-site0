---
title: "Markdown极简教程"
---

:::tip 提示

本内容为**新手可选项**，但是，强烈推荐学习一下，我们的文档都是用Markdown语法书写的，可以非常容易的形成格式统一，美观的内容，其实内容很简单，刚开始会需要记忆语法，随着使用率越来越高，会很容易记住。
:::

:::info 信息

[视频](https://www.bilibili.com/video/BV1Ho4y1v79V/?vd_source=4a888db8814702b2062fcaf2575be745)
:::

本文以：[Typora](https://store.lizhi.io/site/products/id/520)（收费软件） 进行演示

> 这里有一个在win10下使用（其他windows版本没有测试过）的[Typora1.1.5版本](https://pan.baidu.com/s/1c8p_YKFGHxZIrf0jheY-gA?pwd=4321)（不是最新版）解密版，有需要的可自行下载

后面开始使用VSCode也可以使用VSCode编写Markdown（免费软件）

Ctrl + / 可以快速在Markdown预览模式与源码模式之间切换（视频中后面会有解释）

## 1.标题

\# 一级标题

# 一级标题

\## 二级标题

## 二级标题

\### 三级标题

### 三级标题

直至 六级标题

## 2.列表

### 2.1.无序列表（无序号）

\- + 空格 + 内容

\- 无序列表项1

- 无序列表项1

\- 无序列表项2

- 无序列表项2

### 2.2.有序列表（有序号）

数字 + 空格 + 内容

1. 有序列表项1
2. 有序列表项2
3. ...

## 3.引用

\> 内容

> 引用

## 4.任务列表

**任务列表稍微复杂一点：\- + 空格 + [ ] + 空格**

\- [ ]

- [ ]

## 5.代码块

\``` 按哪种编程语言显示

内容

\```

```python
print("小白慢爬营")
```

对于行中文字进行标识，通常用两个 \`将文字包裹，如：\`文字\`。

## 6.超链接

\[链接名](链接)

[Github About](https://github.com/about)

## 7.图片

\!\[链接名](链接)

![](https://github.githubassets.com/images/modules/site/about/octocats.webp)

---
---

# Markdown超简教程

## 1.为什是（什么是）Markdown？

你觉得[这样](https://github.com/coding-newbies-group/programming-co_creation-docs/blob/main/docs/p1/p1-12-array.md)的排版样式如何？

实际上我们[如何写](https://github.com/coding-newbies-group/programming-co_creation-docs/blob/main/docs/p1/p1-12-array.md?plain=1)出这样排版的内容？

Markdown可以让我们专注于内容本身，而不是花费过多精力在格式和排版上。

**特定的写法，会被特定的显示。**

## 2.哪些平台支持Markdown？

Markdown是一种纯文本格式，意味着无论是在Windows、Mac还是Linux系统中，几乎所有的文本编辑器和阅读器都能够良好支持。不必担心文档在不同平台上的兼容性问题，Markdown可以让您的文本内容在各种环境下保持一致的格式。

下面的回答来自AI，未一一验证，欢迎勘误。

> 1. 博客平台：
>    - 简书（[www.jianshu.com](http://www.jianshu.com))
>    - CSDN（[www.csdn.net](http://www.csdn.net))
>    - 掘金（[juejin.cn](https://juejin.cn)）
>    - segmentfault（[segmentfault.com](segmentfault.com)）
>    - 哔哩哔哩（[bilibili.com](segmentfault.com)）的个人空间
> 2. 社区和论坛：
>    - V2EX（[www.v2ex.com](http://www.v2ex.com))
>    - 思否（[segmentfault.com](segmentfault.com)）
>    - 少数派（[sspai.com](sspai.com)）
>    - 中国大学MOOC（[www.icourse163.org](http://www.icourse163.org))
> 3. 内容管理系统（CMS）：
>    - WordPress（[zh-cn.wordpress.org](zh-cn.wordpress.org)）
>    - Typecho（[typecho.org](typecho.org)）
>    - Hexo（[hexo.io](hexo.io)）
>    - Ghost（[zh.ghost.org](zh.ghost.org)）
> 4. 在线协作工具：
>    - 腾讯文档（[docs.qq.com](docs.qq.com)）
>    - 语雀（[www.yuque.com](http://www.yuque.com))
>    - Teambition（[www.teambition.com](http://www.teambition.com))
>    - 印象笔记（[www.yinxiang.com](http://www.yinxiang.com))
> 5. 开发者社区和知识库：
>    - GitHub（github.com）的README.md文件、Issues等
>    - 开源中国（[www.oschina.net](http://www.oschina.net))
>    - 老鸟程序员（[www.laoniuprogram.com](http://www.laoniuprogram.com))

## 3.如何学习Markdown？

* 看教程
* 直接用——完。

## 4.常用Markdown语法

### 4.1.标题

语法：`#` + `空格` + `标题内容`，连续#号的数量代表标题级别。

例子：

```
# 一级标题
```

# 一级标题

```
## 二级标题
```

## 二级标题

```
### 三级标题
```

### 三级标题

直至 六级标题

### 4.2.列表

### 4.2.1.无序列表（无序号）

语法：`-` + `空格` + `内容`

例子：

```
- 无序列表项1
```

- 无序列表项1

```
- 无序列表项2
```

- 无序列表项2

### 4.2.2.有序列表（有序号）

语法：`数字` + `.` + `空格` + `内容`

例子：
```
1. 有序列表项1
```
1. 有序列表项1
```
2. 有序列表项2
```
2. 有序列表项2

### 4.3.引用

语法：`>` + `引用内容`

例子：

```
> 引用内容
```

> 引用内容

### 4.4.任务列表

语法：`-` + `空格` + `[` + `空格` + `]` + `空格` 

例子：

```
- [ ] 
```

- [ ] 

对于任务列表，可以进行勾选，如：

- [x] 

### 4.5.代码

用于把内容放到一个灰色底纹的格子里，通常用于在正文中放`代码`或`命令`的内容。

语法：\` + 空格 + \` 

例子：

```
在Windows的命令行工具Windows PowerShell中，可以通过命令``获取当前路径下有哪些文件及文件夹。
```

在Windows的命令行工具Windows PowerShell中，可以通过命令`Get-ChildItem`获取当前路径下有哪些文件及文件夹。

### 4.6.代码块

语法：在一对儿，三个反引号\```之间，包裹代码；第一个 三个反引号\```后面+`空格`+`编程语言的名字`，将按此编程语言的配色显示该代码。

例子：

~~~javascript
``` javascript

console.log("小白慢爬营")

```
~~~

```python
console.log("小白慢爬营")
```

### 4.7.超链接

语法：`[` + `链接名` + `]` + `(` + `链接` + `)`

例子：

```
[Github About](https://github.com/about)
```

[Github About](https://github.com/about)

### 4.8.图片

语法：`!` + `[` + `图片名` + `]` + `(` + `链接` + `)`

例子：

```
![](https://raw.githubusercontent.com/vwumumu/images/master/octocats.webp)
```

![](https://raw.githubusercontent.com/vwumumu/images/master/octocats.webp)

图片名可以为空，图片链接将在支持Markdown语法的工具中显示为该链接所代表的图片。