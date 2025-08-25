### 1、list：<u>列表</u> 是一种有序的集合（数组）：

​	`classmates = ['a', 'b', 'c'] `

classmates就是一个list

用len函数可以获取list的元素个数

用索引访问list中的每一个元素，从0开始

如果想获取最后一个元素，可以用-1做索引

#### list中一些常见的方法：

`append()`：往末尾追加元素

`insert(index, element)`：插入element索引位置为index

`pop(i?)`：删除指定元素(不传参则删末尾)

### 2、tuple：<u>元组</u> tuple一旦初始化就不能修改

`classmates = ('a', 'b', 'c')`

tuple更加安全，当你定义一个tuple的时候,tuple的元素就必须被确定下来，如果要定义只有一个元素的tuple，需要加一个逗号，以消除与数学运算中()的歧义

`t = (1,)`