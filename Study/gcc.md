* -f后面跟一些编译选项，PIC是其中一种，表示生成位置无关代码（Position Independent Code）

* expected specifier-qualifier-list before sth:使用了位定义的符号（类型在某些东西前面）， 一般是在结构体嵌套定义，或者引用自定义的类型时候。
  
函数参数的类型没有定义(少包含了头文件),同时函数返回指针型数据：
* zxmx_url.h:41: error: expected ')' before '*' token

if条件语句后面多一个分号";":
* suggest braces around empty body in an 'if' statement:

const 限定的变量赋给，非const时候的报错:
* warning: initialization discards qualifiers from pointer target type
