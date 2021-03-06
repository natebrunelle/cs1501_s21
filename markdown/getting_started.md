---
title: Problem Set 0: Getting Started
...


The problem set is intended to get you set up for the semester. For future exercises you'll need to use LaTeX (for written exercises) and your choice of Python or Java (for programming exercises). You may change which programming language you use at will throughout the semester, so don't feel like you must decide now.

We will reward completion of this problem set with bonus points. These bonus points will add a small amount to your final grade in the class. The idea for these bonus points is that they will count for little enough that you will not be tempted to accumulate bonus points instead of making your best effort on homework, but enough to make a difference in your final grade. Generally, expect that you'll need to spend 3x as long on a bonus activity for the same grade impact as exercises.

That being said, the tasks included in this exercise are pre-requisite for all other exercises, so the incentive of bonus points is just icing!


# Getting Started with LaTeX

LaTeX is essentially a programming language for documents. It's the most powerful and widely-used tool for producing highly-readable documents with combinations of code, pseudo-code, mathematics, figures, etc. We will be using it for all written assignments this semester.

## Register for Overleaf

While you're welcome to use any LaTeX tool that you'd like, we highly recommend using Overleaf. To use this tool, first visit [https://www.overleaf.com](https://www.overleaf.com) and register an account (if you don't already have one). UVA has a site license, so if you register with your @virginia.edu email address you will have full access to all the Overleaf features for free.

## Set Up Your Project

You will have a separate Overleaf project for each exercise. The easiest way to set up the repository is to upload the zip file posted with each exercise. To do this:

1. Download the [exercise0.zip](/files/exercises/exercise0.zip) file: 
1. In Overleaf, click on *Create First Project* or *New Project* and select *Upload Project* from the menu.
1. Select the *exercise0.zip* file you downloaded in step 1.

## Editing The LaTeX Template

1. Look for the line, *submitter{TODO: your name}* and replace the "TODO: your name" with your name and UVA id: *submitter{Nathan Brunelle (njb2b)}*
1. List your collaborators and resources, replacing the TODO in *collaborators{TODO: replace ...}* with your collaborators and resources. (Remember to update this before submitting if you work with more people.)
1. Replace the line, *usepackage{algo}* (the second line in the file) with *usepackage[response]{algo}*. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment.
1. Then, try rebuilding the PDF by clicking *Recompile*. You should see a file that includes your name and collaborators, but with all the directions removed (we don’t want to see these in your submission).

## Deliverable

- Modify the [exercise0.tex](https://www.cs.virginia.edu/~njb2b/cs4102/f20/files/exercises/exercise0.zip) file to complete each problem. To see an example of what your submission might look like, see [this pdf](https://www.cs.virginia.edu/~njb2b/cs4102/f20/files/exercises/exercise0_sample.pdf). You should reproduce the proof seen there for problem 2.
- Learn how to include drawings in your documents with the *includegraphics{file}* command by including a caricature of Nathan Brunelle or David Wu in the same pdf.
- Submit the generated pdf on [the kytos submission system](https://kytos.cs.virginia.edu/cs4102/task.php?task=Exercise%200&). Name it *exercise0.pdf*.

# Getting Started with Python and Java

This semester you will be able to use either Java or Python (your choice) for the programming exercises. This exercise is for you to get your programming environment set up and to complete a couple of (hopefully) easy programming tasks.

You're only required to install one of Java or Python (you do not need to install both).

## Java

If you already/still have a Java JDK installed on your machine from CS2110, you're likely good to go! If not, follow the procedure below according to the OS you're using.

### Windows

To install on windows, I recommend [this super helpful video](https://www.youtube.com/watch?v=RFk653ilyhA) made by our very own Professor Will McBurney of CS2110 fame.

### Mac

To install Java JDK on a Mac, follow this procedure:

1. Go to http://jdk.java.net in a web browser

1. Click on jdk13

1. Select the correct download for your operating system

1. Once that file is downloaded, extract the zip or tar.gz file into /Library/Java/JavaVirtualMachines/

5) Remember where you extract the folder, as you will need it soon.

### Eclipse

If you would like to use Eclipse as your IDE (any IDE suffices):

1. Go to http://eclipse.org

1. Click on download in the top right.

1. Download Eclipse IDE 2019-12

1. When finished download, attempt to run the file. It will ask for a Java VM. The window should say something like: “The required 64-bit Java 1.8.0 virtual machine could not be found. Do you want to browse your system for it?”

1. Click “Yes” on that window.

1. Navigate to where you stored the openjdk-13.0.2_windows-x64-bin folder from the installing OpenJDK step. Go into that folder, then into the folder “bin”, and select javaw.exe

---On Mac, the you will want to link to jdk-13.0.2.jdk/Contents/Home/bin

------Also, check your Library folder -> /Library/Java/JavaVirtualMachines/jdkX.Y.Z.jdk/ (where X Y and Z are version numbers) for a Contents/Home/bin if the above address doesn't work

1. At this point, Eclipse will install. Accept all license agreements.

## Python 3

If you already have python 3 installed on your machine (perhaps from CS1110), then you're likely good to go. If not, I recommend following the procedure available on the [cs1110 webpage](https://cs1110.cs.virginia.edu/lab01-installing.html). You can skip any steps involving PyGame or sdl.

## Deliverable

There is no deliverable here, but be advised you have a programming assignment due on September 18.

