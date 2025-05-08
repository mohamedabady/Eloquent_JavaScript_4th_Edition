# Introduction to Eloquent Javascript Edition 4

### Brief Intro About programming.

- programming is the act of constructing a program - which is a set of precise instructions telling a computer what to do in order to give the End User a certain value from its operations.

- Computers are dump machines. But the merit is that they can run very large number of small processes in a very short time, hence enabling us to build something that resonates with human logic and thinking.

- A programming language is an artificially constructed medium through which human mind can instruct the computer what to do. Now programming languages evolved to be as if we are writing readable English text.

### Act of Programming

- Programming is found to be Hard by the majority of practitioners. The logic says that Programming Languages have set of rules and we should follow them to create our programs. But the issue is that when we build the programs, they start to be like a maze and we can easily get lost into it. Learning how to deal with Language rules are the patterns that help us create efficient programs that are in the same time easy to read and understand.

- A program is a piece of text written by a programmer. It's also the driving force behind the computer action. It's also the data stored in computer memory. But in general, a program can be compared to a machine where several individual parts are put together to make a final valuable output.

- Programming is a practice of mind. Programs grow under our hands while typing code. But as a program grows, so does it's complexity. So the valuable skill here is how to manage to create interesting programs that tend to be easy to read and understand.

- Best Practices in Programming. It's true that professional programmers who dived deep with the programming language were able to derive some patterns or techniques of how to build efficient programs. But this approach doesn't work all the time. Challenges of human life are always in an ever-changing state, hence new challenges require new solutions. Of course, you need to make mistakes and this sharpen your skills in understanding programs and how programming should be.

### Why Language Matters

- The first machine to be called a computer was built on data being fed to the machine as 0 and 1 which means false and true. These were the punch cards. Hence, the written representation of a sequence of instructions was a large array of 0s and 1s. 

- With the advancement of technology and building compilers, we were able to make representation a bit more friendly to human logic. 

**Example: sum the range of numbers from 1 to 10**

- iteration 1 :   
00110001 0000000 0000000  
00110001 0000001 0000001  
...    --> not interested in following that i Guess !  

- iteration 2 : translation of  each line of 0s and 1s to English scentence instruction:  

1- Store the number 0 in memeory in location 0.  
2- store the number 1 in memory in location 1.  
3- store the value of memory location 1 in memory location 2.  
4- subtract number 11 from the value in memory location 2.  
....  

- iteration 3 : introducing names that are more readable and resonate about.

``` 
    Set "total" to 0.
    Set "count" to 1.
[loop]
    Set "compare" to "count".
    Subtract 11 from "compare".
    If "compare" is 0, continue at [end].
    Add "count" to "total"
    Continue at [loop].
[end]
    Output "total"
```

- iteration 4 : if we need to translate this program to javascript we can write : 

```
let total=0, count=1;

while(count <= 10){
    total+=count;
    count+=1
}

console.log(total)

// -> 55
```

- iteration 5 : when we get to know functions and modules in javascript we can creat `range()` function and `sum()` function.  
Then our program will look like : 
```
console.log(sum(range(0,10)))

// -> 55
```

- we get to a conclusion that a good programming language enables people to talk about the actions that the computer has to perfrom in a higher level. This is done by omitting details, providing building blocks eg: `while` and `console.log()`. Also by allowing programmer to build his own blocks like `sum()` and `range()`.


### What is JavaScript

- It was introduced in 1995 to add programs to wbe pages in the NetScape Navigator browser. 

- 