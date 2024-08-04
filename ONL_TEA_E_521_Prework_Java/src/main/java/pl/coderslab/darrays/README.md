Remember to place solutions of the exercises in the appropriate `java` files prepared for the exercises. 

## Exercise 1


In the file `Main01.java`:

1. Create an array with **three int** elements. Name the array `threeElements`.
2. Put three numbers in it: 3, 4, and 5.
4. Print the elements of the array one by one on the console, separating them by a space.
5. Do not use a loop in this exercise.

Expected result:
```3 4 5```


## Exercise 2

In the file `Main02.java` create an array with a fruit list. Name the array `fruits`.  

Then:
1. Put three values in it: "apple", "banana", "berry".
2. Print the **first** fruit in the console.
3. In the next line in the console, print **the last fruit** (use `length`).
4. Print all fruits in a loop - **each element on a new line** (use `length`).

Expected result:
```
apple
berry
apple 
banana 
berry 
```


## Exercise 3

In the file `Main03.java`:

1. Create an array of `int` elements with values (4, 643, 112, 9999, 69 ), and call the array `numbers`.
2. Create a ```sum``` variable and assign the number `0` to it.
3. Use the ```for``` loop to calculate the sum of the numbers in the array.
4. Print the sum on the console, according to the pattern: `SUM: 10827.`.


## Exercise 4

In the file `Main04.java`:

1. Create an array with numbers (4, 643, 112, 9999, 69), and name the array `numbers`.
2. In a ```for``` loop, check which numbers are even and print them in the console **one under the other**.
3. Create an additional variable `sumOdd` with a value of `0`.
4. Modify the loop from point 1 so that it **additionally** adds up odd numbers.
5. Display an additional message in the console, according to the pattern: `SUM: 10711.`.

Expected result:
````
4
112
SUM: 10711.
````


## Exercise 5

In the file `Main05.java`:

1. Create an array with numbers (4, 643, 112, 9999, -69), and name it `numbers`.
2. Create a variable ```min``` and assign `0` to it.
3. Use a ```for``` loop to find the lowest number, assign it to the variable ```min``` and print it on the console.
4. To do this, iterate the array and check if a particular element is smaller than the current value of `min` - if so, update the `min` variable.

Expected result:
````
MIN: -69
````


## Exercise 6

In the file `Main06.java`:

1. Create an array with numbers (4, 643, 112, 9999, -69), and name it `numbers`.
2. Print the elements of the array starting from the end, using the ```for``` loop - each element on a new line.

Expected result:
````
-69
9999
112
643
4
````


## Exercise 7

The file `Main07.java` contains an array of temperatures.

1. The temperatures in the array are expressed in degrees Celsius - convert them to degrees Fahrenheit.  
   The conversion rate is: `tempCelc * 1.8 + 32`.
2. To do this, iterate the array and overwrite each temperature with a new calculated value.
3. Calculate the average temperature from the new calculated values and assign it to the `avg` variable.
4. Print it in the console in the following way: `AVERAGE: 3.95` - round the number to two decimal places.  
You can use the following method:
 ```java 
 String.format( "%.2f", variableToFormat );
 ```
