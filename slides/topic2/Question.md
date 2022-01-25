# QUESTIONS

```
1. 使用列表表达式找出以下列表中大于6的值并将该值乘2得到新列表
a = [1, 2, 3, 4, 5, 6, 7, 8, 10, 25, 18, 12]
结果：[14, 16, 20, 50, 36, 24]
```

```
2. 使用字典表达式将字典D中删除以removeKeys为键的键值对 
D = {0: 'A', 1: 'B', 2: 'C', 3: 'D', 4: 'E', 5: 'F'}
removeKeys = [0, 2, 5]
结果：{1: 'B', 3: 'D', 4: 'E'}

3.
prices = {
    'ACME': 45.23,
    'AAPL': 612.78,
    'IBM': 205.55,
    'HPQ': 37.20,
    'FB': 10.75
}
3.1 创建一个字典，要求：股票价格大于200
3.2 创建一个字典，里面的键如下：
tech_names = {'AAPL', 'IBM', 'HPQ', 'MSFT'}

<!--
p1 = {key: value for key, value in prices.items() if value > 200}
p2 = {key: value for key, value in prices.items() if key in tech_names}
-->

<!--
i: D[i] for i in D.keys() - removeKeys}
-->
