---
layout: post
title:  "Getting Started with Processing"
description: A tutorial to download Processing.
date:   2019-05-23 21:03:36 +0530
categories: General Java Processing
exerpt_seperator: <!--more-->
---

In this post I will detail how to download Processing to Windows and Linux machines, as well as some programming basics and activities.
<!--more-->
For anybody reading this hoping to take part in an FTC competition, I would reccomend that you use the FTC Blocks software, because it is much more intuitive and has less of a learning curve, but I still encourage you to also continue working to learn programming basics, as it will help you understand the Blocks software and later create programs in Java. [Here](https://www.firstinspires.org/resource-library/ftc/technology-information-and-resources) are some resources to help set up Blocks, or Onbot, both of which I know almost nothing about.
---

# Downloading Processing

Processing is an IDE and graphics library for Java, making it easy to learn Java without having to worry about complex configuration. It can be downloaded [here](https://processing.org/download/) with simple installation instructions. If you are one of the students in Lebanon, you can contact us if you are unable to install it.

---

# Basics

Here we will discuss some of the very basic programming principles. We will work with integers, and learn about if statements, while loops, for loops, and create simple shapes.

---

## Basic format

This is the basic format of code in processing

```
void setup(){
  //Code to be run once after start is pressed
}

void loop(){
  //Code to be run multiple times
}
```

The above code has comments (written after //) to explain what each section does, each section is called a method. Now that you know the basic format, let's talk about if and else statements.

Let's look at a quick sketch, and go over a few more things 


```
//Declare variables before any methods
int variable = 10;

void setup(){
//nothing to run in setup for this sketch
}

void loop(){
    println(variable);
}
```

There are a few things that are important to notice in the above sketch:

* There is a ';' after the command
   * This is because in Java, we could write all code on one line, e.g `void loop(){println(variable);}` So the computer doesn't really "see" when we end a line, it's just so we can read it more easily, the computer only sees the end of a line when we type ';'s
* There is no ';' after `void loop()` or `void setup()`
    * This is because they have '{'s after them. These aren't commands, but sections of code, so instead of a ';' following it, the '{}'s contain the code within it.
* The `int variable = 10;` outside of the methods
    * This 'declares' the variables, all it does is let the computer know what variables are being used later in the code

## If/Else statements

If you are familiar with any other programming language, this should be very easy for you, the basic setup of if and else statements is:

```

if(//condition){
    //run this code
}

```

So lets look at an example (we will also work with real graphics, not just the console):

```
void setup(){

}

void loop(){

}
```