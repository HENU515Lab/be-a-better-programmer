#  简易的 Markdown 解析器

## 目的

学习`正则表达式`、`文件 IO` 等相关内容，编写`简易的 Markdown 解析器`。

##　具体要求

编写程序，解析群文件新发放的 test.md 文件，将 Markdown 格式的图片和超链接转换成 HTML 格式。

首先，你需要使用`正则表达式`在文件中筛选定位到 Markdown 格式的图片和超链接。

然后，将图片和超链接的路径获取出来并转换为 HTML 格式。

例如将以下 markdown 格式文本转换成带有 `<a>` 和 `<img>` 标签的 HTML 形式：

```text
[issues](https://github.com/seriouszyx/Awesome-tools/issues)
![top](https://i.loli.net/2018/11/06/5be16fc176ed8.jpg)
```

转换完成之后，生成新的 HTML 文件，双击打开该 HTML 文件后，图片和超链接均可以在网页上得到显示。

> 展示编程思路，撰写文章发布在 CSDN 上。

##　补充

本次作业不限制编程语言，你可以使用熟悉的 JavaScript，也可以使用你感兴趣的语言，比如 Java、PHP、Python、C++ 等。

作业在**3月1日**前完成，本次作业完成后公布考核分，选定18级组长、副组长，并开始计划分组。
