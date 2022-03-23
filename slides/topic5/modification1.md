# Modifying Globals Inside a Function

```py
x = 42          # global scope x
def myfunc():
    x = x + 1   
    print(x)  # x=?
myfunc()
```

```py
x = 42          # global scope x
def myfunc():
    global x
    x = x + 1   
    print(x)  # x=?
myfunc()
print(x)        # x=?
```
