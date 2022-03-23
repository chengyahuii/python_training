# 参数

<br/>

## 位置参数

- 最常见且传参需要严格按照顺序

```py
def func(name, job):
    print(name, 'is a', job)
func('Bob', 'developer')
```

<br/>

### 关键字参数

- 参数的顺序不再重要

```py
# Keyword arguments can be put in any order
def func(name, job):
    print(name, 'is a', job)
func(name='Bob', job='developer')

func(job='developer', name='Bob')
```

