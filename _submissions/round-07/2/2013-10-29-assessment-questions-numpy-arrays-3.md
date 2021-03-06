---
date: 2013-10-29
round: Round 7
title: 'Assessment Questions: Numpy Arrays'
author: Joshua Adelman
permalink: /2013/10/assessment-questions-numpy-arrays-3/
tags:
  - Assessment
---
******Novice from Competent**

Given the 2D array generated using the following code snippet:

&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;-  
`import numpy as np<br />
x = np.random.normal(size=(10,10))<br />
y = x[2:5,1:5]`  
&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;-

What is the shape of *y*?

1.  (4,5)
2.  (3,3)
3.  (3,4)
4.  (5,4)
5.  (4,3)

**Expert from Competent**

Suppose you had an array generated by the following code:

`x = np.arange(25).reshape((5,5))`  
`<br />
array([[ 0,  1,  2,  3,  4],<br />
[ 5,  6,  7,  8,  9],<br />
[10, 11, 12, 13, 14],<br />
[15, 16, 17, 18, 19],<br />
[20, 21, 22, 23, 24]])<br />
`

Which of the following commands would give you the following array?  
`<br />
array([[ 1, 4],<br />
[ 6, 9],<br />
[21, 24]])<br />
`

1.  `x[[0,1,4],[1,4]]`
2.  `x[np.ix_([0,1,4],[1,4])]`
3.  `x[np.meshgrid([0,1,4],[1,4])]`
4.  `x[[0,1,4]][1,4]`
5.  `x[[0,1,4]][[1,4],:]`
