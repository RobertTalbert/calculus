---
tags: mth201, templates
---

# AEP 5: Exploring logistic functions 


This AEP puts some of our derivative rules, along with tools for finding concavity and inflection points, to work in exploring a class of functions used in population and financial modeling. 

## Prerequisites and tech requirements 

You will be ready to begin this AEP following **Module 8.** 

**Technology used in this AEP:** Desmos for graphing functions; Wolfram|Alpha for finding derivatives and solving equations. 



## What this AEP is about 

A lot of real-world quantitative situations involve data that behave like this: 

- The data start with small values
- There is initially rapid, exponential growth
- However at some point, the data stop growing exponentially; the values continue to grow, but approaching some upper limit. 

This happens, for example, when studying a population living in an environment with outside constraints like predators or physical limitations; or a university that experiences initially fast enrollment growth but then the enrollment growth slows as limitations on dorm spaces and classroom facilities are reached. 

A class of functions that models behaviors like this is called **logistic functions**. Logistic functions all have the same form: 

$$f(x) = \dfrac{L}{1 + e^{-k(x-a)}}$$

In this function, 

- $x$ is the input variable; it often represents time 
- $L$ is the upper limit that the data approach as $x$ gets very large  ($L$ must be positive)
- $k$ is a growth rate ($k$ must also be positive)
- $a$ is a horizontal shift value 
- $e$ is the usual number, $e \approx 2.71828...$

For example, here's the logistic function $f(x) =\frac{10}{1 + e^{-0.1(x-2)}}$:

![enter image description here](https://i.ibb.co/gm1tKk5/desmos-graph-30.png)

Notice the "S" shape of the curve. This shape is the distinctive feature of logistic functions, and the reason they are so widely used in modeling real data. 

Here's a Desmos graph that allows you to play with sliders to see the effects of changing the parameters in a logistic function: https://www.desmos.com/calculator/kf3dod6jwn  You might need to adjust the viewing window to get a good look at the graph, depending on how you set the sliders. 

## Setup 

You're going to build your own random logistic function to work with on this AEP, so that we're not all using the same one. Go to [Wolfram|Alpha](http://wolframalpha.com) and generate the following: 

- A random number between 5 and 50, and let this be $L$. 
- A random number between 0.05 and 0.35, and let this be $k$. 
- A random number between $-5$ and $5$, and let this be $a$. 

To generate a random number between two bounds $a$ and $b$, just enter "random number between a and b" and hit enter. For example, [here's how to generate a random number between 10 and 10000](https://www.wolframalpha.com/input/?i=random%20number%20between%2010%20and%2010000). 

## AEP Tasks 

1. List the values of $L$, $k$, and $a$ that you generated (and state which is which). Then go to Desmos.com, enter your logistic function with those parameter values, and adjust the viewing window so that the "S" shape is clearly visible. ([Here's an example of a logistic function with a bad viewing window](https://ibb.co/XbPsCFd); [here's the same function in a much better window](https://ibb.co/c3cgp0h).) In the writeup, share a link to your Desmos graph. 
2. Using the derivative rules of Chapter 2, **find the first derivative of your logistic function**. You'll need to show all the steps on this and simplify completely. To make this neat and professional: First do all the calculus separately and make sure your answer is correct; then type up your work *using correct notation*. For this AEP, "correct notation" means in particular to use actual fractions and exponents, and don't type up the work using basic text input from the keyboard. For example, `20/(1+e^(-0.2(x-2)))` all in one line is not correctly formatted; writing it as $\frac{20}{1+e^{0.2(x-2)}}$ is correct. If you need help, please ask on Campuswire. 
3. Does your logistic function have any critical values? If so, find them. If not, explain why not. 
4. Now **find the second derivative of your logistic function**. For this, you can use Wolfram|Alpha to find the second derivative, but you need to state in your writeup the second derivative fully simplified and formatted as described earlier. Also, give the link to the Wolfram|Alpha calculation Then **make a second derivative sign chart** for your function and **find the interval on which it's concave up and the interval where it's concave down**, and **find the exact $x$- and $y$-coordinate of the inflection point**. All algebra steps can be done using Wolfram|Alpha, but please give links to any calculation you perform using that tool. 
5. Look at the $y$-coordinate of the inflection point and compare it to the value of $L$, the upper limit that the function approaches. You should notice a relationship between the two. What do you notice?
6. Write a 1-2 paragraph summary of your work on this AEP, addressing the following: 
    - What concepts from the course were used in your work
    - How the work you did here could be useful in a different application setting 
    - Three things you learned in the process of completing this assignment
    - At least one substantive question that you still have (Please, do not ask questions about the assignment itself, grades or the course; ask about math, technology, or something related to the core concepts.)



## Grading criteria and submission instructions

Please refer to the [overall quality standards for AEPs](https://hackmd.io/@rtalbert235/HkSbMs2Av) at the link (and posted to the *AEPs* area on Blackboard) first, and make sure your work meets all these criteria. In addition to the overall standards, this AEP has the following specific standards: 



| Mark: | Criteria:  |
| -------- | --------  |
| **E** (Excellent)     | All the criteria for an M are satisfied, and additionally there are no mathematical mistakes; all verbal explanations are clear, easy to understand, and mistake-free; and the presentation of the writeup is neat and professional.         |
| **M** (Meets Expectations) | All the links to Desmos and Wolfram Alpha must work and show the correct computations. Both the first and second derivatives must be correct, fully simplified, and formatted as described above. (Putting your function as a single line of text, like `20/(1+e^(-0.2(x-2)))`, will result in an "R" grade and you'll need to resubmit with the right formatting. All the information needed for an "outsider" to understand your work needs to be self-contained within the work. **The reader should not have to do any work to fill in gaps.**  | 



Please [see the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-are-individual-assignments-graded) for how grades of **P** (Progressing) and **X** (Not Assessable) are assigned. 


To submit this AEP: 

- Create a **typed document** using a word processor utilizing an equation editor for any significant mathematical notation. **Submissions that are handwritten or contain any handwritten work without prior permission will be graded "X" and returned without comment.** 
- Save the document as a PDF. Please **do not submit Word (.doc, .docx) or Open Office (.odt) files** as these do not always render mathematical notation correctly on screen. 
- Upload the PDF to the appropriate AEP assignment in the *AEPs* area on Blackboard. **Remember to hit the "Submit" button after uploading**, otherwise your work is merely on the Blackboard server and not in the instructor's grading queue. 

Once graded, the grade (E, M, P, X) will appear in your gradebook. You can then open the submission to view feedback left by the professor. These appear as text comments on the page or as general comments next to the grade. Grades of E or M may not have much feedback. Grades of P or X *always* have feedback, so please look carefully for this. 

For information on revisions of AEPs, please [consult the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-do-I-revise-and-resubmit-my-work).


[![hackmd-github-sync-badge](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw/badge)](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw)