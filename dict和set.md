# 字典：dict（全称dictionary），js的map

使用键值对存储，具有极快的查找速度

为避免key不存在的错误，有两种办法：

### 1、通过in判断key是否存在：

### 2、通过dict提供的get()方法，如果key不存在的话，则返回None或者自己指定的value

`d.get('elemnent', -1?)`:如果没有传-1，且d中没有元素element，则返回None，传入-1即返回-1

## 想要删除一个key，可以用pop(key), 可以删除对应的value



# set：key不重复的集合

```
s = set(list[1,2,3])
s = {1,2,3,4,5}
set是无序的
s.add(key) # 可以添加元素到set中
s.remove(key) # 可以删除元素
```

