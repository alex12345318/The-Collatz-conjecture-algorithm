# The-Collatz-conjecture-algorithm

                                                                    1. Introduction

An algorithm that calculates the numbers and values of decrease and increase and proves why each number entered in funktion falls to a value of 1 and and due to the function 3 * X + 1, falls in to an infinite loop 4-2-1.

                                                                 2. Algorithm operation
                                                              
                                                              
                                                              
The algorithm simulates Collatz conjecture and for each number entered positiv value, calculates the number of divisions, the number of multiplications with adding the number 1, the sum of subtraction by division,the sum of the increase by multiplying and adding the number 1 and the sum and difference of the sum of the decrease and increase.The algorithm first enters an even number, confirms with enter and then an odd number and confirms with enter. In this way, the check can be performed for all numbers from 1 to approximately 9 billion.


                                                      3. Mathematical proof of the Collatz conjecture
                                                      
                                                      
In each check it is seen that the number of divisions of the entered value is greater than the number of multiplications. This is because after each multiplication by 3, 1 is added and the new value becomes an even number  and by function each even number is divisible by 2.It can also be noticed from each check, that the sum of all decrements by division is always greater than the sum of increments by multiplying and adding the number 1. The differenc between of the sum of decrements and sum of increments is always  by exactly 1  less than the initial value entered.
When the sum of the reduction is subtracted from the initial entered value, you always get 1. This is proof that each number entered in the function 3 * X + 1 / X / 2 will always fall to the value 1, no matter what its value or how many steps it will take to make it happen.


                                                                 4. Mathematical formula
                                                                 
  S(d)- the sum of the reduction.   S(m)- the sum of increase.   R- the difference between the sum of the decrease and the amount of the increase. M-  the difference between the initial value of X and R. M  is always 1. 
  
  S(d)= (X1/2)+(X2/2)+(X3/2)...+(Xn/2)
  S(m0= (2X1+1)+(2X2+1)+(2X3+1)...+(2Xn+1)
  R = S(d) - S(m)
  M = X - R
  M = 1
                                                              3. Indirect proof of Collatz conjecture.
                                                                     
                                                                     
  Since the function never ends, a value that would not collapse to a value of 1 ,would have to grow indefinitely.Such a value should have an increase amount greater than the decrease amount.The only way X grows is by multiplying and adding.Therefore, it is necessary that the number of multiplication and addition in the function (increase) is equal to or greater than the number of decrease (division).
 
n1 - number of increases in the function
n2 - number of reductions in the function

If n 1 = > n 2 , X grows to infinity.
If n 1 < n 2 X = 1.

X is the initial entered value of an a positive integer number.
  e is the even value of X
  r is an odd value of X.
If X is an odd number, then r = 3 × X + 1.
Now X becomes an even number and e = X ÷ 2.
After the first iteration,for each positive integer, the sum of the increases (S(m)) is greater than the sum of the decrease (S(d)).If n1 = n2 after each new iteration, S (m) will always be greater than S (d).But it is not possible for n1 to be equal to n2.Let us note the increase (multiplication and addition) with "a" and the decrease (division) with "b".The function is such that for each “a” we have one “b” but for each "b" we do not necessarily have "a".Only after "b" when the value of X is an odd number, we have "a".

E.g:
Enter even value X
1000
500
250
125
376
188
94
47
142
71
214
107
322
161
484
242
121
364
182
91
274
137
412
206
103
310
155
466
233
700
350
175
526
263
790
395
1186
593
1780
890
445
1336
668
334
167
502
251
754
377
1132
566
283
850
425
1276
638
319
958
479
1438
719
2158
1079
3238
1619
4858
2429
7288
3644
1822
911
2734
1367
4102
2051
6154
3077
9232
4616
2308
1154
577
1732
866
433
1300
650
325
976
488
244
122
61
184
92
46
23
70
35
106
53
160
80
40
20
10
5
16
8
4
2
1
4
4
Number of divisions :
72
Number of multiplications with adding the number 1:
41
The sum of the reduction by division:
41612
The sum of increments by multiplying and adding the number 1:
40613
The difference between the sum of reducions and increases:
999
Enter odd value V
27
82
41
124
62
31
94
47
142
71
214
107
322
161
484
242
121
364
182
91
274
137
412
206
103
310
155
466
233
700
350
175
526
263
790
395
1186
593
1780
890
445
1336
668
334
167
502
251
754
377
1132
566
283
850
425
1276
638
319
958
479
1438
719
2158
1079
3238
1619
4858
2429
7288
3644
1822
911
2734
1367
4102
2051
6154
3077
9232
4616
2308
1154
577
1732
866
433
1300
650
325
976
488
244
122
61
184
92
46
23
70
35
106
53
160
80
40
20
10
5
16
8
4
2
1
4
Number of divisions :
70
Number of multiplications with adding the number 1:
42
The sum of the reduction by division:
40589
The sum of increments by multiplying and adding the number 1:
40563
The difference between the sum of reducions and increases:
26

If X = 100
"a"= 41, "b"= 72
If x = 27
"a"= 42, "b"= 70
Each "a" was followed by one "b", but only after the odd values of the division was one "a".
Since the function never stops, rise of"a" is inevitable. For every increase "a", an identical increase "b" is inevitable.But each time the value of X after division is an odd number, "b" will be repeated and X will be minus one "a" in that iteration.As there is no other way in the function to increase except for X to be an odd number, the number of repetitions "a" will decrease each time the value after "b" is an even number.
Let us note the value that would be able to increase in the Collatz conjecture in relation to the initial value X, with the notation W.
Such a value (W) would be absurd, during its increase, it would have an increasing number of reductions ("b") in relation to the increase  ("a") that it would have to gravitate to infinity in a negative direction.As this is a positive number, although division cannot convert a positive number into a negative value, the value of W cannot exist.

If it is not possible for n1 to be equal to n2, it logically follows that it is impossible for n1 to be greater than n2.
Number n2 is always > n1 because two or more consecutive multiplications (increases) are impossible (due to the addition of number 1),while there are virtually no restriction how many times  a division can occur. Each multiplication converts the value into an even number followed by division (decrease).

 The number X that would go to infinity, would have to have the sum of the increases increasing  to infinity and the sum of the reduction increasing to infinity with the sum of the increasing being higher.Constant increase of X is possible only if the number of increases is equal to or greater than the number of reductions.If the number of reductions is greater than the number of increases, increase is not possible and it is only a question of the number of iterations when the initial value of X will fall to 1.
