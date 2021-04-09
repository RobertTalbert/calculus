---
tags: mth201, templates
---

# AEP 7: Average value of a function




## What this AEP is about 

This AEP will guide you through self-teaching of a topic we left out of the syllabus, on how to use a definite integral to find the **average value** ofa function. 

## Prerequisites and tech requirements 

You will be ready to begin this AEP following **Module 11.** 

**Technology used in this AEP:** The usual --- Desmos for visualizing data and Wolfram|Alpha for automatic symbolic calculations. The [Riemann sum applet](http://webspace.ship.edu/msrenault/GeoGebraCalculus/integration_riemann_sum.html) might be useful as well. 

## Background and setup 

How would you find the "average height" of this function, $f(x) = \frac{x^2}{10}+1$, from $x=0$ to $x=6$? 

![](https://i.imgur.com/yJS4Mfu.png)

It starts at a height of $f(0)= 1$ and ends at a height of $f(6)=4.6$. So you might just find the *statistical average* of those two heights: $\frac{1 + 4.6}{2} = 2.8$. Here's the graph again with $y=2.8$ drawn on top:

![](https://i.imgur.com/4rsWCyH.png)

Something about this seems wrong --- most of the time, the function is *below* this average. How can most of the graph be below average? Maybe our statistical average is biased because the function increases rapidly at the end. What if we instead found the height of the function at each point $x=0,1,2,\dots,6$ and averaged those instead? Plugging in those seven $x$-values to $f$ and then averaging gives us: 

$$\frac{1 + 1.1 + 1.4 + 1.9 + 2.6 + 3.5 + 4.6}{7} = 2.3$$

This seems like a more accurate average: 

![](https://i.imgur.com/BiFGI6s.png)

We could improve the average even more by **taking more sample points, finding their heights, and then dividing by the number of points** to get the average. 

This idea of getting the heights of the points should remind you of a *Riemann sum* --- except with a Riemann sum we also multiply by $\Delta x$ each time to get an area. This is an estimate to an integral, and the estimate, just like our average, gets better as we increase the number of points. 

So we will define the **average value of a function $f(x)$ on an interval $[a,b]$ like this: 

:::info
If $f$ is a continuous function on $[a,b]$, then its average value on $[a,b]$ is given by 
$$f_{\text{AVG}[a,b]} = \frac{1}{b-a} \int_a^b f(x) \,dx$$
:::
That is, finding the average value of a function --- think of it as a continuous stream of numbers rather than a finite list --- is *not* just adding up numbers and dividing, but **integrating the function** (which is like the "adding up" part) and then dividing not by the "number of points" because that's infinite, but rather dividing by the length of the interval. 

:::success
**Example:** The average value of $f(x) = \frac{x^2}{10} + 1$ on $[0,6]$ as discussed above is
$$\begin{align*}
\frac{1}{6-0} \int_0^6 \left( \frac{x^2}{10} + 1\right) \, dx &= \frac{1}{6}\left[ \left. \frac{x^3}{30} + x\right|_0^6 \right] \\
&= \frac{1}{6} \left( \left( \frac{216}{30} + 6  \right) - \left(0 + 0 \right)  \right) \\
&= \frac{11}{5} = 2.2
\end{align*}$$
:::



**Before beginning the tasks below**, get some more information on average values of functions by doing the following: 

- Watch this 8-minute video from the MTH 201 playlist on average value: https://www.youtube.com/watch?v=MQG9Nur4fdM  
- Read [Section 4.3.3](https://activecalculus.org/single/sec-4-3-definite-integral.html) in the textbook that talks about average value: 

## AEP Tasks 

1. Find the average value of the function below, on the interval $[-4,6]$. On this one, *show ALL your work* and *use exact values only, no decimals.* The function is entirely made up of line segments and parts of circles. 

![](https://i.imgur.com/Sp88BRY.jpg)

2. In class, Prof. Talbert randomly chose $y = x^2 \tan(x)$ as an example a function that's hard to integrate. 
    - Estimate the value of $\displaystyle{\int_0^{1/2} x^2 \tan(x) \, dx}$ using a midpoint Riemann sum and 8 rectangles. Show all your setup work, then crunch the numbers on a computer and give an answer correct to six decimal places. 
    - Determine the average value of $x^2 \tan(x)$ on $[0,1/2]$ using the estimate from the previous part. Explain your reasoning. 
    - Check your work by graphing $y = x^2 \tan(x)$ along with the average value plotted as a horizontal line, like in the graphs above. (The average value should *look like* the actual average height of the function.) Include an image of your graphs. 

3. Find a function that involves one independent variable and one dependent variable. If you've done AEP 1, 2, or 3 you might consider using the function you picked out for those assignments. Determine an interval of the input that you are interested in. Then, determine the average value of your function over that interval. If your function is given as a table of data, you can do this in a couple of ways: either fitting the data with a well-fitting regression and then using the formula to find the average value, or just use the data to compute a Riemann sum with a good-sized number of rectangles. The choice is yours; just be sure to clearly state your method, use the best possible regression or a high number of rectangles, and show your steps. And also check your work to make sure it's reasonable. 


5. Write a 1-2 paragraph summary of your work on this AEP, addressing the following: 
    - What concepts from the course were used in your work
    - How the work you did here could be useful in a different application setting 
    - Three things you learned in the process of completing this assignment
    - At least one substantive question that you still have (Please, do not ask questions about the assignment itself, grades or the course; ask about math, technology, or something related to the core concepts.)



## Grading criteria and submission instructions

Please refer to the [overall quality standards for AEPs](https://hackmd.io/@rtalbert235/HkSbMs2Av) at the link (and posted to the *AEPs* area on Blackboard) for grading standards. There are no special rules for this AEP. 

Also please [see the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-are-individual-assignments-graded) for how grades of **P** (Progressing) and **X** (Not Assessable) are assigned. 


To submit this AEP: 

- Create a **typed document** using a word processor utilizing an equation editor for any significant mathematical notation. **Submissions that are handwritten or contain any handwritten work without prior permission will be graded "X" and returned without comment.** 
- Save the document as a PDF. Please **do not submit Word (.doc, .docx) or Open Office (.odt) files** as these do not always render mathematical notation correctly on screen. 
- Upload the PDF to the appropriate AEP assignment in the *AEPs* area on Blackboard. **Remember to hit the "Submit" button after uploading**, otherwise your work is merely on the Blackboard server and not in the instructor's grading queue. 

Once graded, the grade (E, M, P, X) will appear in your gradebook. You can then open the submission to view feedback left by the professor. These appear as text comments on the page or as general comments next to the grade. Grades of E or M may not have much feedback. Grades of P or X *always* have feedback, so please look carefully for this. 

For information on revisions of AEPs, please [consult the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-do-I-revise-and-resubmit-my-work).


[![hackmd-github-sync-badge](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw/badge)](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw)