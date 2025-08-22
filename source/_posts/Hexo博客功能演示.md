---
title: Hexo博客功能演示
date: 2025-04-14 14:00:00
tags: [Hexo, 教程, Markdown, 功能演示]
categories: [教程, 功能演示]
---

# Hexo博客功能完整演示

这篇文章将展示Hexo博客的所有主要功能，包括文本格式化、图片插入、代码展示、分类和标签等。

## 1. 文本格式化

### 标题层级
使用 # 号可以创建不同层级的标题：
# 一级标题
## 二级标题
### 三级标题

### 文字样式
- **粗体文字**：使用两个星号包裹
- *斜体文字*：使用一个星号包裹
- ~~删除线~~：使用两个波浪线包裹
- `行内代码`：使用反引号包裹

### 列表
有序列表：
1. 第一项
2. 第二项
3. 第三项

无序列表：
- 项目一
- 项目二
- 项目三

## 2. 代码展示

### JavaScript代码
```javascript
function hello() {
    console.log('Hello, Hexo!');
    return 'Welcome to my blog';
}
```

### Python代码
```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)
```

## 3. 图片展示

### 网络图片
![Hexo Logo](https://hexo.io/icon.svg)

### 本地图片
（注意：需要先将图片放在source/images目录下）
![本地图片示例](/images/example.jpg)

## 4. 表格

| 功能 | 描述 | 示例 |
|------|------|------|
| 标题 | 使用#号 | # 标题 |
| 列表 | 使用-或* | - 项目 |
| 代码 | 使用``` | ```代码``` |

## 5. 引用

> 这是一段引用文字
> 可以包含多行
> 使用 > 符号开头

## 6. 链接

- [Hexo官网](https://hexo.io)
- [Markdown教程](https://www.markdownguide.org)

## 7. 分类和标签

这篇文章使用了以下分类和标签：
- 分类：教程、功能演示
- 标签：Hexo、教程、Markdown、功能演示

## 8. 数学公式

使用LaTeX语法：
$$
E = mc^2
$$

行内公式：$\sum_{i=1}^n i = \frac{n(n+1)}{2}$

## 9. 注意事项

1. 图片建议使用图床服务
2. 代码块要指定语言
3. 保持文章结构清晰
4. 适当使用分类和标签

希望这个演示对你有所帮助！
