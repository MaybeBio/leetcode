![image](https://github.com/user-attachments/assets/e2658183-1f03-446f-b0b8-71e69fa7c026)

![image](https://github.com/user-attachments/assets/1ece72ee-1328-4811-93d1-132764192f19)

![image](https://github.com/user-attachments/assets/99a115b2-c857-4edc-a022-db8f96003030)

![image](https://github.com/user-attachments/assets/0e61919c-e505-4257-87ae-4b3068e6f1d6)

![image](https://github.com/user-attachments/assets/11b3ba14-76c2-4ae8-9f68-281cd0a70e4f)


算法本质上还是逆序构建数字，1个1个从个位数%10取下个位数，然后对于取下的个位数1个1个*10加上去，只不过这里又考虑了溢出问题，
设计的是反转一半数字；

如果是奇数的话，肯定是翻转到位数不一致的时候，中间过程的原始数字小于翻转后的数字，这样才是已经翻转过了一半数字；

如果是偶数的话：
如果是回文数，那反转到小于等于，实际上就是等于，就是一半了；
如果不是回文数，4312，一半是43和21；

——》总之，如果翻转了一半数字，不一定会有中间数字小于等于反转后数字；但是中间数字小于等于反转后数字的时候，一定是已经处理了一半数字（或者更甚）

