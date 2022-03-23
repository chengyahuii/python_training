# Python Variables Scope

<br>

## Global Scope

<br>
在所有函数之外声明的变量有一个全局范围。
<br>
它可以在整个文件中访问，也可以在任何导入该文件的文件中访问。
<br>

```py
x = 42          # global scope x
def myfunc():
    print(x)    # x is 42 inside def
myfunc()
print(x)        # x is 42 outside def
```