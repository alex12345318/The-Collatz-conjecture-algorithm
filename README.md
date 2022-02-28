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
  
  
  
  
