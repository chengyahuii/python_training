# 实例属性

实例属性是一个变量，对每个对象（实例）都是唯一的。该类的每个对象都有自己的该变量的副本。对该变量所做的任何改变都不会反映在该类的其他对象中。

```py
# A class with two instance attributes
class Car:
    # initializer with instance attributes
    def __init__(self, color, style):
        self.color = color
        self.style = style
```