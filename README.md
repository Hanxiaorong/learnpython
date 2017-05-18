### 练习0 安装python和atom

1. 下载atom,网址[https://atom.io/](https://atom.io/)
2. 把atom放到dock
3. 找到terminal终端
4. 把它放到dock
5. 在terminal里面打python
6. 输入quit\(\)加回车退出Python
7. 在GitHub上创建一个仓库，learnpython
8. 将仓库clone到本地
9. cd learnpython进入本地仓库
10. 使用atom编辑python文档，保存在learnpython仓库
11. 以后完成的练习通过git上传到GitHub上保存

### 练习1 Hello world

1. 在atom里面输入代码
2. 练习print
3. 练习””和’’输出str
4. 练习在terminal中查看程序运行结果
5. 打开terminal,首先进入cd learnpython
6. 然后输入python ex1.py

### 练习2  注释

1. 后面是注释内容，不在文档中体现。

### 练习3 数字和数学计算

1. 练习基本+ - \* / %\(求余数\)
2. 练习Print 用,（逗号）隔开，会在同一行输出，中间空格
3. 如果要换行，需要在另一行重新输入print

### 练习4 变量

1. 学习给变量赋值 用‘=’
2. 学习分析错误原因，未给变量赋值
3. 学会变量之间做数学计算
4. 学习输入让阅读更美观，运算符号后面加个空格

### 练习5 格式化输入

1. 变量既可以赋值为数字，又可以赋值为str
2. Print 一句话中，可以先用格式化字符占位，后面再进行填充。
3. 格式是%s\(代表这个位置是一个str\)，后面%字符串
4. %d（代表这是一个整数）
5. 如何要输出多个格式化字符，后面需用\(\)中间用,隔开
6. 句子和%之间没有逗号，注意

### 练习6 更多格式化输入

1. 格式化字符可以嵌套使用
2. %r表示不带格式的完全输出
3. 两个str中间用+连起来，等于两句话连起来在同一行输出

### 练习7 更多的Print输出

1. Str通过\*可以重复N次
2. 一句话以,逗号结尾，下一句可以和上一句在同一行输出，中间空一格

### 练习8 更多的print

1. 在双引号里面再出现双引号，输出时，里面的双引号变成单引号
2. 格式化输出可以调用自身，注意输出里面是没有逗号

### 练习9 更多的Print

1. \n代表换行符
2. 打印多个内容在同一行，中间用，逗号隔开
3. “”“ ”“”三引号之间的内容，可以输入多行str文本，原样输出
4. ‘’和“”只能输出单行文字

### 练习10 转义字符

1. \t为制表符，代表一个缩进
2. \n为换行符，\为一个\

### 练习11  输入

1. raw\_input—&gt;string
2. Input = eval\(raw\_input\(\)\)—&gt;int
3. Pydoc和help\(\)不同，前者功能更强，help只能用于函数

### 练习12 提示

1. raw\_input\(string\)

### 练习13 参数解包变量

1. 引入sys模组，里面argv函数，为程序添加变量
2. argv\[0\]为程序名，后面才是参数
3. 为了让输出美观点，注意中间空行

### 练习14 解包参数和输入

1. 参数解包是事先输入的，更多用于固定情况，比如程序名，人名
2. raw\_input更多是用于与用户的交互，界面更友好，更多提示

### 练习15 读文件

1. 可以用argv解开文件名，因为文件名是固定的，不需要用户交互。
2. open\(name\[, mode\[, buffering\]\]\) -&gt; file object
   * 例如：open\(filename,'w'\)
3. open函数如果不指定打开方式的话，默认为read
4. 文件要先打开为file object，然后才能使用write,read等操作。

### 练习16 读写文件

1. 基本文件操作
   * read
   * write('stuff')
   * close
   * readline
   * truncate
2. 使用一个无实际作用的raw_input来让用户控制程序进程。一个是回车继续，一个是CTRL-C退出，巧妙。

### 练习17 更多的文件操作

1. 引入了新的os.path模组里面的exists函数，判断该路径下的文件是否存在
2. argv第一个变量永远是script
3. len()函数判断文件的字节长度
4. 调用，exists(文件名)；返回指，True，False,如果不存在，就创建一个文件
5. 通过rew_input()用户控制流程
6. open(文件名,'w')用写的方式打开文件
7. .write（）写入文件
8. 两个文件close()

### 练习18 函数
1. 函数的定义方法,def 函数名(参数)：冒号结尾，下一行是函数主题，前面要缩进
2. \*args，这里的*指的是任意个数的参数。
3. arg1, arg2 = args,解包的时候没有*了
4. 参数也可以是明确的几个，或者1个，或者没有参数

### 练习19 函数的参数传递方式
1. 可以直接在()里面给出数字
2. 可以是两个变量
3. 可以是运算式
4. 可以是变量的运算式

### 练习20 函数和文件操作
1. seek()控制指针位置,(0)代表回到开头位置
2. readline()读完一行之后，指针跳到下一行开头.

### 练习21 函数返回值
1. return可以返回函数的计算结果
2. 函数的返回值可以作为参数，调用到新的函数中。

### 练习24 更多的练习
1. python的返回值是有顺序的，而且跟函数的名字无关

### 练习25 更多更多的练习
1. Python程序可以作为一个模组调用
2. 格式是import 程序名，注意没有.py
3. 调用方式是xx.函数名就行了
4. """ """之间的文字是注释，可以通过Help()调用的帮助文档
5. 可以from ex25 import * 来直接调用函数，不用重复写ex25
6. list.pop[i]:取出i位置的元素并返回该值，pop()默认返回最后一个数

### 练习29 If语句
1. if 判断语句:如果为真，执行下一行语句,下一行语句缩进
2. x += 1 等于 x = x + 1,既x加法变化的大小为1

### 练习30 else if
1. 有一个If,必然有一个else
2. 当有多个If语句判定为真，Python只执行第一条语句

### 练习31 通过If语句来控制程序分支进程
1. ==代表布尔值判定是否相等，=代表赋值
2. if和elif不同，elif是承接上面的if继续进行判定，如果改为if，会改变else的输出

### 练习32 循环和列表
1. range(x,y)指的是从x到y，包括x，不包括y。其中x,y都是整数
2. range(x)默认是从(0, x)
3. 可以用for in循环语句从list里面取出elements
4. append函数是在List后面增加元素，使用方法是:列表.append(x)

### 练习33 while循环
1. 如果用while循环语句，关键是要设计出循环的条件。
2. 多用print语句来测试循环代码，看看程序内部是如何运转的。
3. 使用while语句的时候，需要初始化，设计好中间变化，和出圈条件。

### 练习34 访问列表的元素
1. 列表的元素从0开始
2. 善用切片[0]表示列表的第一个元素，[-1]表示列表的最后一个元素。

### 练习35 函数与分支
1. exit(0)退出整个程序,0是正常退出，1是错误退出
2. 通过and 和 and not来反转状态，控制程序进程，很巧妙。
3. 设置程序退出的窗口

### 练习37 符号回顾
1. 关键字，数据类型，转义字符，格式化字符串，操作符，都总结得很好，很有参考价值。

### 练习38 列表的操作
1. string.split(" ")可以把字符串变成列表
2. " ".join(list)可以把列表变成字符串
3. len()操作对象是List
4. pop()操作对象是list

### 练习39 字典
1. del 字典['键']
2. dict.items()返回的是包含键值对的元祖
3. dict.get(key, "str")如何key存在返回值，如果key不存在，默认返回none，或者str
4. 直接用for x in dict,返回的是key

### 练习40 模块、类和对象
1. 模块：对于字典来说，键是一个字符串，获得值的语法是"[键]"。对于模块来说，键是函数或者变量的名称，而语法是".键"。除了这个，基本没有什么区别了
  * 模块是包含函数和变量的Python文件
  * 可以导入这个文件
  * 然后可以使用，操作符访问模块中的函数和变量
2. 实例化：新建一个对象的过程称为实例化，而对象是这个类的一个实例。
3. 对象：每个对象都是某个类的实例，所以“对象”和“实例”这两个词很多情况下都可以互换。
4. 类：类像一个创建对象的工厂。
5. 定义类的时候，似乎不写object，或者不写()，输出也是正确的。
6. 定义类的时候是直接class
7. 类的调用，先进行实例化，然后使用.函数直接使用即可。

### 练习41 面向对象
1. 在本章学习过程中其实遇到了问题，不是很清楚什么是面向对象，不熟悉类和对象等等概念，也不清楚为什么要进行面向对象编程。
2. 看了廖雪峰的PYthon课找到了一点感觉，面向对象编程指的是把一个对象进行封装，调用这个对象的属性和方法。
3. 41章的很多代码看不懂，先放一放，后面再看
()
