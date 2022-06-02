---
title: Markdown的一些注解
categories: Markdown
tags: 
- Markdown
---
Markdown中对html的引用(html不参与编译过程，只是单纯的展示)：
例如对于\<li>..\<li>进行展示，只需要对源文件中的\<前加上\即可。因为Markdown文件对于>没有特殊歧义。
如果要对大量html文件进行展示，在vscode中进行ctrl+F，ctrl+alt+enter全部查找和替换即可
最后效果如下：

>\<html>..\</html> 是网页的根元素
>\<head>..\</head> 元素包含了文档的元（meta）数据