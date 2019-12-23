# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your team lead

1. Describe the biggest difference between `.forEach` & `.map`.

    The methods, .forEach and .map are similar in that they execute a function invoked upon each element of the array. The difference is that .forEach doesn't return a new array and allows for array mutation, while .map returns a new array.

2. What is the difference between a function and a method?

    A function and a method are both pieces of code the can be invoked by name. The main difference between them is that data passed into a function is explicitly passed whereas the method is implicity passed data based on the object it was invoked upon. There isn't much difference between them, but the big one being that methods are assoicated with object invocation.

3. What is closure?

    Closure in JavaScript is basically the ability of a function to have access to outer variables within it's scope chain to the global scope going up (out towards parent and not down to children). Closure is when an inner function can access variable from the parent function and the global scope. But the inverse does not work. A function, does not have access to the variables within another function of a different scope OR the variables declard by it's children (inner) functions. Variables can be passed 'down' (to children functions) but not the inverse 'passed up'. 



4. Describe the four rules of the 'this' keyword.

    - The 1st principle of the 'this' keyword is default or global binding. Global binding means that the 'this' keyword refers to the object of the console.
    - The 2nd principle is Implicit binding. Implicit binding refers to the object referenced before (to the left) the dot when being invoked.
    - The 3rd is Explicit binding which is the type of binding 'this' becomes while using JavaScript's methods apply or call. When we call specific objects with .call or .apply functions, 'this' refers to them explicitly. 
    - The 4th is New Binding which is when when we use object constructor functions, 'this' then refers to a specific instance of an object being referred to. In this case 'this' refers' to constructor function that create 'new' objects, hence new binding.

5. Why do we need super() in an extended class?

    We need the super() method in extended classes so that the constructor function inherits the properties already set in place by it's parent constructor function.

## Project Set up

Follow these steps to set up and work on your project:

- [x] Create a forked copy of this project.
- [x] Add TL as collaborator on Github.
- [x] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [x] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [x] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [x] You are now ready to build this project with your preferred IDE
- [x] Implement the project on your Branch, committing changes regularly.
- [x] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [x] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [x] Add your team lead as a Reviewer on the Pull-request
- [x] TL then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
