#
## Array

* 物理存储结构：由计算机分配一段连续的内存空间
* 时间复杂度
  * 访问特性：支持随机访问，时间复杂度为 `O(1)`
  * 增删元素：`O(n)`
* `java.util.ArrayList` 源码分析
  * 主要分析 `add` 方法的源码：array copy 的操作较多，如果 ArrayList 进行大规模的插入操作时，时间复杂度会上升。`待验证`

## Linked Listw
