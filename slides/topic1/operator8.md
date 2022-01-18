# 位运算符

<br/>
<br/>

|Operator|Meaning|	Example|
|---|---|---|
|<kbd>&</kbd>|AND|x & y|
|<kbd>\|</kbd>|OR	|x \| y|
|<kbd>^</kbd>|XOR|	x ^ y|
|<kbd>~</kbd>|NOT|	~x|
|<kbd><<</kbd>|Left shift|	x << 2|
|<kbd>>></kbd>|Right shift|	x >> 2|

<!--
~按位取反 -a-1
先把一个数通过源码反码补码，对这个补码再进行源码反码补码的计算
负数的反码是对除了符号位取反
-->