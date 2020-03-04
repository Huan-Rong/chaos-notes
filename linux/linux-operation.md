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
