# 什么是 DA 
## 什么是数据结构？什么是算法？

* 广义上，**数据结构就是指一组数据的存储结构。算法就是操作数据的一组方法**。
* 狭义上，是指某些著名的数据结构和算法，比如队列、栈、堆、二分查找、动态规划等。
* 数据结构和算法是相辅相成的。
  * 数据结构是为算法服务的，算法要作用在特定的数据结构之上。我们无法脱离数据结构来讲算法。
  * 数据结构是静态的，它只是组织数据的一种方式。如果不在它的基础上操作、构建算法，孤立存在的数据结构就是没用的。因此我们也无法脱离算法来讲数据结构。即算法是数据结构存在的意义。

### 一个例子

**数组具有随机访问的特点，而链表并不支持随机访问。**常用的二分查找算法需要用数组这种数据结构来存储数据，如果换成链表，二分查找算法就无法工作了。

### Random access VS sequential access

Random(direct) access implies the ability to access any entry in a array in constant time (independent of its position in the array and of array's size). And that is big advantage.

It is typically contrasted to sequential access. Datastructure has sequential access if we can only visit the values it contains in one particular order.

[see more](https://stackoverflow.com/questions/43126147/random-access-in-array)
