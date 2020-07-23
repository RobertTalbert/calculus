# Script for Functions Bootcamp video 3

At this point we've learned what a function is, that functions can be represented in three different ways (as data, graphs, or formulas), and that it's important to be able to shift representations in order to reveal information about a function. 

Let's look specifically in this video at functions given to us as formulas --- not because they are the most important or common representation, because they aren't. Most functions in real life are not naturally formulas but instead are either graphs or data. But formulas are pretty common, and understanding formulas helps us to understand the other representations. 

Recall that *evaluating* a function just means taking a given input and using the function to determine the output that goes with it. We mentioned in an earlier video that when a function is given as a formula, evaluating it at an input value just means replacing all instances of the independent variable with the value you are putting in, then doing the math that results to find the output. 

Let's do a simple example. The area of a circle is a function of the length of its radius. Remember this means that if you give me a specific value of the radius, I can give you the exact value of the area, and there's only one such area possible. 

The relationship between the area of a circle and its radius is well known as a formula: Area = pi times the radius squared. So if I wanted the area of a circle with radius 5, I'd simply find all instances of the radius, replace that with the input, then do the math --- this time by squaring the input and multiplying by pi. The area that comes out is 25 pi which is about 78.54. The 25pi is an *exact* output and the 78.54 is approximate --- note that these are not equal! 

Here's an important fact about functions in any representation. No matter whether our function is data, a graph, or a formula, we use what's called  **function notation** for working with it. Notation in mathematics just means the way that we name things. For example pi is the notation we use for this number that arises in the study of circles. The notation is just a handy way of referring to the concept. When we have a function with an independent or input variable as well as a depdendent or output variable, we often notate it by writing the dependent variable and next to it placing the independent variable in parentheses. For example we'd notate our area of a circle function like this, and we'd pronunce that A of r. Please note this is NOT multiplication of A times r. This is function notation that tells us that r is the input variable and A is the output variable. 

If our function is given as a formula, we often state that the function is equal to the formula, for example A(r) = pi r^2 which is pronounced "A of r equals pi r squared". Then, to evaluate the function, let's say at a radius length of 5, we replace all instances of r with 5 on both the left and the right. This is A of 5, and it's equal to 25pi. Likewise A(3) is the area when the radius is 3, and that's pi 3^2 or 9pi. 

Here's another example: B(t) = t^2(t-1). This is a function where the input or independent variable is called t, the output or dependent variable is called B, and the process for evaluating the function is given by ths formula. For example if you give me an input of t = 4, the output is B(4) = 4^2(4-1) --- just replace all instances of t with 4 --- then do the math on the right: B(4) = 16(3) which is 48. 

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