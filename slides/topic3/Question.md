# QUESTION

- 1. set交集， 并集，补集
A = {'red', 'green', 'blue'}
B = {'yellow', 'red', 'orange'}
通过操作符和方法两种方式来求出A和B交集，并集和补集？

```py
交集 A&B A.intersection(B)
并集 A|B  A.union(B)
item are in A but not in B  A-B   A.difference(B)
补集 A^B A.symmetric_difference(B) 
```