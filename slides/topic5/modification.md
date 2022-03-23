# Modifying Globals Inside a Function

```py
x = 42          # global scope x
def myfunc():
    x = 0
    print(x)    # x=?
myfunc()
print(x)        # x=?
```

```py
x = 42          # global scope x
def myfunc():
    global x    # declare x global
    x = 0
    print(x)    # x=?
myfunc()
print(x)        # x=?
```
