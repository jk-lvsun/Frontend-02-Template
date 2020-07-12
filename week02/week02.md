##### 形式语言
  
######  非形式语言（乔姆斯基谱系）

0型 无限制文法
1型 上下文相关文法
2型 上下文无关文法
3型 正则文法

##### 产生式 （BFN）

> 
    ::=，表示定义为
    |，表示或
    、<>，用来区分非终结符（表示非终结符）

<MultiplicativeExpression> ::= <Number> | <MultiplicativeExpression> "*" <Number> | <MultiplicativeExpression> "/" <Number>
<AddtiveExpression> ::= <MultiplicativeExpression> | <AddtiveExpression> "+" <MultiplicativeExpression> | <AddtiveExpression> "-" <MultiplicativeExpression>

其他产生式 
EBNF ABNF

js 总体上下文无关文法
C++ 形式语言 
VB 上下文相关语法
python 上下文无关语法


形式语言-用途
数据描述语言 JSON HTML XAML SQL CSS
编程语言 C++ C Java C# python 
形式语言 -表达方式
声明式语言 C++ C Java C# python 
命令型语言JSON HTML XAML SQL CSS

###### 编程语言的性质

图灵完备性
命令式---- 图灵机
goto
if while

声明式 ----lambda
递归

动态：
在用户设备/在线服务器
产品实际运行时
runtime

静态
程序员设备
产品开发
compiletime

类型系统 
动态类型系统 静态类型系统

强类型弱类型
string + number

string == boolean

复合类型
结构体
函数签名

子类型

泛型
逆变/协变

##### 命令式编程语言

Atom Identifier()

Grammer                 runtime
literal 字面值            types
variable                  execution context
keywords
whitespace 
lineterminator

js Types

##### Number
String
Boolean
Object
Null 

Undefined (未定义 赋值用null)
Symbol 代替Object string 索引（js 特有概念 Object 属性名）

Number（Double Float）

sign（1）正负
Exponent （11） 指数
Fraction（52） 精度位
0.tostring()
0 .tostring()

##### String 
Charactter 
code point 
encoding

##### Object 
任何一个对象都是唯一的 与状态无关

设计对象的状态和行为时 遵循”行为改变状态“原则

property prototype
在js运行时 原生对象关心原型 属性



