# Vim Resources

* `vimtutor` 命令
* [Chris Toomey](https://ctoomey.com/speaking#podcasts)
* [玩转 Vim - 从放弃到爱不释手](https://www.imooc.com/learn/1129)

## 目标

* Vim 基础操作
* Vim 基础概念
* Vim 配置
* Vim 插件

## 标签页和窗口

> [Vim 标签页和窗口](https://blog.csdn.net/fuxingdaima/article/details/8658342)

标签页包含窗口，即窗口的操作是在标签页中进行的。

### 标签页

* 以标签页的形式打开多个文件：`vim -p *.sh`
* 新建标签页：`:tabnew`
* 关闭当前标签页：`:tabc`、`:q`
* 切换到下一个标签页：`:tabn`、`gt`
* 切换到上一个标签页：`:tabp`、`gT`
* 切换到第一个标签页：`:tabfirst`
* 切换到最后一个标签页：`:tablast`
* 移动标签页到指定位置：`:tabm [索引]`，索引从 0 开始，如果不传索引，则默认移动到最后。
* 在多个标签中同时执行命令：`:tabdo <命令>`，如 `:tabdo %s/mouse/cat/g`，将多个标签页中的文件的 `mouse` 都替换成 `cat`。

## 缓冲区

> [理解 tab、window、buffer 之间的关系](http://einverne.github.io/post/2014/05/vim-buffer-management.html)
> [缓冲区使用 demo](https://zhuanlan.zhihu.com/p/27616958)
