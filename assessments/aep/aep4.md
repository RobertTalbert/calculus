---
tags: mth201, templates
---

# AEP 4: Local Linear Approximations

Have you ever wondered how a calulator knows how to compute numbers like $\sqrt{2}$ or $e^5$, which don't have simple decimal representations? The explanation lies with the use of calculus to build models of functions that are simple, yet accurate *approximations* to functions such as $y = \sqrt{x}$ and $y = e^x$. In this AEP, you'll learn how to build the simplest such approximation. 


## What this AEP is about 

We rely a lot on computers and calculators to do computations for us, but we don't often stop to think about how these devices actually work. For example, even Google "knows" how to find an 11-decimal approximation to $\sqrt{2}$: 

![sqrt2](https://i.ibb.co/rb88P5t/download.jpg)

But how did it do that? 

The simple answer is, **it didn't**. Most computers (including calculators) don't actually compute values like $\sqrt{2}$ and then give us an approximation; they *approximate the values to start with* using a simple replacement for a function that produces that value. 

Suppose you wanted to compute $\sqrt{1.5}$. Think of this value not as a number, but as **the output of the function $f(x) = \sqrt{x}$ when $x = 1.5$**. If you can find a simpler function whose graph closely resembles the graph of $y = \sqrt{x}$ near $x = 1.5$, then you can use the simpler function to give you a good approximation. Here's a Desmos plot of two functions: 

![](https://i.ibb.co/rM0yGq2/desmos-graph-7.png)

The red graph is $f(x) = \sqrt{x}$. The blue one, that peels away toward the end of the window, is 

$$g(x) = 1 + \frac{1}{2}(x-1) - \frac{1}{8}(x-1)^2 + \frac{1}{16}(x-1)^3$$
 
They are not perfect matches, although they do agree at $x=1$. However notice that at $x = 1.5$, **they are very close to each other**. (Interactive plot here: https://www.desmos.com/calculator/aodq92dd9r) In fact, if you plug in $x=1.5$ to the second function, you get $g(1.5) \approx 1.2265625$. On the other hand the true value of $\sqrt{1.5}$ out to 11 decimal places is $\sqrt{1.5} \approx 1.22474487139$, a difference of only $0.1\%$. And the second function, while it looks complicated, only consists of basic arithmetic functions (adding, subtracting, multiplying, and dividing) which is something computers are built to do. 

So the answer to "How does a computer compute?" is that it **approximates using simpler functions**. In this AEP you'll learn how to use calculus to find such functions. 


 
## Prerequisites and tech requirements 

You will be ready to begin this AEP following **Module 5.** (One task uses a derivative method from that Module.)

**Technology used in this AEP:** Just the basic functions of Desmos for plotting graphs and making calculations. 

## Background and setup 

Before starting this AEP, do the following: 

- Read the introductory material above. 
- In the _Active Calculus_ textbook, [read through Section 1.8](https://activecalculus.org/single/sec-1-8-tan-line-approx.html), "Local Linear Approximations". 
- Here are some videos that can help as well: 
    - Quick review of the tangent line approximation (2:18) [http://gvsu.edu/s/0PC](http://gvsu.edu/s/0PC)
    - Calculating a tangent line (5:42) [http://gvsu.edu/s/0PD](http://gvsu.edu/s/0PD)
    - Using a tangent line (3:27) [http://gvsu.edu/s/0PE](http://gvsu.edu/s/0PE)
    - Using the local linearization (7:07) [http://gvsu.edu/s/0PF](http://gvsu.edu/s/0PF)

## AEP Tasks 

1. The reading and viewing define and discuss the *local linear approximation* of a function near a point. In your own words, what is this concept, and what is it used for? 

2. Find the local linear approximation of $y = 3 \cos(x) \sin(x)$ at $x = \pi$ and again at $x = 3\pi/4$. Show all work used in the process. Then plot all three of these items (the function and the two local linear approximations) in Desmos, on an appropriately sized window that contains at least $x=0$ and $x = 4$. Share a link to this plot in your writeup. 

3. Look at the two approximations from the previous task. If you wanted to use one of them to approximate the value of $3 \cos(2.5) \sin(2.5)$, which one would you choose, and why? After explaining this, use the local linear approximation you chose to get an approximate value of $3 \cos(2.5) \sin(2.5)$ and make your reasoning clear. 

4. Suppose $C = f(n)$ gives the cost (in dollars) of producing $n$ milligrams of Covid-19 vaccine. The data from your lab says that $f(100) = 5000$ and $f'(100) = 10$. Build a local linear approximation for $f$ and estimate the cost needed to produce $125$mg of the vaccine. Show all your steps. 

5. In the vaccine situation above, suppose you also know from your data analysis that $f''(100)$ is negative. Which of the following best describes how the cost is changing as more vaccine is produced? 
   - Cost is increasing at an increasing rate
   - Cost is increasing at a decreasing rate
   - Cost is decreasing at an increasing rate
   - Cost is decreasing at a decreasing rate 
State your choice clearly and fully explain how you know it's right. **Then**, use this to state whether the estimate from the previous question is likely to be an *overestimate* (i.e. the true value of the cost is probably lower than the estimation), or an *underestimate* (the true value of the cost is probably higher than the estimation). Explain your reasoning fully and clearly. *Suggestion:* A quick sketch of what the graphs of $C$ and its local linear approximation on the same set of axes might help. 

6. Write a 1-2 paragraph summary of your work on this AEP, addressing the following: 
    - What concepts from the course were used in your work
    - How the work you did here could be useful in a different application setting 
    - Three things you learned in the process of completing this assignment
    - At least one substantive question that you still have (Please, do not ask questions about the assignment itself, grades or the course; ask about math, technology, or something related to the core concepts.)

## Grading criteria and submission instructions

Please refer to the [overall quality standards for AEPs](https://hackmd.io/@rtalbert235/HkSbMs2Av) at the link (and posted to the *AEPs* area on Blackboard) first, and make sure your work meets all these criteria. In addition to the overall standards, this AEP has the following specific standards: 



| Mark: | Criteria:  |
| -------- | --------  |
| **E** (Excellent)     | All the criteria for an M are satisfied, and additionally there are no mathematical mistakes; all verbal explanations are clear, easy to understand, and mistake-free; and the presentation of the writeup is neat and professional.          |
| **M** (Meets Expectations) | <ul><li>The link in Task 2 must work.</li><li>All mathematical computations are correct. </li><li>All verbal explanations are correct, clear, and written in standard English with little to no errors in writing.</li><li>All items that require a clear explanation, whether in writing or in math, have those explanations.</li><li>The reflection in Task 6 must be clear and  professionally written (no grammar/spelling errors).</li></ul>   | 

Please [see the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-are-individual-assignments-graded) for how grades of **P** (Progressing) and **X** (Not Assessable) are assigned. 


To submit this AEP: 

- Create a **typed document** using a word processor utilizing an equation editor for any significant mathematical notation. **Submissions that are handwritten or contain any handwritten work without prior permission will be graded "X" and returned without comment.** 
- Save the document as a PDF. Please **do not submit Word (.doc, .docx) or Open Office (.odt) files** as these do not always render mathematical notation correctly on screen. 
- Upload the PDF to the appropriate AEP assignment in the *AEPs* area on Blackboard. **Remember to hit the "Submit" button after uploading**, otherwise your work is merely on the Blackboard server and not in the instructor's grading queue. 

Once graded, the grade (E, M, P, X) will appear in your gradebook. You can then open the submission to view feedback left by the professor. These appear as text comments on the page or as general comments next to the grade. Grades of E or M may not have much feedback. Grades of P or X *always* have feedback, so please look carefully for this. 

For information on revisions of AEPs, please [consult the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-do-I-revise-and-resubmit-my-work).


[![hackmd-github-sync-badge](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw/badge)](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw)