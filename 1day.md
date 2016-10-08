### JavaScript是一门动态的、弱类型编程语言。
Javascript的语法源自Java，它的一等函数（first-class function）来自于Scheme，它的基于原型（prototype-based）的继承来自于Self。
脚本语言（scripting-language）

1.javascript语言核心
//是javascript的注释
变量是表示值的一个符号名字
变量是通过一个关键字var声明的
值可以通过等号赋值给变量
可以通过变量获取其值

支持多种数据类型
1.数字   1   2.5  0.5
2.字符串 "nihao"
3.布尔值 true false
4.null 是一个特殊的值表示空
5.undefined 和null非常类似（未定义）
6.对象{}
7.数组[]

//javascript中最重要的数据类型就是对象
//对象是名/值对的集合，或字符串到值映射的集合


对象的是由{}括起来 
var book ={
  topic : "javascript",
  fat : true
};

book.topic;
book["topic"]
通过"."或[]来访问对象的属性


book.author="yuitaku";
通过赋值来创建一个新属性
book.content = {};
创建一个空对象它没有属性

javascript 同样支持数组 （以数字为索引）
var arr = [1,2,3,8,10,"helle world"];
arr[0]  // 1
arr.length;   数组中的元素个数
arr[arr.length-1]  //最后一个元素
arr[6]=8;
通过赋值来创建新的元素
arr[0]=10;
通过赋值来改变已有的元素
var empty = [];
空数组




通过[]来定义数组元素通过{}来定义对象属性名和属性值之间的映射关系的语法称为初始化表达式（initializer expression）
表达式是javascript中的一个短语 这个短语可以通过运算符得出一个值，通过. 和[]来引用对象属性或数组元素的值就构成一个表达式

表达式写法是像下面代码这样使用运算符

3+2         //5
3-2           //1
3*2       //6
3/1       //3
"3"+"2"  //"32"
a--;   自减1
a=a-1;
a++;
a=a+1;
a*=3;
a=a*3;

"two"=="three"  false
"two">"three"   true  //tw在字母表中的索引大于th
(x==2)&&(y==3)   //两个比较都是true &&表示与
(x==2)||(y==3)    //||表示或
！ 求反

如果javascript中的“短语”是表达式的话，那么整个句子将成做语句（statement）
以分号结束的行均是一条语句。


 
