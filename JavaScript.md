![](https://hackernoon.com/hn-images/1*bxEkHw1xewxOFjmGunb-Cw.png)
# JavaScript & jQuery

How JavaScript make web pages more interactive?
1. Access content
2. Modify content
3. Program Rouls
4. React to event

![](https://cdn-images-1.medium.com/max/2000/1*OF0xEMkWBv-69zvmNs6RDQ.gif)

- JavaScript can reload the content of page without reload the paage itself.
- Filtering data

## The ABC of prgramming
1. A - Whatt is a script and how do I create one?
2. B - How do computter fit in with the world around them?
3. C - How do I write a script for a web page?

A script is a series of insttructions that a computer can follow tto achive goals

To write a script you need to first state your goals and then list tthe tasks that need to be completed in order to achive it.


_start with big picture of what you want to achieve, and break that down into smaller steps._

1. DEFINE THE GOAL
First, you need to define the task you want to achieve. You can think of this as a puzzle for the computer to solve.

2. DESIGN THE SCRIPT
To design a script you split the goal out into a series of tasks that are going to be involved in solving this puzzle. This can be represented using a flowchart.

3. CODE EACH STEP
Each of the steps needs to be written in a programming language that the compu ter understands. In our case, this is JavaScript.


![](https://media.giphy.com/media/GVd19DZmvRO80/giphy.gif)
## FROM STEPS TO CODE
Every step for every task shown in a flowchart needs to be written in a language the computer can understand and follow.
Just like learning any new language, you need to get to grips with the:
1. __Vocabulary:__ The words that computers understand
2. __Syntax:__ How you put those words together to create instructions computers can follow


You need to learn to "think" like a computer because they solve tasks in different ways than you or I might approach them

For example, when you look at the picture on the left how do you tell which person is the tallest? A computer would need explicit, step-by-step instructi0ns, such as:
1. Find the height of the first person
2. Assume he or she is the "tallest person"
3. Look at the height of the remaining people one- by-one and compare their height to the "tallest person" you have found so far
4. At each step, if you find someone whose height is greater than the current "tallest person", he or she becomes the new "tallest person"
5. Once you have checked all the people, tell me which one is the tallest


# EXPRESSIONS
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.

- EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
```
var color = 'beige';
//The value of co1or is now beige
```

- EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE
```
var area = 3 * 2;
//The value of area is now 6.
```

![](https://i1.wp.com/pandabunnytech.com/wp-content/uploads/2018/11/types-of-statements-in-javascript-e1543313160116.png)
# OPERATORS
Expressions rely on things called operators; they allow programmers to create a single value from one or more values.

- ASSIGNMENT OPERATORS
```
color = 'beige';
```

- ARITHMETIC OPERATORS
```
area = 3 * 2;
```

- STRING OPERATORS
```
greeting= 'Hi 1 + 'Molly';
```

- COMPARISON OPERATORS
```
buy = 3 > 5;
```

- LOGICAL OPERATORS
```
buy= (5 > 3) && (2 < 4);
```

## USING ARITHMETIC OPERATORS
```
var subtotal = (13 + 1) * 5;
var shipping = 0.5 * (13 + 1) ;

var total = subtotal + shipping;

var elSub = document.getElementByid('subtotal ');
elSub.textContent =subtotal ;

var elShip =document.getElementByid('shipping');
elShip.textContent =shipping;

var elTotal = document.getElementByid('total ');
elTotal .textContent =total;

```

## STRING OPERATOR
```
var firstName = 'Ivy ';
var lastName = ' Stone' ;
var fullName = firstName + lastName;
```

__MIXING NUMBERS AND STRINGS TOGETHER__

When you place quotes around a num~er, it is a string (not a numeric data type), and you cannot perform addition operations on strings.
```
var costl = '7';
var cost2 = '9';
var total = costl + cost2;
```

If you try to add a numeric data type to a string, then the number becomes part of the string, e.g., adding a house number to a street name:
```
var number = 12;
var street= 'Ivy Road'; 
var add = number + street
```

If you try to use any of the other arithmetic operators on a string, then the value that results is usually a value called NaN. This means "not a number."
```
var score= 'seven';
var score2 = 'nine';
var total = score * score2;
```

## USING STRING OPERATORS

_JaavaScript_
```
var greeting= 'Howdy ';
var name= 'Molly';
var welcomeMessage = greeting+ name+ '!';
var el =document.getElementByld('greeting'); el .textContent = welcomeMessage;
```

_HTML_
```
<hl>Elderflower</ hl> 
<div id="content">
    <div id="greeting" class="message">Hello 
        <span id="name">friend</span>!
    </div>
</div>
<script src="js/string-operator.js"></script>
```

![](https://chrissainty.com/content/images/size/w2000/2019/02/blazor-bites-javascript-interop.jpg)
# Functions

__WHAT IS A FUNCTION?__
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

### A BASIC FUNCTION
```
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
    var el = document.getElementByld('message'};
    el .textContent = msg; 
}
updateMessage(};
```

In this example, the user is shown a message at the top of the page. The message is held in an HTML element whose id attribute has a value of message. The message is going to be changed using JavaScript.

To call the function whe do like this `FunctionName();`


![](https://i2.wp.com/www.helloitsliam.com/wp-content/uploads/2018/06/062318_1553_IsJavaScrip1.png?ssl=1)
### Declaring a function with Args
```
function MyFunction(width, height) {
    return widtth * height;
}
```
And to call this function like `MyFunction(3, 5);`