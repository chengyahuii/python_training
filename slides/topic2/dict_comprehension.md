# 字典表达式

字典表达式是通过对序列中的每一项应用表达式来创建新字典的方法

格式
```py
{key: value for var in iterbale}
{key: value for var in iterable if_clause}
```
<br/>

Example
```py{1-4|5-8}

D = {c: c * 3 for c in 'RED'}
print(D)
# Prints {'R': 'RRR', 'E': 'EEE', 'D': 'DDD'}

D = {x: x**2 for x in range(6) if x % 2 == 0}
print(D)
# Prints {0: 0, 2: 4, 4: 16}

```