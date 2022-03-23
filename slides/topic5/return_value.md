# return value

<br>

要从一个函数中返回一个值，只需使用一个返回语句。一旦返回语句被执行，函数主体中的其他内容就不会被执行。
```py
# Return sum of two values
def sum(a, b):
    return a + b
x = sum(3, 4)
print(x)
# Prints 7
```

Python 具有返回多个值的能力，这是许多其它语言所缺少的。我们可以通过用逗号分隔返回值来做到这一点。
```py
def func(a, b):
    return a+b, a-b
add, sub = func(3, 2)
print(add)
# Prints 5
print(sub)
# Prints 1
```