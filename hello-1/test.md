# test

this is a test



* \#： 预处理符号



```cpp
#include <iostream>
using namespace std;
 
class printData
{
   public:
      void print(int i) {
        cout << "整数为: " << i << endl;
      }
 
      void print(double  f) {
        cout << "浮点数为: " << f << endl;
      }
 
      void print(char c[]) {
        cout << "字符串为: " << c << endl;
      }
};
 
int main(void)
{
   printData pd;
 
   // 输出整数
   pd.print(5);
   // 输出浮点数
   pd.print(500.263);
   // 输出字符串
   char c[] = "Hello C++";
   pd.print(c);
 
   return 0;
}
```

下面提供了各种运算符重载的实例，帮助您更好地理解重载的概念。

| 序号 | 运算符和实例 |
| :--- | :--- |
| 1 | [一元运算符重载](https://www.runoob.com/cplusplus/unary-operators-overloading.html) |
| 2 | [二元运算符重载](https://www.runoob.com/cplusplus/binary-operators-overloading.html) |
| 3 | [关系运算符重载](https://www.runoob.com/cplusplus/relational-operators-overloading.html) |
| 4 | [输入/输出运算符重载](https://www.runoob.com/cplusplus/input-output-operators-overloading.html) |
| 5 | [++ 和 -- 运算符重载](https://www.runoob.com/cplusplus/increment-decrement-operators-overloading.html) \`\`\`c |
|  |  |
|  |  |
| dwd | dwqdw |
| 6 | [赋值运算符重载](https://www.runoob.com/cplusplus/assignment-operators-overloading.html) |
| 7 | [函数调用运算符 \(\) 重载](https://www.runoob.com/cplusplus/function-call-operator-overloading.html) |
| 8 | [下标运算符 \[\] 重载](https://www.runoob.com/cplusplus/subscripting-operator-overloading.html) |
| 9 | [类成员访问运算符 -&gt; 重载](https://www.runoob.com/cplusplus/class-member-access-operator-overloading.html) |





### 可重载运算符/不可重载运算符

下面是可重载的运算符列表：

| 双目算术运算符 | + \(加\)，-\(减\)，\*\(乘\)，/\(除\)，% \(取模\) |
| :--- | :--- |
| 关系运算符 | ==\(等于\)，!= \(不等于\)，&lt; \(小于\)，&gt; \(大于\)，&lt;=\(小于等于\)，&gt;=\(大于等于\) |
| 逻辑运算符 | \|\|\(逻辑或\)，&&\(逻辑与\)，!\(逻辑非\) |
| 单目运算符 | + \(正\)，-\(负\)，\*\(指针\)，&\(取地址\) |
| 自增自减运算符 | ++\(自增\)，--\(自减\) |
| 位运算符 | \| \(按位或\)，& \(按位与\)，~\(按位取反\)，^\(按位异或\),，&lt;&lt; \(左移\)，&gt;&gt;\(右移\) |
| 赋值运算符 | =, +=, -=, \*=, /= , % = , &=, \|=, ^=, &lt;&lt;=, &gt;&gt;= |
| 空间申请与释放 | new, delete, new\[ \] , delete\[\] |
| 其他运算符 | \(\)\(函数调用\)，-&gt;\(成员访问\)，,\(逗号\)，\[\]\(下标\) |

![hhh](../.gitbook/assets/image%20%283%29.png)

