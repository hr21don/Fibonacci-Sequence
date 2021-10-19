# Fibonacci-Sequence
In mathematics, the Fibonacci numbers are the numbers in the following integer sequence, called the Fibonacci sequence, and characterized by the fact that every number after the first two is the sum of the two preceding ones
## Starting Condition
Given a number N return the index value of the Fibonacci sequence, where the sequence is 
1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, …

Every number is the sum of the previous number for e.g. 
 
 * 0 + 1 = 1
 * 1 + 1 = 2
 * 1 + 2 = 3 ...etc

The first two numbers of the condition must be 0 and 1.

## First Solution Implementation

function fibonacci(n){
    for(var fibonacciArray = [0,1], i=0,j=1,k=0; k<n;i=j,j=x,k++ ){
        x=i+j;
        fibonacciArray.push(x);
    }
    console.log(fibonacciArray);
}

//calling fibonacci
fibonacci(50)

## Recursive Solution Implementation
