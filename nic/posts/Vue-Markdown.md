---
title: Vue Markdown 语法
display: home
image: https://picsum.photos/1920/1080/?random&date=2019-07-15-21
date: 2019-07-15
tags: 
  - Markdown
categories:
  - 文章
--- 
> Vue Markdown 语法

### 1. 斜体和粗体

使用 \* 和 \*\* 表示斜体和粗体。

示例：

这是 _斜体_，这是 **粗体**。

### 2. 分级标题

示例：

# h1
## h2
### h3
#### h4
##### h5
###### h6

```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

你也可以选择在行首加井号表示不同级别的标题 (H1-H6)，例如：# H1, ## H2, ### H3，#### H4。

### 3. 外链接

使用 \[描述](链接地址) 为文字增加外链接。

示例：
```
[本人博客](http://........)
```
这是去往 [本人博客](/) 的链接。

### 4. 无序列表

使用 \*，+，- 表示无序列表。

示例：

* 无序列表项 一
* 无序列表项 二
* 无序列表项 三
```
* 无序列表项 一
* 无序列表项 二
* 无序列表项 三
```

### 5. 有序列表

使用数字和点表示有序列表。

示例：

1.  有序列表项 一
2.  有序列表项 二
3.  有序列表项 三
```
1.  有序列表项 一
2.  有序列表项 二
3.  有序列表项 三
```

### 6. 文字引用

使用 > 表示文字引用。

示例：

> 野火烧不尽，春风吹又生。

```
> 野火烧不尽，春风吹又生。
```

### 7. 行内代码块

使用 \`代码` 表示行内代码块。

示例：

让我们聊聊 `html`。
```
`html`
```

### 8. 代码块

使用 四个缩进空格 表示代码块。

示例：

    这是一个代码块，此行左侧有四个不可见的空格。

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
```
    ``` js{4}
    export default {
        data () {
            return {
            msg: 'Highlighted!'
            }
        }
    }
    ```
```

### 9. 插入图像

使用 \!\[描述](图片链接地址) 插入图像。

示例：

![图标](https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80)
```
![图标](https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80)
```
### 10. 删除线

使用 ~~ 表示删除线。

~~这是一段错误的文本。~~
```
~~这是一段错误的文本。~~
```

### 11. 表格

| 项目   |   价格 | 数量 |
|--------|-------:|:----:|
| 计算机 | \$1600 |  5   |
| 手机   |   \$12 |  12  |
| 管线   |    \$1 | 234  |
```
| 项目   |   价格 | 数量 |
|--------|-------:|:----:|
| 计算机 | \$1600 |  5   |
| 手机   |   \$12 |  12  |
| 管线   |    \$1 | 234  |
```

### 12. 自定义容器

**示例**
::: tip 提示
This is a tip
:::

::: warning 注意
This is a warning
:::

::: danger 警告
This is a dangerous warning
:::

```
::: tip 提示
This is a tip
:::

::: warning 注意
This is a warning
:::

::: danger 警告
This is a dangerous warning
:::
```