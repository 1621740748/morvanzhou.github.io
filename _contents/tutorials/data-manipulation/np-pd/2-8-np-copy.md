---
youku_id: XMTU4ODc2ODUwOA
youtube_id: lXmiDyktnCA
title: Numpy copy & deep copy
description: 


date: 2016-11-3
chapter: 2
---
* 学习资料:
  * [相关代码]()

如果直接把 numpy array赋值给另一个变量,
改变任意的一个变量都会影响到其他变量.
比如:
a = np.arange(4)
b = a
a[0] = 11
那这是b[0] 也会变成11
如果不想这样,
我们就会要用到 deep copy 的概念:
b = a.copy()来只附加 a 的值给 b, 并没有关联 a 去 b.