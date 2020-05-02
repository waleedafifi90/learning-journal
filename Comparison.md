![](https://simplesnippets.tech/wp-content/uploads/2018/10/operators-in-javascript-featured-image-1280x720.jpg)
# Comparison and logical operators

## Javascript Operators
JavaScript includes operators as in other languages. An operator performs some operation on single or multiple operands (data value) and produces a result. For example 1 + 2, where + sign is an operator and 1 is left operand and 2 is right operand. + operator adds two numeric values and produces a result which is 3 in this case.

```
<Left operand> operator <right operand>

<Left operand> operator
```

### JavaScript includes following categories of operators.
1. Arithmetic Operators
1. Comparison Operators
1. Logical Operators
1. Assignment Operators
1. Conditional Operators


### Arithmetic Operators
| Operator	    | Description                                           | 
| ------------- | ----------------------------------------------------- |
| +	            | Adds two numeric operands.                            |
| -	            | Subtract right operand from left operand              |
| *	            | Multiply two numeric operands.                        |
| /	            | Divide left operand by right operand.                 |
| %	            | Modulus operator. Returns remainder of two operands.  |
| ++	        | Increment operator. Increase operand value by one.    |
| --	        | Decrement operator. Decrease value by one.            |


__Example: Arithmetic Operator__
```
var x = 5, y = 10, z = 15;

x + y; //returns 15

y - x; //returns 5

x * y; //returns 50

y / x; //returns 2

x % 2; //returns 1

x++; //returns 6

x--; //returns 4
```

__Example: + operator__
```
var a = 5, b = "Hello ", c = "World!", d = 10;

a + b; // "5Hello "

b + c; // "Hello World!"

a + d; // 15
```


### Comparison Operators

JavaScript language includes operators that compare two operands and return Boolean value true or false.

![](https://res.cloudinary.com/practicaldev/image/fetch/s--iAbnVv87--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://cl.ly/7d9cf8370380/Image%25202018-11-15%2520at%25209.59.47%2520AM.png)

| Operator	    | Description                                                                                                       | 
| ------------- | ----------------------------------------------------------------------------------------------------------------- |
| ==	        | Compares the equality of two operands without considering type.                                                   |
| ===           | Compares equality of two operands with type.                                                                      |
| !=            | Compares inequality of two operands.                                                                              |
| >             | Checks whether left side value is greater than right side value. If yes then returns true otherwise false.        |
| <	            | Checks whether left operand is less than right operand. If yes then returns true otherwise false.                 |
| >=	        | Checks whether left operand is greater than or equal to right operand. If yes then returns true otherwise false.  |
| <=	        | Checks whether left operand is less than or equal to right operand. If yes then returns true otherwise false.     |


__Example: Comparison Operators__
```
var a = 5, b = 10, c = "5";
var x = a;

a == c; // returns true

a === c; // returns false

a == x; // returns true

a != b; // returns true

a > b; // returns false

a < b; // returns true

a >= b; // returns false

a <= b; // returns true

a >= c; // returns true

a <= c; // returns true
```


### Logical Operators

Logical operators are used to combine two or more conditions. JavaScript includes following logical operators.

| Operator	    | Description                                                                                                       | 
| ------------- | ----------------------------------------------------------------------------------------------------------------- |
| &&	        | && is known as AND operator. It checks whether two operands are non-zero (0, false, undefined, null or "" are considered as zero), if yes then returns 1 otherwise 0.                                                   |
| ||           | || is known as OR operator. It checks whether any one of the two operands is non-zero (0, false, undefined, null or "" is considered as zero)                                                            |
| !            | ! is known as NOT operator. It reverses the boolean result of the operand (or condition)                           |

__Example: Logical Operators__
```
var a = 5, b = 10;

(a != b) && (a < b); // returns true

(a > b) || (a == b); // returns false

(a < b) || (a == b); // returns true

!(a < b); // returns false

!(a > b); // returns true
```



# Loops

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Loops-1280x720.jpg)

## JavaScript for Loop

JavaScript includes for loop like Java or C#. Use for loop to execute code repeatedly.

```
for(initializer; condition; iteration)
{
    // Code to be executed
}
```

__The for loop requires following three parts.__
1. Initializer: Initialize a counter variable to start with
1. Condition: specify a condition that must evaluate to true for next iteration
1. Iteration: increase or decrease counter

![](https://media.geeksforgeeks.org/wp-content/uploads/Loop1.png)
__Example: for loop__
```
for (var i = 0; i < 5; i++)
{
    console.log(i);
}
```

- Output:
` 0 1 2 3 4 `

### Points to Remember :
1. JavaScript for loop is used to execute code repeatedly.
1. for loop includes three parts: initialization, condition and iteration. e.g.for(initializer; condition; iteration){ ... }
1. The code block can be wrapped with { } brackets.
1. An initializer can be specified before starting for loop. The condition and increment statements can be included inside the block.


## JavaScript while loop
JavaScript includes while loop to execute code repeatedly till it satisfies a specified condition. Unlike for loop, while loop only requires condition expression.

_Syntax:_
```
while(condition expression)
{
    /* code to be executed 
    till the specified condition is true */
}
```

__Example: while loop__

```
var i =0;

while(i < 5)
{
    console.log(i);
    i++;
}

//Output: 0 1 2 3 4

```

As you can see in the above example, while loop will execute the code block till i < 5 condition turns out to be false. Initialization statement for a counter variable must be specified before starting while loop and increment of counter must be inside while block.

