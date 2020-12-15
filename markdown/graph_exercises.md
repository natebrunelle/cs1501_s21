---
title: Unit 5 Exercises, Graphs
...

All Graphs exercises will be posted here as they are released (about 1 week before the deadline).

# Instructions

Exercises are due Mondays. I recommend you start them early. In my experience with solving tricky problems, it is more productive to work on them in short bursts, with breaks in between. To solve a hard problem, it's less about the number of hours you spend working on it than it is about the number of showers.

# Policies

You may collaborate with up to 4 other people (i.e. a group of up to 5 total) when completing exercises. You may additionally use external materials with following restrictions:

- Your write-ups must be done entirely independently. You may discuss with collaborators, but we expect that the answers you submit be expressed in your own words. 
- You must understand everything you submit. Do not submit anything you could not explain to a member of the course staff.
- You **must** cite any and every source you consult beyond officially-provided materials. Included in your citation, you must identify which components of your submission came from each source (it will be understood that content with no citation is your own exclusive work). Your collaborators are considered to be sources, and so should be cited. An example citation might look like: "I collaborated with David Evans on the pdf style, I consulted \url{https://www.overleaf.com/learn/latex/Aligning\%20equations\%20with\%20amsmath} for help with the align environment, Robbie Hott helped me to debug the for loop on line 107 of my code."
- Do not seek "hints" or entire solutions to the problems. Limit your searching to background information only. Do not use Chegg.

# Deliverables

Unless otherwise indicated, each problem set will be submitted as either a pdf or a java/python file on the [Assignments page](https://www.kytos.cs.virginia.edu/cs4102). Unless otherwise indicated, pdfs must be generated by LaTeX, and must be done by modifying the template file given.

# Problem Sets


There will be a total of 2 exercises for this unit (one programming, one written). The average across these exercsises will count as 50% of your grade on unit 2. The remaining 50% will be your grade on this unit's quiz.

## Exercise 1: High Road Low Road

This first exercise will be a programming assignment. The goal here is for you to see how to manipulate graphs to solve complex problems with them. You may use either Python3 or Java for your implementation. 

To complete this assignment:

1. Read the [description of the problem](files/exercises/graph1.pdf).

1. Download the zip file for your desired programming language: [Java](files/exercises/highroadlowroad_java.zip) or [Python](files/exercises/highroadlowroad_python.zip)

    - **For Java**: You will see three `.java` files: `Graph.java` which implements undirected graphs for you to use when completing your assignment, `HighroadLowroad.java` which is where you will implement your algorithms, and `HighroadLowroadTester.java` which will run your algorithms on several test cases.
    - **For Python3**: You will see three `.py` files: `graph_util.py`  which implements undirected graphs for you to use when completing your assignment, `highroad_lowroad.py` which is where you will implement your algorithms, and `highroad_lowroad_tester.py` which will run your algorithm on several test cases.

1. Implement the functions/methods called `shortest` and `num_shortest` contained in either `HighroadLowroad.java` or `highroad_lowroad.py`. We have already provided signatures for these functions/methods:
    - `shortest`: Returns the length of the shortest highroad-lowroad pair given the graph of cities, a map/dictionary representing the elevation of each city, the starting node, and the ending node.
    - `num_shortest`: Returns the number of shortest highroad-lowroad paths given the same as above.
    - Feel free to add any additional functions/methods that you wish.

1. Check your implementation by running either `HighroadLowroadTester.java` or `highroad_lowroad_tester.py` (we will use exactly these to grade your code, so if you modify them, I recommend checking against the original versions before submitting). It will read input files and run each of the provided tests against your implementation of both methods once. Descriptions of each test are available in the writeup.

## Exercise 2

Many problems are solved by coming up with a way of representing a problem as a graph, then applying a know algorithm to that graph to obtain a solution. This written problem set has two problem, both solvable using that general technique.

For your convenience, here is a pdf of the problem set: [graphs2_blank.pdf](files/exercises/graphs2_blank.pdf).

To complete this assignment:

- First download this zip file - [graphs2.zip](files/exercises/graphs2.zip) - and upload as a new project in Overleaf.

- Next, add you name and computing id under `submitter` in *exercise.tex*.

- Once you've solved a problem, edit the corresponding *problemX.tex* file to include your answers to the problems. In general, everything you need to change within the problem set is marked with a `TODO` comment, so look for those.

- After including all solutions, comment out the line that reads `usepackage{algo}` and uncomment the line that reads `usepackage[response]{algo}`. This will remove the problem set instructions, leaving your solutions in the document.

- Remember to add your resources and collaborators to `collaborators` in *exercise.tex*

- Finally, download the pdf generated by your LaTeX code, call it *graphs2.pdf*, and submit it on the [assignments page](https://www.kytos.cs.virginia.edu/cs4102).
