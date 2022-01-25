# 列表表达式

<br/>

列表表达式是通过对序列中的每一项应用表达式来创建一个新列表的方法


格式:
```py
# expression: collects the results of an expression on each iteration and uses them to fill out a new list.
# var: it takes items from an iterable one by one
# iterable: it's a collection of objects
[expression for var in iterable]
[expression for var in iterable if_clause]
```

Example:
```py {1-4|6-7}
L = []
for i in "RED":
    L.append(i*3)
print(L)

L = [i*3 for i in "RED"]
print(L)
```
