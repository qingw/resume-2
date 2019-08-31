本项目Fork自https://github.com/liweitianux/resume

使用xelatex编译

# 简历命名规范

XX实习+张中俊+西安电子科技大学+硕士+网络空间安全.pdf

安全开发工程师\_张中俊_西安电子科技大学\_硕士\_网络空间安全.pdf

# 改进及设计思路：

* 引入了Font Awesome 5的其他字体，这样就可以使用更多的符号
* 减少了页边距，Education间距等，作为一页简历
* 左上角增加了照片，即使是研发岗，也建议贴上自己的照片
* 在所有面试官可能感兴趣的地方（如实习所在公司、论文发表期刊等）添加url链接，方便面试官直接点击查看
* 一页简历，所有内容在一页上进行展示

# Font Awesome 5

> Font Awesome 5包含多个字体库，每个字体库包含的符号见 https://fontawesome.com/how-to-use/on-the-desktop/setup/getting-started
>
> 在 https://fontawesome.com/icons 中挑选你想要的图标

* 使用方法:

```latex
\icon{\faFlag}
```



使用TeX Live Manager将fontawesome5包升级到version 5.4.1及以上，这样就可以使用使用如下的命令

```bash
\usepackage[fixed]{fontawesome5}
```

* Font Awesome 5 Free

* Font Awesome 5 Free Solid

* Font Awesome 5 Free Regular

* Font Awesome 5 Brands Regular

首先需要将你需要的字体安装到本地上