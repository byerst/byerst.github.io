---
layout: essay
type: essay
title: Smart Questions
date: 2016-09-08
labels:
  - Software Engineering
  - Learning
  - Stack Overflow
---

<img class="ui medium round floated right image" src="../images/questionmarkmeme.jpg">

With so much information out there, we find ourselves often times asking questions in both our careers and in everyday life. Specifically in the software engineering field, there are so many different languages and algorithms that things can get pretty complicated. We can help ourselves out by making sure that the questions we ask are smart questions. How we ask our questions can yield very different answers, and can determine whether or not we get the information we need. One of the keys to asking a good question is to include all of the necessary information in a precise and concise manner. This will make it easier for the person responding to the question to understand exactly what the problem is. There are many other ways to improve the quality of a question. Let's consider a couple of questions I found on stack overflow.

<blockquote cite="http://stackoverflow.com/questions/32590751/make-this-script-work">
For an assignment I need to write a piece of code which goes through numbers from 1 to 100 and only prints even ones and stops once they are printed. Yes, I know how to do it with a for loop but that's easy... I want to know if it is possible to do it with a while loop. Here is my very clunky code (the result of me constantly changing things around):

<code>
import random
counter = 1
while (counter != 50):
    number = random.randrange(1, 100)
    if (int(number) % 2 == 0):
        print (number)
        counter = counter + 1
</code>
The problem with that is that it repeats numbers. It needs to only print each number once. And yes I have tried using "random.sample" but that has a problem with ints.
</blockquote>

