# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from a `JSON` object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in Preprocessing, and JavaScript Basics.

> You have **three hours** to complete this challenge. Plan your time accordingly.

## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You are free to work with the full data set as a stretch goal.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. How would you describe preprocessing to someone new to CSS?

Preprocessing is basically a better way of coding than only using CSS. For someone new to CSS, we use a preprocessor like LESS which is a new, different language that has more robust syntax and helps make our code become more DRY. LESS is compiled through JavaScript into something that fits into and is readable to CSS.

2. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?

Most favorite concept in preprocessing is the parametric mixin, because it allows us to reduce lines of code into something simple and beautiful. The concept that gives me most trouble is Functions because it’s not covered much on TK in Preprocessing module, only examples given were darken() and lighten(), so I’m still not very familiar with functions. 

3. How would you explain the concept of a variable to someone new to programming?

To someone new at programming, a variable may be like giving a category to something. For example, at the strawberry farm, we see small, medium, and large strawberries. We can create a variable, e.g. largeStrawberry, that represents different shapes and types of large strawberries, e.g. maybe some that look like “Dumpling Strawberry”, “Cone Strawberry”, and such. We can set keywords to decide whether we want our variables to change (var, let) or stay as it is (const).

4. What is the purpose of using functions in code?

We use functions in code to accomplish a task that we likely will want to repeat again and again. Functions help simplify these tasks into a few lines of codes which otherwise may be a lot longer and tedious. 

5. What is JSON data?

JSON is Java Script Object Notation, a way to store and exchange data from browser to server. A text - usually uses quotations “” and can be converted into JS objects, vice versa.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set Up

Follow these steps to set up your project:

- [ ] Create a forked copy of this project.
- [ ] Add your Team Lead as collaborator on Github.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Add a viewport meta tag to the head of your index.html page.
* [ ] Add responsive breakpoints to your code for 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.

### Task 3: Stretch Problems

> Include stretch goals in this section. These are additional things the student can do go beyond basic proficiency, and push their scores on the challenge up to a 3. Be clear that these are *not* required. Completing all of the tasks in the required section must be sufficient to  demonstrate proficiency of all sprint objectives, and earn a score of '2. 

> Example stretch goals below:

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Use JavaScript to programmatically create HTML elements in the console and copy them to display all 20 artists on the page
* [ ] Create a function called `randomize` that takes a data array as an argument and returns a the same array in a randomized order.
* [ ] Use advanced array methods (.map, .reduce, .filer) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example)
* [ ] Add responsive breakpoints to your code by using media queries
* [ ] Add CSS animations

## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master
