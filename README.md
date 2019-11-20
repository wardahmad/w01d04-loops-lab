# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
ANSWER HERE
```
for (var i = 0; i <= 100; i++){
    console.log(i)
}

<br>

## Print every number from 10 to 0

```
ANSWER HERE
```
for (var i =10; i >= 0; i--){
    console.log(i);
}
<br>

## Print every number from 4 to -16

```
ANSWER HERE
```
for (var i = 4; i >= -16; i--){
    console.log(i)
}
<br>

## Print every fifth number from 8 to 41

```
ANSWER HERE
```
for (var i = 8; i <= 41; i = i + 5){
    console.log(i)
}
<br>

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
ANSWER HERE
```
for (var i =1; i <= 100; i++){
    if ((i % 3 === 0) && (i % 5 === 0)){
        console.log("Fizzbuzz");
    }else if (i % 3 === 0){
        console.log("Fizz");
    }else if (i % 5 === 0){
        console.log("Buzz");
    } else {
        console.log(i);
    }
}
<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
ANSWER HERE
```
for (var i = 0; i <= 20; i++){
    if (i === 0){
        console.log(i)
    } else {
        if (i % 2 === 0){
            console.log(i+" is even");
        }else {
            console.log(i);
        }
    }
}
<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
ANSWER HERE
```
for (var i = 0; i <= 10; i++){
    console.log(i+" * 9 = "+(i*9))
}
<br>


