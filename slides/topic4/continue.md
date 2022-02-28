# continue

```py
# Print values from 6 through 0 while skipping odd numbers
x = 6
while x:
	x -= 1
	if x % 2 != 0:
		continue
	print(x)
```

```py
# Skip 'blue'
colors = ['red', 'green', 'blue', 'yellow']
for x in colors:
    if x == 'blue':
        continue
    print(x)
```