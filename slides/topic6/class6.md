# create an object

```py
# Create an object from the 'Car' class by passing style and color
class Car:
    # class attribute
    wheels = 4
    # initializer with instance attributes
    def __init__(self, color, style):
        self.color = color
        self.style = style
c = Car('Black', 'SUV')
```

为什么c = Car('Black', 'SUV')没有传self？
