# Code 201 Review, Code 301 Preview, and Project Week Kickoff

## Overview

In this class you will be getting a preview of 301 curriculum and introduced to project week.  You'll also be completing a lab that will walk you through git workflow and handling merge conflicts.

## Learning Objectives

Review concepts from Code 201 and get ready for 301.

### JavaScript Fundamentals

    // declare and assign the string "John to" name.
    let name = "John";  

    console.log( typeof name );

    const nums = [1, 2, 3, 4, 5];

    for( let i=1; i<= 100; i++ ) {
      console.log(i * i);
    }

### JavaScript Object


    // creating an object literal
    const john = {
      first: "John",
      last: "Cokos",
      lastName: "Cookoo",
      age: 50
    }

    // prints out the property of "first"
    // it will be "John"
    console.log(john.first);
    
    // access a property of an object with the bracket notation
    const keyword = "last";
    console.log(john[keyword]);   
    console.log(john["last"]); // the same as above
    console.log(john.last);    // the same as above


### Functions

    // define a function
    function sayHi(name) {
      console.log('Hi', name);
    }

    // invoke or "call" a function
    // call it with the string "Lyndsey"
    sayHi("Lyndsey");

    let names = ["Robert", "John", "Thomas"];
    sayHi(names[0]);
    sayHi(names[1]);
    sayHi(names[2]);

    for(let i=0; i<names.length; i++) {
      sayHi(names[i]);
    }

## Constructors



```
function Person(name) {
  this.fullName = name;
}
```

```
Person.prototype.sayMyName = function() {
  console.log( this.fullName.toUpperCase() );
}
```

```
// create a new instance of Person.
const john = new Person('John Cokos');

// create a new instance of Person.
const robert = new Person('Robert McCreary');

robert.fullName === "Robert McCreary"; // true
```

```
john.sayMyName();
robert.sayMyName();
```

```
// preview of 301.
class Person {
  constructor(name) {
    this.fullName = name;
  }
  sayMyName(){
    console.log(this.fullName.toUpperCase())
  }
}
```

## Javascript for Fun and Profit

```
console.log( greet('John') );

function greet(name) { 
  return sayHelloTo(name, 'Hi');
}

function sayHelloTo(person,greeting) {
  return awkwardGreeting(greeting, person);
}

function awkwardGreeting(words,name) {
  return `${name}, uh ... ${words}?`
}
```

```
// array functions
"These are some words".split(' ')[3].toUpperCase().charAt(0)
```

```
// string functions
"Hello world".charAt(Math.sqrt(16));
```

```
// putting things together...Try this in your Chrome Console!
({ type: "a", href: "http://swapi.co", text: "Star Wars API" })["type href text".split(" ")[Math.max(2, 0)]].length
```

## CSS Position

Take a look at this Replit and play with the different types of position attributes.
https://replit.com/team/code-201-n1/CSS-Position

```
img.float-left {
  float: left;
}
```

```
/* This will stay on the screen even if you scroll up or down */
.fixed-bottom-left {
  display: fixed;
  bottom: 50px;
  left: 30px;
}
```

```
/* This will move as you scroll up or down */
.fixed-bottom-left {
  display: absolute;
  bottom: 50px;
  left: 30px;
}
```

https://replit.com/team/code-201-n1/CSS-Position

```
/* This will change the meaning of height and width when padding is added */
div {
  box-sizing: border-box;
} 
```




### Students will be able to

As a result of completing Lecture 15 of Code 201, students will:

#### Describe and Define

- 301 basic structure and expectations
- How to successfully integrate Git and GitHub into a team code project

#### Execute

- Locate and utilize resources for self-study before beginning Code 301.
- Define a team agreement and establish collaborative process with a team.

## Today's Outline

- Announcements
  - Reminder: weekly surveys will go out today
- Discuss upcoming Career Coaching assignments
- Code Review
- Review Exam
- Code 301 Preview
- Final Project Overview

## Notes

### 301 Preview

Lots of good stuff coming up in Code 301! You'll learn to build MERN apps and deeper exploration of how the web works.

#### Structure of 301

- Pair programming
- Daily code challenges
- 3 modules of app building
- A final project, deployed to the cloud!

## Final Project Overview

1. Go over the final project description.
1. Discuss GitHub workflow in teams.
1. GitHub Issues & Projects are the best way to organize your project work.
