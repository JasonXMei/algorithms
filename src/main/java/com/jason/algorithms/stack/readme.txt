我们都熟悉很有名的撤销（Undo）选项，它几乎存在每个应用程序中。有没有想过它是如何工作的？
其思路就是，按照最后的状态排列在先的顺序将工作的先前状态（限于特定数字）存储在内存中。
这只用数组是无法实现的，因此堆栈就有了用武之地。

可以把堆栈看作一堆垂直排列的书籍。为了获得位于中间位置的书，你需要拿掉放在它上面的所有书籍。
这就是 LIFO（后进先出）方法的工作原理。

堆栈的基本操作：
Push——在顶部插入元素
Pop—— 从堆栈中删除后返回顶部元素
isEmpty——如果堆栈为空，则返回 true
Top ——返回顶部元素，但不从堆栈中删除

常见的堆栈面试问题：
使用堆栈计算后缀表达式
对堆栈中的值进行排序
检查表达式中的括号是否平衡