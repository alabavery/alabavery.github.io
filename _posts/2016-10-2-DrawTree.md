---
layout: post
title: Automating Probability Tree Drawing in Python
---
I wrote a program for drawing probability tree with no intersecting branches, for any number of branches and sub-branches.
I also created animation to show off the cool geometry behind it.

[![Demo CountPages alpha](https://j.gifs.com/r0B6nk.gif)](https://www.youtube.com/watch?v=tyIMAtRVS4w&feature=youtu.be)


* Really forced me to have a clear picture of what the algorithm looked like before putting fingers to the keyboard.  This program used a really lengthy list of geometric procedures and vector math to get to its output; it would have been a debugging nightmare if I had tried to implement them on the fly as I coded.  This was probably the first program for which I spent more time writing on notebook paper than in a code editor.

* First time I used the numpy library extensively.  For arrays and matrices.

* Usefulness of breaking a task down into intuitive components and accomplishing each with clearly named functions.  This in contrast to the approach I would sometimes use in the past, which was to write a giant block of code for the task.

* Heavily used the ability to give arguments default values in Python.  This allowed me to apply one function or class to situations with slightly different circumstances.  Not sure yet whether or not this is a ‘good habit.’  Also used named arguments frequently.  I like that this provides more clarity as you read through the code, but I have heard that there is some debate about whether or not this is useful, especially given the ability of some modern IDEs to provide parameters for a function when you hover over it.

* The usefulness of establishing conventions for variable prefixes that indicate type.

