# A-B-for-Input-Output-Practice-III-

A+B for Input-Output Practice (III)

Problem Description

Your task is to Calculate a + b.

 
Input

Input contains multiple test cases. Each test case contains a pair of integers a and b, one pair of integers per line. A test case containing 0 0 terminates the input and this test case is not to be processed.

 
Output

For each pair of input integers a and b you should output the sum of a and b in one line, and with one line of output for each line in input.  


Sample Input

1 5

10 20

0 0 


Sample Output

6

30

解答：

#include<stdio.h>

 main()
 
 {
 
    int a,b;
    
    scanf("%d %d",&a,&b);
    
    while(!(a==0&&b==0))
    
    {
    
    printf("%d\n",a+b);
    
     scanf("%d %d",&a,&b);
     
    }
    
 }
 
