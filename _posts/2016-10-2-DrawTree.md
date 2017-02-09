---
layout: post
title: Probability Tree Drawing in Python
---
I wrote a program for drawing probability trees with no intersecting branches, for any number of branches and sub-branches.
I also created animation to show off the cool geometry behind it.

[![Demo CountPages alpha](https://j.gifs.com/r0B6nk.gif)](https://www.youtube.com/watch?v=tyIMAtRVS4w&feature=youtu.be)

The real challenge of this was actually in the geometry deductions I made while planning the code rather than the code itself. Basically, it required [a bunch of those clever little tricks you remember from middle and high school](http://www.analyzemath.com/high_school_math/grade_10/geometry.html) with the addition of a tiny bit of fancier linear algebra.  In addition to reminding me of my high school bullies, this project also taught me a few valuable programmign lessons:

* I was forced to have a clear picture of what the algorithm looked like before putting fingers to the keyboard.  The lengthy list of geometric procedures and vector math would have made a debugging nightmare if I had tried to implement them on the fly as I coded.  This was probably the first program for which I spent more time writing on notebook paper than in a code editor.

* This was the first time I used the numpy library extensively.  For arrays and matrices.  If you use Python and you haven't learned about numpy yet **learn about it**.  There's a slight learning curve, but in the long run it will make your life easier.

* The project drove home the usefulness of breaking a task down into intuitive components and accomplishing each with clearly named functions.  This in contrast to the approach I would sometimes use in the past, which was to write a giant block of code for the task.

* Heavily used the ability to give arguments default values in Python.  This allowed me to apply one function or class to situations with slightly different circumstances.  Not sure yet whether or not this is a ‘good habit.’  Also used named arguments frequently.  I like that this provides more clarity as you read through the code, but I have heard that there is some debate about whether or not this is useful, especially given the ability of some modern IDEs to provide parameters for a function when you hover over it.

* The usefulness of establishing conventions for variable prefixes that indicate type.  Especially helpful for a dynamic typing language like Python.

