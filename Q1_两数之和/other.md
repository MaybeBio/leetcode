
![image](https://github.com/user-attachments/assets/46bebb11-03eb-4110-9f08-5f595da8d25d)

![image](https://github.com/user-attachments/assets/f5d3e298-4e4e-4321-b3d0-802723616ca8)


还是双指针，两个for，其实我代码中第2个循环内部的else:continue是没有必要的，反正没有达成if条件的话，本来就会进入下一个循环j；

另外当Python解释器遇到 return 语句时，它会立即停止函数的执行，并将 return 后面的表达式的值返回给调用者，也就是return是退出；

所以应该在2个for循环里面没有解答成功的时候，即case：所有N*N暴力无解之后，return[]，即返回空列表。

![image](https://github.com/user-attachments/assets/5d19c323-bf0d-4937-92e9-57f9fa4677ca)

官方给出的解答是使用哈希表hash table，哈希表中存储的key是值，value是index索引；

![image](https://github.com/user-attachments/assets/b1a6c81f-c6af-4171-961c-be75e2d31d69)

操作上是hash表要另外开内存放第1个for循环的值，当然第1次for循环开过去hash表，实际上第2次for循环就可以避免了，能够直接以O（1）的复杂度去寻找target-

使用的是enumerate，对于1个可迭代对象能够同时返回索引index和值，

参考：https://www.runoob.com/python/python-func-enumerate.html

![image](https://github.com/user-attachments/assets/929eb55d-6c15-4320-8b0a-1bd511df178c)

![image](https://github.com/user-attachments/assets/f2f8a4c4-10b2-463f-a8bd-ed9fd58fd3c4)






