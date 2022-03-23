# Python Variables Scope

<br/>

不是所有的变量都可以从我们程序的所有部分访问
<br>
变量在程序中可被访问的部分称为其 "范围"，由变量的声明位置决定。

## Local scope
<br>
当函数调用退出时，局部变量将从内存中删除。
<br>
因此，试图在函数之外获取局部变量的值会导致错误。
<br>

```py
def myfunc():
    x = 42      # local scope x
myfunc()
print(x)        # x = ?
```