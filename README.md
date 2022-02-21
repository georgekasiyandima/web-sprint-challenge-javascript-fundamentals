# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge.

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results

### Commits

Set up codegrade early and commit your code regularly and meaningfully.

## Interview Questions

### (please edit this file and write your answer below each question.)

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each.

`.map` - with .map we can map each item in an array to something else and map returns a new array.
DESCRIPTION OF `.map`
Uses a callback function which is called for each item of the array.
The `.map` method callbacks takes three arguements namely: value, index, array.
After running the callback function on each item, the map method returns the transformed array, leaving the original array unchanged.
`.reduce` - method in arays we can reduce all the elements into a single value. The single value can be a number ,object e.t.c.
DESCRIPTION OF `.reduce`.
Example - Lets say we want to return a single value in an array of numbers.
The reduce method will take a call back function with two parameters the accumulator and currentValue.
The accumulator is something we initialize and the callback function is executed multiple times.
The currentValue will be set to each element in the array.
In each call we get the currentValue and its added to the accumulator so that we return the sum of accumulator and currentValue.
The reduce method will get the return result of (accumulator + currentValue) and store it in the accumulator.
Finally we get the the result as a single value and thats how `reduce` works.
`.filter`- The filter() method creates a new array filled with elements that pass a test provided by a function.
It also receives the similar arguments as map but the difference lies in the callback as it needs to return either true or false.
it takes five parameters:
callback: This parameter holds the function to be called for each element of the array.
element: The parameter holds the value of the elements being processed currently.
index: This parameter is optional, it holds the index of the currentValue element in the array starting from 0.
arr: This parameter is optional, it holds the complete array on which Array.every is called.
thisValue: This parameter is optional, it holds the context to be passed as this to be used while executing the callback function. If the context is passed, it will be used like this for each invocation of the callback function, otherwise undefined is used as default.
Return value: This method returns a new array consisting of only those elements that satisfied the condition of the arguement function.

2. Explain the difference between a callback and a higher order function.

Callbacks are a great way to handle something after something else has been completed. By something here we mean a function execution. If we want to execute a function right after the return of some other function, then callbacks can be used.
Callbacks are executed in some event or change of state.

Higher order function - A Higher-Order function is a function that receives a function as an argument otherwise returns function as output.

3. Explain what a closure is.

n JavaScript, a closure is a function that references variables in the outer scope from its inner scope.A child function keep the environment of the parent scope even after the parent function has already executed.

4. Describe the four principles of the 'this' keyword.

-default binding - this will refer to window context which it’s the default context.
-implicit binding - the object that is standing before the dot is what this keyword will be bound to.
-explicit binding - In this case, you can force a function call to use a particular object for this binding, without putting a property function reference on the object. so we explicitly say to a function what object it should use for this — using functions such as call, apply and bind
-new binding-when the new keyword is used(a constructor), this is bound to the new object being created.Properties and methods are added to the object referenced by this.

5. Why do we need super() in an extended class?

We need the super keyword in an extended class because it is used to call the constructor of its parent class to access the parent's properties and methods.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade.

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:

1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start`
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources

[Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://notion.so.bloomtech.BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
