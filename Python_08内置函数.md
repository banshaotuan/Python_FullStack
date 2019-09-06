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

