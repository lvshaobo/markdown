# JAVA
1. javac -d destdir srcFile
2. java ==java class name==
3. comments //, /\*... \*/
4. java源文件的文件名必须与*public类*的类名相同
5. java语句可以多行书写，但一个字符串/变量名不能跨越多行
6. char单括号， string双括号
7. java包装类:
	String a = '45';
	int i = Integer.parseInt(a);
8. 运算符
	- 算术运算符
		`\: if 两个操作数都是整数类型，则除数不能是0，else 除数可以是0或者0.0，结果为正无穷或者负无穷`
	- 位运算符(操作补码)
		`>>: 左边空出来的位以符号位填充`
		`>>>: 左边空出来的位以0填充`
		`移位运算中， 低于int类型的操作数总是先自动类型转化为int类型后再进行移位`
	- 拓展赋值运算符
		`byte a = 5;`
		`a = a + 5;   //出错，类型不匹配`
		`a += 5;	  //正确`
	- 比较运算符
		`&&, || 为短路操作`
		`&, | 分别对应&&, ||，但不会短路`
9. break/continue: 结束/继续本次loop，break/continue outer外层标签(外层循环之前定义)
10. rerurn: 结束整个方法，不管这个return处于多少个循环之内
11. 数组：type[ ] arrayName; type[ ] 为引用类型，使用type[ ]定义变量时仅仅表示定义了一个引用变量，这个引用变量还没有指向任何有效的内存，因此`定义数组时不能指定数组的长度`，而且`这个数组也不能使用，只有对数组进行初始化后才可以使用`