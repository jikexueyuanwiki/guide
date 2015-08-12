# Fork 仓库

进入这个示例仓库：<https://github.com/jikexueyuanwiki/simple>，然后 Fork 一份到自己的仓库。

## 文件目录详解

- **cover/** - 存放 [官网首页](http://wiki.jikexueyuan.com/) 背景图片（图片由极客学院提供，后期整理上线时，编辑会添加）
 - background.png 或 background.jpg
 - logo.png 或 logo.jpg
 
- **images/** - 存放图片（用到的图片文件都放在这）

- **README.md** - 说明文档（**必须有**，默认 wiki 首页显示，相当于书籍的序）

- **TOC.md** - 目录（**必须有**，该 wiki 的目录）

- **config.json** - 书籍名称和介绍（**必须有**）

 
## 文章目录格式介绍 

`TOC.md` 文件是整本书的目录，它是各个章节的一个链接集合，下面我们举两个例子来说明：

### 简单模式

```

- [Chapter 1](chapter1.md)
- [Chapter 2](chapter2.md)
- [Chapter 3](chapter3.md)

```

### 多级目录模式

```
- [Part I](part-one.md)
    - [Writing is nice](writing.md)
    - [GitBook is nice](gitbook.md)
- [Part II](part-two.md)
    - [We love feedback](feedback_please.md)
    - [Better tools for authors](better_tools.md)
```

>注意：编写完 TOC.md 文件后，还需要创建对应的 md 文件（如writing.md)。

到此，你已经有了一个自己的仓库，但是为了避免仓库名重复，我们将讲解[修改仓库](start-writing.md)。

```
  


