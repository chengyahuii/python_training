# Basic Example

```py
# Iterate until x becomes 0
x = 6
while x:
    print(x)
    x -= 1
```
```py
# Iterate until list is empty
L = ['red', 'green', 'blue']
while L:
    print(L.pop())
```
```py
# Iterate until string is empty
x = 'blue'
while x:
    print(x)
    x = x[1:]
```

```py
x = 6
while x:
    print(x)
    x -= 1
else:
    print('Done!')
```