# self

self参数指的是单个对象本身。它被用来获取或设置特定实例的属性。
self应该始终是类中任何方法的第一个参数，即使该方法没有使用它。

```py
class Car:
    def __init__(self):
        self.color = red
```
