# Variable Length Arguments

<br/>

不定长参数可以用来接收无限个数的参数

*\*args：在一个参数前加上星号*时，它将所有不匹配的位置参数收集到一个元组中。
因为它是一个普通的元组对象，你可以执行元组支持的任何操作，如索引、迭代等。
下面的函数将传递给函数的所有参数打印成一个元组。
```py
def print_arguments(*args):
    print(args)
print_arguments(1, 54, 60, 8, 98, 12)
# Prints (1, 54, 60, 8, 98, 12)
```
*\**kwargs：** 语法是类似的，但它只对关键字参数起作用。它把参数收集到一个新的字典中，其中参数名是键，它们的值是相应的字典值。
```py
def print_arguments(**kwargs):
    print(kwargs)
print_arguments(name='Bob', age=25, job='dev')
# Prints {'name': 'Bob', 'age': 25, 'job': 'dev'}
```