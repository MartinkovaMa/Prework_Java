Remember to place solutions of the exercises in the appropriate `java` files prepared for the exercises.  

## Exercise 1


1. In the `Main01.java` file, create two variables, named `no1` and `no2`, which will store integers with values of `3` and `7`.
2. Then use the conditional statement ```if ... else``` to print out in the console which one of them is greater.
3. Print the text according to the pattern: `The greater number is 7`.


## Exercise 2


1. In the `Main02.java` file, create three variables named `no1, no2, no3` which will store integers with values 3, 7, 11.
2. Then use the conditional statement `if ... else if ... else` to print out which one is the greatest number.
3. Print the text according to the pattern: `The greatest number is 11`.


## Exercise 3


1. In the file `Main03.java` create a loop that will print out **Java** 3 times in the console.
2. Write both a `for` and a `while` loop.
3. The text will be displayed 6 times in total.

Expected result:
````
Java
Java
Java
Java
Java
Java
````


## Exercise 4


1. In the `Main04.java` file, create a loop that prints numbers from 1 to 10 in a single line in the console.
2. Write both a `for` and a `while` loop.
3. 20 numbers will be printed out in total.

Expected result:
````
1 2 3 4 5 6 7 8 9 10 
1 2 3 4 5 6 7 8 9 10 
````


## Exercise 5


1. In the file `Main05.java` create variables `resultFor` and `resultWhile` and assign the number `0` to them.
2. Then create a loop that adds numbers from 1 to 10 and assigns the result to the `resultFor` or `resultWhile` variable.
3. The loop should add the next number from the specified range to the `resultFor` or `resultWhile` variable in each iteration.
4. Write both a `for` and a `while` loop.
5. Print out the variables: `resultFor` and `resultWhile` in separate lines in the console.

Expected result:
````
55
55
````


## Exercise 6


1. In the `Main6.java` file write code which, based on the value of the variable `n` ( `int n = 6;`), displays all numbers from zero to **n**.
 For each number, print out whether it is even or odd.  

Pattern:

```
0 – even
1 – odd
2 – even
3 – odd
...
```

Write both a `for` and a `while` loop.

*Hint: How to check if a number is even or odd?
 Just calculate the remainder of its division by `2`.
 If the result is 0, then the number is even; otherwise it is odd.*

Expected result:
````
0 - even
1 - odd
2 - even
3 - odd
4 - even
5 - odd
6 - even
0 - even
1 - odd
2 - even
3 - odd
4 - even
5 - odd
6 - even
````


## Exercise 7

1. In the file `Main07.java` create two independent loops and print out their counter values in each iteration for `i < 3` and `j < 3`.
2. Use: ```System.out.println("i = " + i + " j = " + j);```.
3. Do this exercise using two `for` loops.

*Hint: The principle of creating nested loops (dependent and independent) is discussed in the article
 **Loops for and while** in the section **Flow control**. If you have any doubts, study this article again.*
 
Expected result:
```
i= 0 j= 0
i= 0 j= 1
i= 0 j= 2
i= 1 j= 0
i= 1 j= 1
i= 1 j= 2
i= 2 j= 0
i= 2 j= 1
i= 2 j= 2
```


## Exercise 8

In the file `Main08Sample`, there is a program that prints out in the console a pattern made up of `n` stars, as shown below.  
Analyze it very carefully.

Example for ```n = 5```:

```
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *
```

Nested loops are used for this exercise!

In the `Main08.java` file, write a program that will draw, based on the value of the variable `n`, the following pattern for `int n = 5;`, as written in the method main:

```
* 2 3 4 5
* * 3 4 5
* * * 4 5
* * * * 5
* * * * *
```


To create such a pattern, in the middle of the nested loop, use the conditional statement `if` to decide whether to print out an asterisk (star) or the counter from the nested loop.


## Exercise 9


In the file `Main09.java` write a program that will draw, based on the value of the variable `n`, a pattern like the one below, for `int n = 5;`, as written in the method main.

```
*
* *
* * *
* * * *
* * * * *
```

You can do this exercise in two ways:

1. using dependent loops,
2. using independent loops and conditional `if` statement.

*Use your solutions for the previous exercises, modify them. You will need to think a little and understand nested loops here.* 



## Exercise 10

In the `Main10.java` file, write a program that will draw, based on the value of the variable `n`, the following pattern, (here for ```n = 5 ```):

```
* 2 3 4 5
* * 3 4 5
* * * 4 5
* * * * 5
* * * * *
* * * * *
* * * * 5
* * * 4 5
* * 3 4 5
* 2 3 4 5
```

To create such a pattern, in the middle of a nested loop use the `if` conditional statement to decide whether to print out an asterisk or the counter from the nested loop.
