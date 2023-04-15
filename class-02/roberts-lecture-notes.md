# Class 02

## JavaScript and typing

In JavaScript we can use different 
types in the same variable.

    let name = "John";
    name = 'Jim';
    name = `Jerry`;

    // loose typing
    // dynamic typing
    name = 0; // OK!
    name = true // OK!


## Data Types in JavaScript

There are several data types in JavaScript:
boolean, number, string, array, object

Types in other languages like C: *characters*, *integers*

## Undefined and null

Any variable can be `undefined` or `null`. (In some languages, there is no `undefined`, they only have `null`.)

    let name;
    console.log("My name is: " + name);
    // My name is: undefined

    name = "Robert";
    // My name is: Robert

    name = null;
    // My name is: null

    name = undefined;
    // My name is: undefined

## If and Else

    // By the way, also false...
    // 0, null, undefined, '', false
    // But it's better to just use T/F
    let hungry = true;
    let thirsty = true;
    
    if(hungry) {
      console.log("Eat some fries.");
    } else if (thirsty) {
      console.log("Drink water.");
    } else {
      console.log("Hang out.");
    }


## Checking for Equality

We can use `===` to check if two things are equal.
   
    console.log("Hello.")
    let name = "Robert";
    if(name === "Robert") { // true
      console.log("You are the teacher.");
    } else {
      console.log("You are a student.");
    }


## Links

Replit: https://replit.com/@rmccrear/Class-02-Lecture-If-Else#index.js

Vocabulary Practice: https://quizlet.com/793042870/class-02-css-terms-flash-cards/


## GitHub Authorization

After following the two steps below, you should be able to push to your GitHub repositories.

Install GitHub CLI: https://github.com/cli/cli#installation

    brew install gh

Authorize your computer to connect to GitHub: https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git#github-cli

    gh auth login

