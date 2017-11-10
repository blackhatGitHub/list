Python 2.7.13 (v2.7.13:a06454b1afa1, Dec 17 2016, 20:42:59) [MSC v.1500 32 bit (Intel)] on win32
Type "copyright", "credits" or "license()" for more information.
>>> var = '20'
>>> print str(var)
20
>>> print var
20
>>> new_var = 'abc'
>>> print new_var
abc
>>> print int(new_var)

Traceback (most recent call last):
  File "<pyshell#5>", line 1, in <module>
    print int(new_var)
ValueError: invalid literal for int() with base 10: 'abc'
>>> print int(var)+1
21
>>> print var+1

Traceback (most recent call last):
  File "<pyshell#7>", line 1, in <module>
    print var+1
TypeError: cannot concatenate 'str' and 'int' objects
>>> print str(var)+1

Traceback (most recent call last):
  File "<pyshell#8>", line 1, in <module>
    print str(var)+1
TypeError: cannot concatenate 'str' and 'int' objects
>>> random()

Traceback (most recent call last):
  File "<pyshell#9>", line 1, in <module>
    random()
NameError: name 'random' is not defined
>>> import random
>>> var = random()

Traceback (most recent call last):
  File "<pyshell#11>", line 1, in <module>
    var = random()
TypeError: 'module' object is not callable
>>> var = random.random()
>>> print var
0.0141814298764
>>> var = random.uniform(3,7)
>>> print var
6.55262358518
>>> var = random.uniform(7,3)
>>> print var
6.20376162595
>>> var = random.randint(3,7)
>>> print var
5
>>> var = 1
>>> page_num = 1
>>> print '第',str(page_num),'页'
第 1 页
>>> print '第'+page_num+'页'

Traceback (most recent call last):
  File "<pyshell#23>", line 1, in <module>
    print '第'+page_num+'页'
TypeError: cannot concatenate 'str' and 'int' objects
>>> print '第' + page_num + '页'

Traceback (most recent call last):
  File "<pyshell#24>", line 1, in <module>
    print '第' + page_num + '页'
TypeError: cannot concatenate 'str' and 'int' objects
>>> print type(page_num)
<type 'int'>
>>> print '第'+page_num+'页'

Traceback (most recent call last):
  File "<pyshell#26>", line 1, in <module>
    print '第'+page_num+'页'
TypeError: cannot concatenate 'str' and 'int' objects
>>> print "第"+page_num+"页"

Traceback (most recent call last):
  File "<pyshell#27>", line 1, in <module>
    print "第"+page_num+"页"
TypeError: cannot concatenate 'str' and 'int' objects
>>> print "第"+ page_num +"页"

Traceback (most recent call last):
  File "<pyshell#28>", line 1, in <module>
    print "第"+ page_num +"页"
TypeError: cannot concatenate 'str' and 'int' objects
>>>  print "第" + page_num + "页"
 
  File "<pyshell#29>", line 2
    print "第" + page_num + "页"
    ^
IndentationError: unexpected indent
>>> page_num = 1
>>>  print "第" + page_num + "页"
 
  File "<pyshell#31>", line 2
    print "第" + page_num + "页"
    ^
IndentationError: unexpected indent
>>> random.choice(['a','b','c'])
'c'
>>> random.choice(['a','b','c'])
'b'
>>> list1 = list1 = ['physics', 'chemistry', 1997, 2000];
>>> list1 = ['physics', 'chemistry', 1997, 2000];
>>> list1[0]
'physics'
>>> list1[1]
'chemistry'
>>> list1[2]
1997
>>> list1[3]
2000
>>> list1[0:4]
['physics', 'chemistry', 1997, 2000]
>>> list1[0:3]
['physics', 'chemistry', 1997]
>>> list1[2:1]
[]
>>> list1[2:2]
[]
>>> list1[2:3]
[1997]
>>> list1[1:2]
['chemistry']
>>> del list[2]

Traceback (most recent call last):
  File "<pyshell#46>", line 1, in <module>
    del list[2]
TypeError: 'type' object does not support item deletion
>>> del list1[2]
>>> 
>>> list1
['physics', 'chemistry', 2000]
>>> 
