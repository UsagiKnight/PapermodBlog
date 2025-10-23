+++
title = "Markdown 语法测试文章"
author = "Usagi"
date = "2025-10-23"
tags = [ "Hugo", "PaperMod", "教程", "分类法" ]
[cover]
image = "https://images.unsplash.com/photo-1760648149145-560e619098ef?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1740"
alt = "text"
relative = false
[params]
ShowShareButtons = true
+++

# 1. 标题测试 (Heading Test)

## H2 次级标题
### H3 三级标题
#### H4 四级标题

---

# 2. 文本格式 (Text Formatting)

这是普通文本，用于测试字体的**粗体** (`**粗体**`) 和*斜体* (`*斜体*`)。

你也可以使用组合：***粗斜体*** (`***粗斜体***`)。

还有 ~~删除线~~ (`~~删除线~~`)。

如果要测试行内代码：你可以使用 `` `npm install hexo-cli -g` `` 来安装 Hexo 命令行工具。

# 3. 列表 (Lists)

**无序列表 (Unordered List):**

* 项目 A
    * 子项目 A.1
    * 子项目 A.2
* 项目 B

**有序列表 (Ordered List):**

1.  第一步：准备环境
2.  第二步：安装 Hexo
3.  第三步：启动服务器

# 4. 代码块 (Code Blocks)

**标准代码块 (Standard Code Block):**

```bash
hexo clean
hexo generate
hexo deploy
```