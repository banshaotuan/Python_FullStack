## 迭代器



## 生成器


> generator方法


send()与__next__()方法的异同:

send()方法在获取生成器下一个值的时候与__next__()是一样的
只是在获取下一个值的时候，send可以给上一个yield传递一个值
使用send()需要注意：
    第一次获取下一个值的时候，应使用__next__()
    最后一个yield不能接受外部的值
    



yield from   
