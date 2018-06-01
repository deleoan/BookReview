# Working Effectively with Legacy Code
The book is about how can we address or handle Legacy Code. There are several techniques given in the book which answers common questions being asked by every developer who handles legacy code. The book will teach you how to refactor, read and understand, and test a Legacy Code. To have better understanding, let's define first what is Legacy Code. 

### What is Legacy Code?

It is the worst nightmare of every developer. Why? Because it is a code base without automated testing. That's it! It is quoted in the book:

<img src="images/code_without_test_quote.jpg" class="inline"/>

## Part I: The Mechanics of Change

### Changing Software

There are <b>Four Reasons to Change Software</b> stated in the book, which are:
<ul>
    <li>Adding a Feature</li>
    <li>Fixing a bug</li>
    <li>Improving the design</li>
    <li>Optimizing resource usage</li>
</ul>

Knowing the difference of<b>Adding a Feature and Fixing a bug</b> is somehow unclear. While working for a specific change, developer may say that it is an additional feature while customer may say that it is only a bug fix. In the book <i>Behavior</i> was used to clearely define those two. The difference of adding new behavior and changing old behavior is quoted in the book:

<img src="images/behavior_quote.jpg" class="inline"/>

<b>Improving the design</b> is simply refactoring, this is the change of software wherein we want to improve the structure of the code and make it more readable and maintable. <i>Refactoring</i> means that changes that we apply does not change the behavior of the system.

<b>Optimization</b>, almost same with Refactoring by not changing system's behavior but the purpose is different. In Optimization the purpose is to make the code faster, it focuses on saving memory.

We realized that the hardest part of changing a software is maintaing its behavior or <i>Preserving behavior</i>. Why? Because there are changes that can be risky, we must ensure that we know why we are making that specific change, analyze the change, be cautious, and <i>“If it’s not broke, don’t fix it.”</i> 

### Working with Feedback



## Part II: Changing Software

## Part III: Dependency-Breaking Techniques
