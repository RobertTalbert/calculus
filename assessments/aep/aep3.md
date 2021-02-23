---
tags: mth201, templates
---

# AEP 3: More derivatives from data

In this AEP, you'll use an earlier data set to build several function models for the data, then use what you've learned from Modules 2-4 to analyze their derivatives and interpret what the derivatives tell you. 


## What this AEP is about 

:::info
**Note:** You do *not* need to complete AEP 1 or 2 to do this AEP, but it helps; and we'll be referring back to some of the instructions and notes from those AEPs here. 
:::

In AEP 1 and 2, we looked at taking data that relates two variables and using tables of data to estimate and interpret the derivatives of that relationship. In this AEP, we are going to take this one step farther and use Desmos' **regression** capabilities to build formulas to model data, then use rules and concepts we've learned to think about the first and second derivatives of those functions and what information they might convey. 

## Prerequisites and tech requirements 

You will be ready to begin this AEP following **Module 4.** In particular, you'll need the basic derivative rules for power, polynomial, and exponential functions, along with an understanding of how to interpret information about derivatives and concavity. 

The different kinds of *regressions* used in this AEP (see below) require knowledge of different kinds of functions, from your precalculus knowledge. You'll need to know the definitions and some examples of each of these kinds of functions: 

- Linear functions
- Power functions
- Polynomial functions; and polynomials of a given *degree* (for example, what is a "fourth degree polynomial")
- Exponential functions

Since these are prerequisite topics, review on this is not included in this AEP; it's up to you to seek out review material and ask questions if you need to. 

**Technology used in this AEP:** 

- This AEP relies heavily on Desmos and its ability to compute **regressions**. As described in AEP 1, a *regression* is a function constructed to be the "best fit" through a plot of points. A basic explanation of what a regression is, is found here: https://www.khanacademy.org/math/probability/regression And a brief tutorial on how to construct regressions in Desmos is given here: https://learn.desmos.com/regressions. Finally, here is a sample Desmos worksheet where different kinds of regressions are constructed, so you can see the basic template: https://www.desmos.com/calculator/ycldxhrez1 
- You'll also need to be able to share a Desmos worksheet, as you learned in the Tools Assignment. 


## Background and setup 

For this AEP, you are to use a set of data to build some models. To obtain these data, you can do any of the following: 

- Use the Covid-19 data for the state or territory that you examined in AEP 1, if you've done AEP 1; 
- Use the two-variable data set that you used in AEP 2, if you've done AEP 2; or 
- Find a two-variable data set as described in AEP 2. 

Once you have the data, enter it into a table in Desmos. The easiest way to do this is put the data into a two-column spreadsheet first, then copy the data, and then paste it into Desmos. (The regressions tutorials above show how to do this, but it's literally just copy and paste.) Make sure to save your Desmos workspace when signed in using your GVSU Google account; this will allow you to save it and reopen it later. 

:::success
**Pro tip**: While you technically don't need to have completed AEP 1 or 2 to do AEP 3, if you have *not* completed AEP 1 or 2 yet, it's a really good idea to pair it with AEP 1 or 2 and do both AEP's at the same time using the same set of data. It's like a 2-for-1 package! 
:::

## AEP Tasks 

1. Use Desmos to build regressions for your data using the following kinds of models. Next to each type of model is the Desmos code you should enter in for it. 

    - Linear: `y_1 ~ mx_1 + b`
    - Power: `y_1 ~ ax_1^b`
    - Second-degree polynomial: `y_1 ~ ax_1^2 + bx_1 + c`
    - Third-degree polynomial: `y_1 ~ ax_1^3 + bx_1^2 + cx_1 + d`
    - Fourth-degree polynomial: `y_1 ~ ax_1^4 + bx_1^3 + cx_1^2 + dx_1 + f`  (Note: That's an `f` at the end. You can't use the letter `e` for a parameter value because Desmos thinks this is the *number* $e$. And if you have defined a function in this worksheet using `f(x)` then you'll have to use `g` or some other letter.)
    - Exponential: `y_1 ~ ab^x_1`
In this part, **please also include working links to the data that you used and to your Desmos worksheet**. 

2. You've now built six different models for your data. In each model there is a statistic called $R^2$. This is a number between 0 and 1 that, roughly speaking, tells you how good the fit is between the model and the actual data. No model fits perfectly; but the closer $R^2$ is to 1, the better the fit. State which model has the highest $R^2$ for your data, and then state the formula for that model in your writeup. Also, in Desmos, enter this model's formula and call it `M(x)`. 

3. Hide all the objects in your Desmos worksheet except the data plot and the graph of $M(x)$. (Do this by clicking on the circle on the left of each cell. Clicking again makes the object reappear.) Then on top of these two, plot the first and second derivatives of $M(x)$. You can do this just by typing `M'(x)` and `M''(x)` in Desmos. Write a 2-3 sentence summary explaining what the graphs of the first two derivatives tell you about your model. Your summary should be specific (not a general explanation but what information about your particular set of data that you learn from the derivatives), clear, and understandable by a fellow student without that person having to fill in gaps or do extra work. 

4. On your writeup, use the derivative rules from Sections 2.1 and 2.2 to calculate the first and second derivatives of $M(x)$.  Then find the values of the first and second derivatives at a point of your choosing taken out to ten decimal places. Show all your work here (it won't be much).

5. Having completed the above tasks, think about this question: What are the relative strengths and weaknesses of finding the derivative of a function using numerical estimation techniques (as was done in AEP 1 and 2) versus using formula-based techniques as we are doing here? Write a thoughtful, well constructed, 2-3 sentence response. 

6.  Write a 1-2 paragraph summary of your work on this AEP, addressing the following: 
    - What concepts from the course were used in your work
    - How the work you did here could be useful in a different application setting 
    - Three things you learned in the process of completing this assignment
    - At least one substantive question that you still have (Please, do not ask questions about the assignment itself, grades or the course; ask about math, technology, or something related to the core concepts.)



## Grading criteria and submission instructions

Please refer to the [overall quality standards for AEPs](https://hackmd.io/@rtalbert235/HkSbMs2Av) at the link (and posted to the *AEPs* area on Blackboard) first, and make sure your work meets all these criteria. In addition to the overall standards, this AEP has the following specific standards: 



| Mark: | Criteria:  |
| -------- | --------  |
| **E** (Excellent)     | All the criteria for an M are satisfied, and additionally there are no mathematical mistakes; all verbal explanations are clear, easy to understand, and mistake-free; and the presentation of the writeup is neat and professional.           |
| **M** (Meets Expectations) | <ul> <li>The links to the data source and Desmos worksheet must work.</li><li>All the models requested must be correctly constructed in Desmos and the one with the highest $R^2$ value must be correctly identified and written in the writeup and i Desmos.</li><li>The first and second derivatives must be plotted correctly.</li> <li>The explanation of what the derivatives tell you must be specific, given in the context of the original data, clearly written, and contain no errors. </li><li>The narrative summaries in Tasks 5 and 6 must be clear, professionally written (no grammar/spelling errors), and pitched to the right level of audience.</li></ul>   | 

Please [see the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-are-individual-assignments-graded) for how grades of **P** (Progressing) and **X** (Not Assessable) are assigned. 


To submit this AEP: 

- Create a **typed document** using a word processor utilizing an equation editor for any significant mathematical notation. **Submissions that are handwritten or contain any handwritten work without prior permission will be graded "X" and returned without comment.** 
- Save the document as a PDF. Please **do not submit Word (.doc, .docx) or Open Office (.odt) files** as these do not always render mathematical notation correctly on screen. 
- Upload the PDF to the appropriate AEP assignment in the *AEPs* area on Blackboard. **Remember to hit the "Submit" button after uploading**, otherwise your work is merely on the Blackboard server and not in the instructor's grading queue. 

Once graded, the grade (E, M, P, X) will appear in your gradebook. You can then open the submission to view feedback left by the professor. These appear as text comments on the page or as general comments next to the grade. Grades of E or M may not have much feedback. Grades of P or X *always* have feedback, so please look carefully for this. 

For information on revisions of AEPs, please [consult the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-do-I-revise-and-resubmit-my-work).


[![hackmd-github-sync-badge](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw/badge)](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw)