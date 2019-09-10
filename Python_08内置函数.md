### 内置函数

exec()   没有返回值
eval()   有返回值


exec和eval都可以执行字符串类型的代码
eval只能用在你明确知道你要执行的代码是什么，eval适合使用于简单的计算
exec适合适用于流程控制


code = '''
for i in range(10):
  print(i)
'''


### exec(code)

### compile() 
将字符串类型的代码编译，代码对象能够通过exec语句来执行或者eval()进行求值


### divmod(x,y) 
除余函数

### divmod()
divmod(9,5)   >>> (1,4)

### round()
round()   四舍五入，保留几位  
```
a = 3.141195004
print(round(a,4))
>>> 3.1412

```

### reverse()   
反转列表，直接在原对象上进行

### reversed()  
反转列表，返回一个对象反转的迭代器



### bytes() 
转换成为bytes类型

网络编程，只能传二进制
照片和视频也是可以二进制存储
html网页爬取的也是编码



### bytearray
ord()  字符转数字
chr()  数字转字符


### repr
用于%输出，原封不动输出原内容


### frozenset
不可变的集合



