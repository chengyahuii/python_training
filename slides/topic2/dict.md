# 字典

一个键值对的集合

```py

# Create a dictionary to store employee record
D = {'name': 'Bob',
     'age': 25,
     'job': 'Dev',}

L = [('name', 'Bob'),
     ('age', 25),
     ('job', 'Dev')]

D = dict(L)

```

这两种创建字典方式的不同？？？哪种方式更好？？？

```
通过 D["name"] 可以获取到相应key的值
通过D["id"] = xxx 可以给字典创建一个新的键值对
```