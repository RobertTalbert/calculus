# Script for Functions Bootcamp video 3

At this point we've learned what a function is, that functions can be represented in four different ways, and that it's important to be able to work with equal fluency in the data, graph, and formula representations of a function.

Let's look specifically in this video at functions given to us as formulas --- not because they are the most important or common representation, because they aren't. But because they are pretty common, and understanding formulas helps us to understand the other representations. 

First, here's a new term: To *evaluate* a function means to find the output value that results from a given input. Literally "e + valuate" means to pull a value out of the function. 

When the function is given as a formula, this means to use the formula to compute the output, when you're given the input. 

To do so with a formula, just replace all instances of the independent variable with the value you are putting in, then do the math that results to find the output. 

For example, the area of a circle is a function of the length of its radius. Remember this means that if you give me a specific value of the radius, I can give you the exact value of the area, and there's only one such area possible. 

The relationship between the area of a circle and its radius is well known as a formula: Area = pi times the radius squared. So if I wanted the area of a circle with radius 5, I'd simply find all instances of the radius, replace that with the input, then do the math --- this time by squaring the input and multiplying by pi. The area that comes out is 25 pi which is about 78.54. The 25pi is an *exact* output and the 78.54 is approximate --- note that these are not equal! 

We usually use **function notation** for working with functions in any representation. In the case of circle area, area which uses the variable name A is a function of radius length which uses the variable name r. In function notation, we'd write A(r) = pi r^2 which is pronounced "A of r equals pi r squared". The A(r) on the left isn't multiplication but rather a way of saying that A *depends on r*. When we found the area of a circle with radius 5, we found A(5) --- this means we found the output or area corresponding to an input of 5. 

If we wanted the area when the radius is 3, that's A(3) and we'd find that by replacing all the r's with a 3: A(3) = pi 3^2 which gives us A(3) = 9pi. 

Here's another example: B(t) = t^2(t-1). This is a function where the input or independent variable is called t, the output or dependent variable is called B, and the process for computing an output when given an input is given by ths formula. For example if you give me an input of t = 4, the output is B(4) = 4^2(4-1) --- just replace all instances of t with 4 --- then do the math on the right: B(4) = 16(3) which is 48. 

Pause for a second and work these out to make sure you understand: 

B(1)
B(0)
B(-5)

You should get B(1) = 0, B(0) also = 0, and B(-5) =-150. If you didn't, see if you can debug your work and make corrections. Remember to replace all instances of t with the input, and watch out for negative numbers! 

A bonus of working with formulas is that we can evaluate them not only when the inputs are numbers but also when they are algebraic expressions in their own right. For example let's take the previous function B(t)=t^2(t-1) and find B(h+2). What does this mean? Well, it means the same thing as B(4) --- I replace all instances of t with the input, h+2, and do the math that results. In this case, 

B(h+2) = (h+2)^2(h+2-1)

On the right, there's some simplifying I can do by multiplying out the first factor and simplifying the second one:

B(h+2) = (h^2 + 4h + 4)(h+1)

And then I can multiply these two together to get 

B(h+2) = h^3 + 5 h^2 + 8 h + 4

I'll leave the details to you as a refresher of basic algebra. Be sure to check those though! 

So now you know how to evaluate a function given to you as a formula, when the input is both a number and an algebraic expression. 