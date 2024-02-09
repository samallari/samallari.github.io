---
layout: essay
type: essay
title: "Say No More to Fuzzy Code: Cleaning Up with ESLint"
# All dates must be YYYY-MM-DD format!
date: 2024-02-08
published: true
labels:
  - JavaScript
  - ESLint
---

## Before University
Before university, I would write code however I wanted. As a beginner programmer, it was more important to me that my code worked rather than be readable or pretty to look at. When it came to being neat, I was more of an "organized mess" type of person. As long as I knew where everything was and I knew what it did, I was okay with that. As I wrote more code, I started to realize the importance of indentation, spaces, and curly brace placements. Debugging code is easier when the code is easier to read. I once tried to look at a file I wrote years ago to remember how I did something, but when I took a look at it, I had no idea what was going on. That's when I realized that I needed coding standards. Nowadays, I try to write code that's concise and easy to follow because I'm no longer the only person looking at my code. 

## Standardizing Code?
 As I entered university and started my Computer Science courses, I learned that there are coding standards that emphasize good practices in programming. I get why some people grumble over coding standards, but I think coding standards makes you a smarter and better programmer. As a beginner, reading documentation about coding standards may seem like a daunting task. It feels like an endless scroll of words and code, you might think "who has time for that?" Many beginner programmers have that notion of "if it works, it works". However, taking the time to learn coding standards can help you learn to write code efficiently. 

For example, one rule is when using anonymous functions, prefer arrow functions:
``` js
// bad
function totalDegrees(data) {
  const awards = _.pluck(data, 'AWARDS');
  return _.reduce(awards, function(memo, sum) {
    return memo + sum;
  });
}

// good
function totalDegrees(data) {
  const awards = _.pluck(data, 'AWARDS');
  return _.reduce(awards, (memo, sum) => memo + sum);
}
```
Before I learned coding standards, I would write code like the bad example. I didn't really understand ES6 at first, so I didn't utilize arrow functions that much. However, when I started to be more conscious about coding standards, I realized that arrow functions are kinda awesome. Being able to write an anonymous function in single line like that was a game changer. I could write functions more quickly, and as a bonus my code was more readable for others.

## ESLint
<img style="text-align: center; width: 30%; margin: 20px; float: right;" src="https://i0.wp.com/www.johnxiong.com/wp-content/uploads/2018/05/download.jpeg?w=552&ssl=1">

ESLint is a linter, which I've learned is called that because it acts as a "lint catcher". Now that I've mentioned it, you can even think of the squiggly error lines as little bits of fiber and fluff. ESLint is a wonderful tool that flags anything that doesn't comply with a JavaScript Style Guide. Now complying with coding standards is a simple as hitting the "Fix ESLint Problems" button. I don't have to worry too much about knowing every single rule because ESLint can fix it for me. I have to admit, seeing all the squiggly lines disappear and getting a nice green checkmark in the end is highly satisfying. At the end of the day, coding standards aren't just some trivial rules we should abide by. They improve the quality of code and makes code that is readable and usable by others. When working in teams or open-source projects, coding standards are more important than ever. Without coding standards, it'd be like trying to read a doctor's messy handwriting. You might get the right prescription or you might get something else entirely. Coding standards reduce confusion and makes the process better overall. 
