HOMEWORK FOR BASIC PYTHON
# HW1 基本IO及数据结构

## 1. (基本IO)使用一条语句, 打印以下字符串

```
poi (￣▽￣)"
```
(提示:特殊字符是否要特殊处理)

```
\\\///
```
(要求:编写两条语句, 使用两种方法处理其中的特殊字符. 提示:r或\\)

```
foo
bar

```
(提示:跨行字符串)

## 2. (基本IO)按要求续写代码并运行

```python
s1='1234567890'
length=0
```
要求:

1. 将字符串s1的长度赋给length
1. 从键盘读取输入'233'到s2
1. 连接字符串s1,s2为s
1. 将字符串s1去头去尾
1. 将s2首位修改为3
1. 打印字符串s,s1,s2,及s,s1,s2的长度,中间以','分隔
1. 保存源码及输出

## 3. (基本数据结构: list, tuple) 按要求完成代码

构建一个名为a的list,一个名为b的tuple(元祖). list和tuple均包含以下数据
```
0,1,2,3,4,'foo','longlonglongstring!',8,8,8,8
```
对于其中可修改的对象, 执行以下操作

1. 将'foo'直接修改成'Foo'
2. 在尾部附加 5 (int)
3. 去除元素 0
4. 去除元素 2 4
5. 读取当前的首个元素到一个单独变量, 并输出
5. 将'longlonglongstring!'修改成'longlonglongstring#'
6. 打印 a, b, 中间换行

Tips: [] ()

## 4. (set) 按要求完成代码

1. 构建一个set c, 其数据来源于b(见3) Tips:set()
1. 使用类似的语法将tuple b 转化成list保存到 d. Tips:list()
1. 构建空set e
1. 在e中加入元素1,2,3,4
1. 在e中删去元素4
1. 分别取c,e的交集, 并集并输出

## 5. (dict) 按要求完成代码

将下列对照表以dict的形式存储, 首行无需处理

姓名|分数
-|-
A|100
B|90
C|80

1. 添加数据 "D: 70分"
1. 删除数据 "C: 80分"
1. 修改数据 "B: 100分"
1. 输出dict
1. 判断'E'是否在dict中, 并将逻辑值输出

## 6. 关于list的补充(选做)

构建list如下

```
a: 1,3,2,4,6,5,7,8,8
b: 2,3,4,5,9
```

尝试以下函数
```
len(a)
max(a)
min(a)
cmp(a,b)
tuple(a)
```

尝试合并a,b为c


尝试以下方法
```
a.count(8)
a.count(7)
a.reverse()
a.sort(<func>) #自行查阅资料
a.extend(b)
a.remove(1)
```

可以参见:http://www.runoob.com/python/python-lists.html

## 7. (补充) 查找资料了解python2,3不兼容的原因, 以及python3中的字符串编码规则.

## 附: 大纲

* IO和基本数据结构
* 基本运行, 条件, 循环, 类型转换
* 函数1
* 切片, 迭代, 列表生成式, 生成器, 迭代器
* 函数2
* 面向对象初步
* 面向对象2
* 文件IO, 模块使用, 编辑器操作
* 错误处理和测试
* 正则表达式
* 绘图
* iPython, Pandas初步, 
* 各种包的使用...
* 进程,线程,网络编程讨论

***
Copyright © 2018 Huaqiang Wang. All rights reserved. 