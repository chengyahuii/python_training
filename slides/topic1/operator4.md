# 赋值运算符

<br/>
<br/>

| Operator | Meaning |	Example	| Equivatent to |
|---|---|---|---|
| <kbd>//=</kbd> |	Floor division assignment |	x //= 3	| x = x // 3 |
| <kbd>**=</kbd> |	Exponentiation assignment |	x **= 3	| x = x ** 3 |
| <kbd>&=</kbd> |	Bitwise AND assignment |	x &= 3	| x = x & 3 |
| <kbd>\|=</kbd> |	Bitwise OR assignment | 	x \|= 3	| x = x \| 3 |
| <kbd>^=</kbd> |	Bitwise XOR assignment |	x ^= 3	| x = x ^ 3 |
| <kbd>>>=</kbd> |	Bitwise right shift assignment | x >>= 3 | x = x >> 3 |
| <kbd><<=</kbd>	| Bitwise left shift assignment |	x <<= 3	| x = x << 3|

<!--
& 位与 两位都为1的时候结果才为1

｜ 位或 两位都为0的时候结果才为0，只要一个为1就为1

^ 异或 两位相同为0， 相反为1

\>> 右移几位 就丢弃右边n位，如果是负数就左边补1，如果是正数就补0， 右移几位就地板除2的n次方

\<< 左移 ，最左边的n位被丢弃，右边的以0补全
-->
