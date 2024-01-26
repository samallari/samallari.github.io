---
layout: essay
type: essay
title: "Clever Coders ask Clever Questions"
# All dates must be YYYY-MM-DD format!
date: 2024-01-25
published: true
labels:
  - Stack Overflow
---

>“Asking questions is half of learning.” - Elijah Muhammad

In Eric Raymond’s article, [How to ask questions the smart way](http://www.catb.org/esr/faqs/smart-questions.html), he outlines what makes a question “bad” and provides a guide on how to ask better questions. For me, asking questions can be difficult, especially when I don’t even know where to start. Typically, I’ll try breaking down a problem or an area of confusion to something more bite sized and figure it out on my own. 
When I was an Assistant TA for Intro to Computer Science, I was on the receiving end of a lot of questions. That semester, I finally understood the importance of crafting a “smart” question. Smart questions were easier to answer, because often the student could tell me what they’ve tried to do and point me to the errors in their code. Then, it became easier for me to explain the error to the student and how it can be fixed. 

## try { StackOverflow }
Stack Overflow is widely regarded as a programmer’s best friend. In times of need, SO can be a real lifesaver. I’ve certainly learned a lot from searching for an answer for someone else’s question. The SO community is so large though, that it makes sense for one to weed out the questions they think is not worth answering. Raymond writes, “We [responders] take time out of busy lives to answer questions, and at times we're overwhelmed with them. So we filter ruthlessly… The best way to get a rapid and responsive answer is to ask it like a person with smarts, confidence, and clues who just happens to need help on one particular problem.” 

### How to Ask Questions the Dummy Way
If you’re feeling a little silly and a bit like a fool, here’s one way to ask questions the “dummy” way. Let’s take a look at user tayswervin’s [post](https://stackoverflow.com/questions/34071331/need-help-creating-an-invoice-program-using-arrays), titled "Need help creating an invoice program using arrays". 

As stated in the title, user tayswervin simply states that they need help creating an invoice program using arrays. They write, “I cant figure out where to go with my code, also in my if loop it doesn't let me enter more company names after the first loop.” Then, they proceed to throw at you blocks of code. 

First of all, what is an “if loop”? Scanning through their code briefly, I don’t even see a single if statement. Interestingly, they don't use an array at all in their code either. They were most likely referring to the “for loop” in their code, but before asking a question, you should make sure to check your post for typos so that you don’t look like a dummy… Careless and sloppy questions typically means a careless and sloppy thinker, and no one wants to help someone like that. Second, I don’t want to be scanning through huge blocks of code looking for a problem and then solving said problem. Nobody really wants to be reading all that. Like Raymond says in his article, “Don't ask others to debug your broken code without giving a hint what sort of problem they should be searching for.” User tayswervin provides little insight into what they’ve tried to do or what they think the problem is, appearing like a dummy.

### How to Ask Questions the Smart Way
In reply to tayswervin, user Manos Nikolaidis sends them to another [thread](https://stackoverflow.com/questions/13102045/scanner-is-skipping-nextline-after-using-next-or-nextfoo), appropriately titled “Scanner is skipping nextLine() after using next() or nextFoo()?”

In contrast, user blekione, provides a specific block of code where the issue is occurring. They write, “I am using the Scanner methods nextInt() and nextLine() for reading input… The problem is that after entering the numerical value, the first input.nextLine() is skipped and the second input.nextLine() is executed.” User blekione’s even provides what the output is on the console and what it should be. Now I know exactly what blekione’s goal is and what the issue is and can come up with a solution more quickly. In fact, the answers are more detailed in comparison to the comments lefts on tayswervin’s post. If only tayswervin dug deeper than surface level stuff and tried to debug it themselves (like… even adding a few print statements would have made them realize the issue with nextInt()), they would have been able to craft a more specific question, and might have even come across the thread Nikolaidis shared. 

## Questions on Questions
Asking questions the smart way is really important, but it’s also really difficult. However, I think one learns the most by doing so. As a student, this makes rethink the way I ask questions (I’m questioning my questions!). In his article, Raymond emphasizes the importance of searching for an answer before asking others. The attempt you make in answering your own questions can provide an insight into exactly what you are looking for and can make your question even smarter.
