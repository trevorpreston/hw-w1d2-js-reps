# Homework - JS Practice and Project HTML/CSS Draft

![](https://media.giphy.com/media/10bdAP4IOmoN7G/giphy.gif)

# Part 1 - Javascript Practice

For this assignment, complete the problems below and add your solutions to the README.md. 

To do this, fork this repo.  You do NOT need to clone it.

Then edit the ReadMe directly in Github.  I'll show you now!

DO NOT FORGET TO SCROLL DOWN TO THE BOTTOM AND HIT THE BIG GREEN "COMMIT NOW BUTTON" AFTER YOU FINISH.

then submit:

Since we did not clone it, there is no need for ANY git commands in the console.  Just skip right ahead to the "open pull request" step (the little button below the clone button) and answer the usual submission questions:

```
on a scale from 0 to 5, how complete is this homework?
on a scale from 0 to 5, how comfortable were you with this assignment?
what was a win you had with this assignment?
what was a challenge you had with this assignment?
other stuff on your mind? work with anyone? tell us about it! 
```

please don't forget to answer the submission questions when you submit!



## 1 - Activity Assignment
*Without running the following code*, try to determine:

```js
var a = 1;
var b = 'bongos';
var c = true;

a = b;
b = c;
c = a;
```

### Your solution here:
1.  What is `a`?
```
a is (your answerre)
```
2.  What is `b`?
```
b is (your answer here)
```
3.  What is `c`?
```
c is (your answer here)
```

Now run it and don't update your answers above.  Any surprises?  Don't worry about submitting wrong answers, it's all good :3

For the next problems, feel free to test out solutions in repl.it before putting your solutions in this readme!

## 2 - Activity Concatenation
Use the `+` operator to concatenate these strings together within a `console.log()`: "Please", "squeeze", "the", "cheese". __Make sure there are spaces in-between each word__.  Feel free to test this in repl.it.

```js
var firstWord = "Please";
var secondWord = "squeeze";
var thirdWord = "the";
var fourthWord = "cheese";
```
Result should be:
```js
"Please squeeze the cheese"
```

```js
// your answer here
```

## 3 - Variable Assignments

Output a console log `The sum of 5 and 10 is 15` where the values for 5 and 10 are saved to variables, and where 15 comes from those variables being summed.

```js
var num1 = 5;
var num2 = 10;
```

Let's do this in parts:
1. How can we make `num3` equal to the sum of `num1` and `num2`?
```js
// your solution here
```
2. Use variables `num1`, `num2` and `num3` to fill in the `console.log()` to complete the sentence: 

>The sum of 5 and 10 is 15

```js
console.log(/* your answer here */)
```

## 4 - Comparisons
By just looking at the following expressions, determine in your mind whether or not each will evaluate to true or false.  **Try and do this without running the code or using repl.it**!

### 4a: single operator
```
a) 999 > 999
b) 999 === 999 
c) 999 !== 999
d) -5 >= -4
e) 100 <= -100
f) 20 + 5 < 5 
g) 81 / 9 === 9
h) 9 !== 8 + 1
```


### Your solution here:
Write `true` or `false` based on the list above
```
a) 
b)  
c)
d) 
e) 
f) 
g) 
h) 
```

### 4b: multi-operator:
```
a) false || true
b) false && true
c) 'camel' === 'llama' && true
d) (6 > 8) || (7 > 6)
e) (true || false) && (true && true)
f) (20 + 5 < 30) && ('woof' !== 'meow') 
g) (81 / 9 === 9) && ('9' == 9)
h) (12 !== 12) || (9 !== 8 + 1)
```


### Your solution here:
Write `true` or `false` based on the list above
```
a) 
b)  
c)
d) 
e) 
f) 
g) 
h) 
```

## 5 - Conditionals:
Feel free to test your code in repl.it or a local javascript file.

*  Create a variable called b and assign it a random number between 0 and 100.
*  Write a conditional that matches the following conditions:
*
*   - if b is less than 25, print "bottom quartile"
*   - if b is between 25 and 50, print "lower quartile"
*   - if b is between 50 and 75, print "upper quartile"
*   - if b is between 75 and 100, print "top quartile"

```js
// your answer here
```

## 6 - Loops:
Feel free to test your code in repl.it or a local javascript file.

* Write code that logs "Love me, pet me! HSSSSSS!" 20 times.

* For every even number in your loop, log "...human...why you taking pictures of me?...", "...the catnip made me do it...", or "...why does the red dot always get away..." at random.

```js
  // your answer here 
```

## 7 - Arrays:

### 7a - Movies:
Feel free to test your code in repl.it or a local javascript file.


*  Create a variable `favoriteMovies` that is equal to an array of your 5 favorite movies:

```js
// your answer here
```

*  How would you replace the 3rd favorite movie with the value `Toy Story 3`?

```js
// your answer here
```

*   How would you remove the last movie from that array?
```js
// your answer here
```

### 7b - Yell at the Ninja Turtles
Feel free to test your code in repl.it or a local javascript file.

Create an array with the members of the ninja turtles (Donatello, Leonardo, Raphael, Michaelangelo)

Use a for loop to call .toUpperCase() on each of them and print out the result.

```js
// your answer here
```

Bonus: Modify the answer you just wrote. Instead of all letters being uppercase, make the letters alternate back and forth between uppercase and lowercase.
```js
// not required, but if you want a challenge!
// your answer here
```

## SUPER BONUSES 
**NOT REQUIRED NOT REQUIRED NOT REQUIRED NOT REQUIRED NOT REQUIRED NOT REQUIRED NOT REQUIRED NOT REQUIRED**
but you if you are hungry for more:

Triangles
declare a variable argument and set it equal to 7.

1. declare a variable `argument` and set it equal to 7.

2. Write a loop that console logs a "left isosceles" triangle (SEE BELOW) made of '#' that has the height and length of `argument`.

>Ex: `argument` is 7

```
#
##
###
####
#####
######
#######
```

2. Write a loop that console logs a "right isosceles" triangle (SEE BELOW) made of '#' that has the height and length of `argument`.  This is deceptively tricky. 

>Ex: `argument` is 7

```
      #
     ##
    ###
   ####
  #####
 ######
#######
```


3. Write a loop that console logs an "upside down left" isosceles triangle made of '#' that has the height and length of the argument.

>Ex: `argument` is 7

```
#######
######
#####
####
###
##
#
```

4. Write a loop that console logs an "upside down right" isosceles triangle made of '#' that has the height and length of the argument.  This is also tricky.

>Ex: `argument` is 7

```
#######
 ######
  #####
   ####
    ###
     ##
      #
```

5. Change the value of `argument` and reload your code and marvel at how you just solved a challenging problem and feel proud of yourself.


# Due Date and Time:

Your javascript exercises are due at 2am!

