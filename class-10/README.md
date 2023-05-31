# JS Debugging and More CSS Layout

## Overview

Learning how to **debug** your code will help you to better identify the errors you see in your console, and how to fix them.

## Class Outline

- Code demo
  - Debugging workflow
- Lab preview and prep

## Learning Objectives

### Students will be able to

Understand error codes like:

* SyntaxError: Unexpected end of input
* ReferenceError: x is not defined
* TypeError: Cannot read properties of undefined 

TypeError example

    let seattle = new Store();
    let x = sattle.maxCust;
    // ERROR MESSAGE:
    // TypeError: Cannot read properties of undefined (reading 'sattle’)

ReferenceError example

    let aveCookies = 2.3;
    let total = cust * avecookies;
    // ERROR MESSAGE:
    // ReferenceError: avecookies is not defined

SyntaxError example 

    let day = "Friday";
    let s = `Today is ${day !!!`;
    // ERROR MESSAGE:
    // SyntaxError: Unexpected end of input

Replit for Bug Hunting: [https://replit.com/team/code-201-n1/NodeCookieShopWithBugs](https://replit.com/team/code-201-n1/NodeCookieShopWithBugs)

#### Describe and Define

- Response design principles
- Software execution call stack
- JavaScript debugging tools and methodologies

#### Execute

- Create an accurate CSS layout from a comp image.
- Demonstrate understanding of a variety of JS debugging techniques.
  - `console` messages (error, warn, info)
  - The `debugger` statement
- Produce quality code using a proper debugging methodology.

## Notes

1. What are a few ways we can debug our code?

1. What are some of the error types you may encounter in the console?

### Major Browsers' Debugging Tools

**Keyboard**:

1. Windows: `ctrl` + `shift` + `i`

1. macOS: `command` + `option` + `i`

**Chrome**:

1. Open the browser.

1. From the menu, select "More Tools".

1. From tools, choose "Developer Tools".

1. Select Console.

**Firefox**:

1. Open the browser.

1. From the menu, select "Web Developer".

1. Select "Web Console".

**Safari**:

1. Go to Safari, Preferences, Advanced in the main menu.

1. Check "Enable Show Develop menu in menu bar".

1. From the Develop menu, select "Show Web Inspector".

## Video about breakpoints

You can debug with breakpoints in the browser. Breakpoints let you stop the code at a certain point, and examine what is going on.

[Udemy Course "Devtools Pro" Section 1 part 7 "Souces Tab and Basic Debugging"](https://www.udemy.com/course/devtools-2017-the-basics-of-chrome-developer-tools/learn/lecture/6871494#overview)

[Youtube: Debugging JavaScript - Chrome DevTools 101](https://www.youtube.com/watch?v=H0XScE08hy8)


## Array methods

You can do a lot of things with loops and arrays. But arrays also have methods you can use, too.

[Array Method Tutorial](https://javascript.info/array-methods)

[Video: Array methods](https://www.youtube.com/watch?v=HOc49cbm-68)

[Replit: Array methods](https://replit.com/team/code-201-n1/Array-Methods-1)


## JavaScript Review Slides

Please review these slides. You can copy them and add them to your Badgr slide deck. Please ask questions about anything you see in them that you want to understand more deeply.

[Link to slides](https://docs.google.com/presentation/d/17bU73pZre745DzZzZW7IzfX5NTjte0YwC-ESUcOjOuA/edit?usp=sharing)