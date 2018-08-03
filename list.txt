>>> li=['naveen','saravana','harish','keerthi']
>>> li
['naveen', 'saravana', 'harish', 'keerthi']
>>> li.append['eugene']
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'builtin_function_or_method' object is not subscriptable
>>> li.append('eugene')
>>> li
['naveen', 'saravana', 'harish', 'keerthi', 'eugene']
>>> li[-1]
'eugene'
>>> li[0:2]
['naveen', 'saravana']
>>> li[-1:2]
[]
>>> li[-1:-3]
[]
>>> li[-1:0]
[]
>>> li[0:-3]
['naveen', 'saravana']
>>> li[-3:]
['harish', 'keerthi', 'eugene']
>>> li[-3:-1]
['harish', 'keerthi']
>>> li[-1]=('Eaugene')
>>> li
['naveen', 'saravana', 'harish', 'keerthi', 'Eaugene']
>>> li.insert(3,'sadakoban')
>>> li
['naveen', 'saravana', 'harish', 'sadakoban', 'keerthi', 'Eaugene']
>>> li.index('naveen');
0
>>> li.remove('harish')
>>> li
['naveen', 'saravana', 'sadakoban', 'keerthi', 'Eaugene']
>>> li.pop();
'Eaugene'
>>> li
['naveen', 'saravana', 'sadakoban', 'keerthi']
>>> li[0] + li[1]
'naveensaravana'
>>> li[0]*5
'naveennaveennaveennaveennaveen'