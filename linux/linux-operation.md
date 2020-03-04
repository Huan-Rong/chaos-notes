# Linux Operation
## 版本
### 查看内核版本

* cat /proc/version
* uname -a

### 查看发行版本

* lsb_release -a: 通用命令，可能需要执行 `yum install -y redhat-lsb-core` 命令
* cat /etc/redhat-release：只适用于 RedHat 系

## YUM

`yum install <command>` 查看命令所在的软件包

## 命令的类别

[命令的类别](https://www.cnblogs.com/xiangyuguan/p/10981548.html)

* 内部命令和外部命令的区别在于，系统启动之后命令会不会加载到内存中。
* 判断命令的类别：`type <command>`

## 文件和目录的查看命令 ls

* `-l`：以列表形式查看
* `-a`：显示隐藏文件
* `-r`：逆序显示
* `-R`：递归显示
* `-t`：按照修改时间排序

## 通配符

* `*`：匹配任意数量的任意字符
* `?`：匹配单个任意字符
* `[xyz]`：匹配 xyz 中的任意一个字符
* `[!xyz]`、`[^xyz]`：匹配不在 xyz 中的任意一个字符
* `[a-z]`：匹配字符范围中的任意一个字符
* `[!a-z]`、`[^a-z]`：匹配不在字符范围中的任意一个字符
