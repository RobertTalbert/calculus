---
tags: mth201, aeptemplates
---

# AEP 1: Rates of change from data


## What this AEP is about 

In this AEP, you will use technological tools to work with the New York Times' COVID-19 data sets tosets of data and build a models of econfirmed Covid-19 cases for a single US state and then apply the concepts ofomic or health data, then apply what you've learned to determine average/ and instantaneous rate of change to get an accurate estimate of how fast the number of cases is changing on a single day. s of change.

## Prerequisites and tech requirements 

You will be ready to begin this AEP following **Module 1.** 

**Technology used in this AEP:** 

- The data used in this AEP are stored in a Google Spreadsheet, found here: + [Desmos](https://docs.google.com/spreadsheets/d/1j-0--qqnoqM34Ot4q-TFFqq98LaIpAb_wVPxadibNKQ/copy?usp=sharing **When you click this link, you will be asked to make a copy. Do so, by clicking the button that says "Make a copy".** You don't have access to the original spreadsheet, to avoid accidentally altering the data. Once you click the "Make a copy" button, it will add it to your Google Drive; you can use the Google Drive that is associated with your GVSU Gmail account or your personal Google Drive if you have it. 
- You'll need to learn how to do a couple of operations in Google Spreadsheets to work with the data. Here is a 6-minute video that explains what you need and how to do it: esmos.com) to graph data points. You've seen how to graph formulas with Desmos, but you can also graph tables of data. Here is a tutorial: https://learn.desmos.com/tables Many more tutorials are available via a web search. 
+ [Desmos](https://www.screencast.com/t/DmpSBuf7U 
- Finally, you will need to learn how to use Desmos to construcdesmos.com) to plot **regressions**. A *regression* is a function constructed to be the "best fit" through a plot of points. A basic explanation of what a regression is, is found here: https://www.khanacademy.org/math/probability/regression And a brief tutorial on how to construct regressions in Desmos is given here: https://learn.desmos.com/regressions. Finally, here is a sample Desmos worksheet where different kinds of regressions are constructed, so you can see the basic template: https://www.desmos.com/calculator/ycldxhrez1 

**Several future AEPs will involve using Desmos to plot data and build regression formulas**, so learning these tasks now will pay off considerably later on. 


## Background and setup 


The number of cases and number of deaths from Covid-19 unfortunately still continues to be a dominant topic of discussion today. We can begin to use our Calculus skills to make sense of the data that have been collected on this, to make predictions and explanations of how the pandemic is continuing to unfold. 

As mentioned above, data on the number of cases and the number of deaths from Covid-19, for each of the 50 states in the USA and the District of Columbia, from 3/20/2020 through 1/14/2021 can be found in this spreadsheet: 

https://docs.google.com/spreadsheets/d/1j-0--qqnoqM34Ot4q-TFFqq98LaIpAb_wVPxadibNKQ/copy?usp=sharing


When you click this link, you'll be asked if you want to make a copy of the spreadsheet; say "Yes", and an editable copy of the spreadsheet will be added to your Google Drive. (You can use your GVSU Google account to save the spreadsheet if you don't have a personal Google account.) You can't edit the original spreadsheet because then nobody could use the data. 

Keep this spreadsheet handy, as you'll need it below. 

(The data were originally collected by the New York Times and published here: https://github.com/nytimes/covid-19-data/blob/master/us-states.csv) 

Before starting the tasks below, **choose one of the states or territories shown in the spreadsheet, and filter the spreadsheet so that you only see that state/territory's data**. (Instructions are linked above.) **Copy and paste the entire data set for that state/territory into a blank Desmos worksheet**. This will plot the data and automatically rescale the window. As in the example in one of the videos above, this may at first look like a continuous graph but actually it is a [scatter plot](https://en.wikipedia.org/wiki/Scatter_plot) made up of all the 300+ individual data points for that state. 



## AEP Tasks 

1. Using the data for your state, find the average rate of change in Covid-19 *cases* (not deaths) on each month from April 2020 through December 2020. Show your work on one calculation, then you can just state the remaining results (just double-check them to make sure there's no mistakes). Make sure to give correct units on your answers. Give a 1-3 sentence description of how the average case rates themselves change over time. 

2. In the Desmos worksheet you set up in the first task, use Desmos to construct linear, quadratic, and exponential regressions for the data. In your main writeup, for this part share the link to your Desmos worksheet. (Here's how to share the link: https://support.desmos.com/hc/en-us/articles/202528709-Permalink)

3. In each of your regression models in Desmos, there's a statistic called $R^2$. This is a number that ranges between 0 and 1, and it measures the "goodness of fit" of each model. The closer $R^2$ gets to 1, the better the fit is; an $R^2$ value of 0 would indicate no correlation between the model and the original data, while an $R^2$ value of 1 indicates a perfect fit where every point in the scatter plot lies on the graph of the model. Of the three models you made, find the one that has the highest $R^2$ value; if there's a tie, pick one to work with. In your writeup, write down the formula for this model. 

:::success
**Example**: In the [sample Desmos worksheet](https://www.desmos.com/calculator/ycldxhrez1) you were given, the quadratic model has the highest $R^2$ value at $0.969$. Desmos gives specific values for the $a$, $b$, and $c$ used in the model (under "Parameters"), and we can put those into the generic form to get: 
$$y = -9.48317x^2 + 2882.24x - 23685.7$$
By comparison, the linear model has the formula $y = 1364.93x + 1427$, and the exponential model has the formula $y = 55461.7(1.00912)^x$. We wouldn't use these models in this AEP since the quadratic model is a better fit, but that's what the formulas look like. 
:::

4. Using the model you selected in the previous problem, predict the number of Covid-19 cases in your state on the date that you submit your work. This number is not in the original data set, so you're using the model to make a forecast. Then look up this number in a reliable news source and report it, and provide a link to the source. How far off was your prediction? 

5. Using the model you selected in the previous problem, find the average rate of change in the number of Covid-19 cases on the following intervals: $[300, 301]$, $[300, 300.5]$, $[300, 300.1]$, $[300, 300.01]$, $[300, 300.001]$. Show all your work on at least one of these computations, then just state the results of the others. Put correct units on your answers. 

:::warning
**WARNING: Do not round off decimals here.** Rounding off will cause numerical error which will propagate and get worse as the size of the intervals shrinks. To save yourself a lot of copying of decimals, do your numerical calculations using a computer. 
:::

6. Based on the information from the previous task, how fast was the number of Covid-19 cases changing in your state on day 300? Explain how you know, and indicate the units of your answer. 

7. Write a 1-2 paragraph summary of your work on this AEP, addressing the following: 
    - What concepts from the course were used in your work
    - How the work you did here could be useful in a different application setting 
    - Three things you learned in the process of completing this assignment
    - At least one substantive question that you still have (Please, do not ask questions about the assignment itself, grades or the course; ask about math, technology, or something related to the core concepts.)
 Again, many more tutorials and examples can be found via a web search. 

**Several future AEPs will involve using Desmos to plot data and build regression formulas** so learning these tasks now will pay off considerably later on. 


## Background and setup 

(Give background + any initial steps that need to be taken)

## AEP Tasks 

## Grading criteria and submission instructions

Please refer to the [overall quality standards for AEPs](https://hackmd.io/@rtalbert235/HkSbMs2Av) at the link (and posted to the *AEPs* area on Blackboard) first, and make sure your work meets all these criteria. *In addition to the overall standards*, this AEP has the following specific standards: 



| Mark: | Criteria:  |
| -------- | --------  |
| **E** (Excellent)     | (no additional requirements beyond [the standard ones](https://hackmd.io/@rtalbert235/HkSbMs2Av))          |
| **M** (Meets Expectations) | The Desmos graph of the data should be appropriately sized with little to no dead space and showing all the data. All links that are requested must be given and must work.Text          |
| **M** (Meets Expectations) | Text   | 

Please [see the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-are-individual-assignments-graded) for how grades of **P** (Progressing) and **X** (Not Assessable) are assigned. 


To submit this AEP: 

- Create a **typed document** using a word processor utilizing an equation editor for any significant mathematical notation. **Submissions that are handwritten or contain any handwritten work without prior permission will be graded "X" and returned without comment.** 
- Save the document as a PDF. Please **do not submit Word (.doc, .docx) or Open Office (.odt) files** as these do not always render mathematical notation correctly on screen. 
- Upload the PDF to the appropriate AEP assignment in the *AEPs* area on Blackboard. **Remember to hit the "Submit" button after uploading**, otherwise your work is merely on the Blackboard server and not in the instructor's grading queue. 

Once graded, the grade (E, M, P, X) will appear in your gradebook. You can then open the submission to view feedback left by the professor. These appear as text comments on the page or as general comments next to the grade. Grades of E or M may not have much feedback. Grades of P or X *always* have feedback, so please look carefully for this. 

For information on revisions of AEPs, please [consult the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-do-I-revise-and-resubmit-my-work).


[![hackmd-github-sync-badge](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw/badge)](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU1NzExNTYzOV19
-->