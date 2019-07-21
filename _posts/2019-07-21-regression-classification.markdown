---
layout: post
title:  Notebook for Thomas' Calculus
date:   2019-07-21 13:32:20 +0300
description: Writing down the important points of this textbook of Thomas' Calculus, sas Brief history of that # Add post description (optional)
img: post-1.jpg # Add image post (optional)
tags: [Blog, Math, Notebook]
author: Barry # Add name author (optional)
---

## Functions
Functions are fundamental to the study of calculus.
This Chapter reviewd what the functions are and how they classifed, trandformed and combined, and trigonometric functions are also included.
This contains inverse, exponential and logarithmic functions.Besides, the real number system, Cartesian coordinates, straight lines, circles, parabolas, and ellipses are reviewed in appendics.

### Functions; Domain and Range

The first sample of function:
$$y=f(x) $$
  ("$y$ equals $f$ of $x$" )

In this notation, the symbol $f$ represents the functions,
the letter $x$ is the independent vairable representing the input value of $f$, and y is the dependent variable or ouput value of $f$ at $x$.

>**Definition**: a function $f$ form a set $D$ to a set $Y$ is a rule that assigns a unique(single) element $f(x)\in Y$to each element $x\in D$

The set $D$ of all possible iput values is called the **domain** of the function.The set of all output values of $f(x)$ as $x$ varies thorughout $D$ is called the range of the function.

When we define a function $y=f(x)$ with a formula and the domain if not stated explicitly or restricted by context,the domain is assumed to be the largest set of ret $x$-values for which the formula gives real $y$-values, which is called the **natural domain**.
If we want restrict the domain in some way, we must say so.The domain of $y = x^2$ is the entire set of real numbers. To restrict the domain of the function to, say, positive values of $x$, we should write "$y=x^2,x>0.$"

when  the range of a function is a set of real numbers, the function is said to be **real-valued**.

A function can also be pictured as an **arrow diagram**.

###Graph of functions
If $f$ is a function with domain D, its **graph** consists of the points in the Cartesian plane whose coordinates are the input-output pairs for $f$. In set notation, the graph is $\{x,f(x)|x\in D\}$.


### Representing a Function Numerically
A function may be represented algebraically by a formula
and visually by a graph. Another way to represent a function is numberically,through a table of values.The graph cosisting of only the points in the table is called a **scatterplot**.

### The Vertical Line Test for a Functions
Not every curve in the coordinate plane can be the graph of a function. A function $f$ can havae only one value $f(x)$ for each $x$ in its domain, so no Vertical line can intersect the graph of a function more than once. A
the circle is not the graph of a function.But uppper semicircle defined by the function $g(x)=\sqrt{1-x^2}$.
lower semicircle defined by the function $g(x)=-\sqrt{1-x^2}$

### Precisewise-Defined functions
<b> absolute value function </b>
$$
\begin{equation}
\lvert x\rvert=\begin{cases}
x & & {x \leq 0} \\
-x & & {x<0}  
\end{cases}
\end{equation}
$$

<b>greatest integer function </b> or <b> integer floor function</b>
It is denoted $\lfloor x\rfloor$

<b>least integer function or integer ceiling funciton<\b>
It is denoted $\lceil x\rceil$

### Increasing or Decreasing functions
If the graph of a function climbs or rises as you move from left to right, we say that the function is increasing.If the graph descendds or falls as you move from left to right, the function is decreasing.

><b>Definitions<\b> Let f be a function defiend on interval $I$ and let $x_1$ and $x_2$ be any two points in $I$.
1. If $f(x_2)>f(x_1)$ whenever x_1<x_2, then $f$ is said to be increasing on $I$.
2. If $f(x_2)<f(x_1)$whenever x_1<x_2, then $f$ is said to be decreasing on $I$.

###Even Functions and Odd Functions: Symmetry
The graph of even and odd functions have characteristic sysmmetry properties.

<em>Definitions</em> A function $y=f(x)$ is an
 even function of x if $f(-x)=f(x)$,odd function of$x$ if $f(-x)=-f(x)$.for every x in the function's domain.

 The graph of an even function is symmetric about the y-axis.
 The graph of an odd function is symmetric about the origin.

###Common functions

<em>Linear Functions</em>

<em>Power Functions</em>

A function $f(x) = x^a$, where a is a constant, is called  a power funciton.

<em>Polynomials</em>

A function $p$ is a <b>Polynomials</b> if
$p(x)=a_nx^n+a_{x-1}x^{n-1}+ ...+a_1x+a_0$
where n is a nonnegative integer and the numbers a_0,a_1,a_2,...,a_n are real constants(called the <b>coefficients</b> of the Polynomials).
All Polynomials have domain $(\infty, -\infty)$.

leading coefficient $a_n\ne0$ and$n>0$, then $n$ is called the degree of the Polynomial.Linear functions with $m\ne0$are Polynomials of degree 1. Polynomials of degree 2, usually written as $p(x)=ax^3+bx^2+cx+d$of degree 3.


<em>Rational Functions</em>

A rational function is a quotient or ratio $f(x)=p(x)/q(x)$, where $p$and$q$ are Polynomials.The domain of a rational function is the set of all real x for which $q(x)\ne0$.

<em> Algebric Functions</em>

Any function constructed from Polynomials using algebraic operations(addition, subtraction, multiplication, division and taking roots)lies within the class of algebraic  functions.

<em>trigonometric functions</em>

There are six basic trigonometric function, lying within the sine and cosine functions classes.

<em>exponential Functions</em>

Functions of the form $f(x)=a^x$,where the base $a>0$is a positive constant and $a\ne1$, are called exponential functions.

<em> logarithmic functions </em>

These are the function $f(x)=log_ax$, where the base$a\ne1$ is a positive constant.They are the<i>inverse functions</i> of the exponential functions.

<em>Transcendental Functions</em>

These are functions that are not algebraic.They include the trigonometric, inverse trigonometric, exponential, and logarithmic functions, and many other functions as well. A particular example of a Transcendental function is a <b>catenary</b>.
