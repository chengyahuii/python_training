# 类属性

类属性是一个变量，对所有对象都是一样的。而且这个变量只有一个副本，与所有对象共享。对该变量所做的任何改变都会反映在所有其他对象中。

```py
# A class with one class attribute
class Car:
    # class attribute
    wheels = 4
    # initializer with instance attributes
    def __init__(self, color, style):
        self.color = color
        self.style = style
```