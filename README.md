# Data Structures and Algorithms for the busy developer

## Introduction

If you're looking for a new study plan to
- Study for a mid-term / finals on the topic.
- Pass a coding interview.
- Dusting off skills that you haven't practiced in weeks/months/years.
- learn because you're an avid learner

You've come to the right place.

Not everyone has either months or hundred/thousand of hours to invest learning about this fundamental core computer science / software engineering skill. This repository is a distilled summary information on grasping the core knowledge to either brush up or learn about DS+A quickly. The goal of this repository is to help developers who have about 2 to 4 weeks' worth of time to prepare and learn. I found that most guides online are geared towards people who have fro. months up to a year to prepare.

The goal of this guide isn't to be comprehensive. It should be seen a good resource on your journey of data structures and algorithms knowledge. After going through the material here, I suggest finding other resources to compliment and further what you've read on / practiced. In time, I hope the guide gets better summaries, illustrations,etc to help those in need. But as mentioned earlier, this isn't meant to replace what is already available for those who have ample amounts of time on their hands to learn.

## Complexity Analysis for algorithms
Algorithms are basically computations taking care of inputs and outputs. When we talk about algorithm complexity, we're trying to assert and predict how fast the algorithm should run. In that context, we get to forget of our surronding environment such as the programming language or hardware. Analyzing complexity also allows developers to quickly evaluate and compare competing solutions and determine which would fare best based on their given situation and tradeoffs.

### Handling input size
One important aspect of complexity analysis is that you can explain how your algorithm will react once your input size grows. As a software developer, you're responsible for every line of code that you're writing, reviewing, designing and maintaining. You should understand and have a clear idea how your program will behave if you'd get 100x more traffic on your website. Could your server handle this kind of pressure with the current design?

There are many mitigating factors involved when you're trying to implement a solution to your problem. Being pragmatic with your time and resources is an important skill to thrive in an Agile workplace. In the context of complexity analysis, we're looking for optimized solutions. When you practice your skills, it'll be important on trying to find the best solution you can think of. When designing an algorithm, always have in mind the constraints of your given problem space. For instance, knowing the smallest size and largest size of your input will help drive a solution to your problem. Once you work on an urgent project, then you can think about being pragmatic and see whether a brute-force solution would meet the requirements.

### Worst-case analysis
In the context of complexity analysis, we're interested in how the program will behave once the input grows. When we talk of worst-case situations, we're trying to evaluate how would the program react in case we're very unlucky. In that situation, we'll discard instructions that have less impact than others. We'll keep an eye out for instructions with underlying impact growing fast as the input is growing.

### Big O Analysis

O(n) - read it as "Big O of n"

Θ(n) - read it as "theta of n". 

Ω(n) - read it as "omega of n".
