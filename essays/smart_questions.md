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

With so much information out there, we find ourselves often times asking questions in both our careers and in everyday life. Specifically, in the software engineering field, there are so many different languages and algorithms that things can get pretty complicated. We can help ourselves out by making sure that the questions we ask are smart questions. How we ask our questions can yield very different answers, and can determine whether or not we get the information we need. One of the keys to asking a good question is to include all of the necessary information in a precise and concise manner. This will make it easier for the person responding to the question to understand exactly what the problem is. There are many other ways to improve the quality of a question. Let's consider a couple of questions I found on stack overflow.

<blockquote cite="http://stackoverflow.com/questions/32590751/make-this-script-work">
"For an assignment I need to write a piece of code which goes through numbers from 1 to 100 and only prints even ones and stops once they are printed. Yes, I know how to do it with a for loop but that's easy... I want to know if it is possible to do it with a while loop. Here is my very clunky code (the result of me constantly changing things around) The problem with that is that it repeats numbers. It needs to only print each number once. And yes I have tried using "random.sample" but that has a problem with ints."
<pre>
import random<br>
counter = 1<br>
while (counter != 50):<br>
    number = random.randrange(1, 100)<br>
    if (int(number) % 2 == 0):<br>
        print (number)<br>
        counter = counter + 1<br
</pre>

</blockquote>

This question here is an example of a poorly written question. One of the main reasons for this is how unclear the question is. Anyone trying to answer this question is going to have a difficult time understanding the problem. The person also states that this is a homework assignment, and most people believe those problems are to be worked on your own rather than turning elsewhere for an answer. It is also worth noting that the subject of this question was "Make this script work." It's never a good idea to demand something from people who don't have to help and are doing so of their own accord. 

<blockquote cite="http://stackoverflow.com/questions/111102/how-do-javascript-closures-work">
"How would you explain JavaScript closures to someone with a knowledge of the concepts they consist of (for example functions, variables and the like), but does not understand closures themselves?

I have seen the Scheme example given on Stack Overflow, but unfortunately it did not help."
</blockquote>

This question is an example of a good question because they do a good job of explaining their current working knowledge with JavaScript to help provide background information. The person also shows that they have put forth some kind of effort in trying to understand the problem on their own but they were unsuccessful. These types of questions lend themselves to receiving better answers.

As software engineers, asking questions is a huge part of how we gain new knowledge so we must learn how to ask questions in a smart way. Through this we will be able to get the most helpful answers and ultimately help us with our work.
