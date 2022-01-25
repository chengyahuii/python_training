# 列表的创建方式

```py
a = list()
a = []
```

这两种方式的不同？？？

<v-click>

<div class="font-bold">
区别主要在于list()是一个function call，Python的function call会创建stack，
并且进行一系列参数检查的操作，所以CPU要执行的指令就会变多，反观[]是一个内置的C函数，可以直接被调用，因此效率高。
</div>

</v-click>