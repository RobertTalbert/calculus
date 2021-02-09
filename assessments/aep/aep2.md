---
tags: mth201, aep
---

# AEP 2: Derivatives from data 

In this AEP, you'll seek out data on a topic of interest to you, construct the derivative of your data using both numerical approximations, and then analyze the first and second derivatives and think about what the information from the derivatives mean in context.


## What this AEP is about 

Data sets that involve two variables, and one of the variables is related to the other, are called **two-variable data sets**. An example of a two-variable data set is the Covid-19 data used in AEP 1, in which the number of cases of Covid-19 in a particular state was a function of time. There is an implied relationship between one variable and the other. For example, in the Covid-19 data, there is an implied relationship between time and Covid-19 cases -- as time passes, the number of cases changes. Time is like the input variable to a function, and number of cases is like the output; we call time the *independent* variable and Covid cases the *dependent* variable because the number of cases *depends on* time. Covid-19 case numbers also depend on a host of other variables (population density, the percentage of the population wearing masks, etc.) but in our data set, *time* is the independent variable we focus on.

Note that there is no explicit formula that perfectly describes this relationship. If there were, then for example in the Covid-19 data, we could perfectly predict the number of Covid-19 cases on a given day, and there's just no way to do that. Instead, to tell the story of the data, we rely on **good estimates** using two kinds of approaches:

- We can simply use the data themselves without trying to model it at all with a formula or graph; or 
- We can try to construct a graph or formula that is as good of an approximation to the data as possible, then use the graph or formula. This approach was the focus of AEP 1, and the approximate function we construct there is called a **regression model**. 

**Both approaches are inexact by nature and will contain some error.** Just because we come up with a regression function, for example, does not mean that this function is infallible. As humans, we have to always think critically about the limitations and potential sources of error in any analysis of data we perform, no matter how exact-looking the model may be. 

In AEP 2, you'll have the opportunity to tell the story of a two-variable data set that interests you, using the numerical approach to analysis, and using what you've learned about the first and second derivative to dig deep into the hidden information your data set contains. 


## Prerequisites and tech requirements 

You will be ready to begin this AEP following **Module 3.** In particular, you'll need knowledge of *derivative estimation techniques*, *concavity*, and the *second derivative* which are topics introduced in Module 3. 

**Technology used in this AEP:** 

- You'll be asked to put a set of data into a **spreadsheet** that can be shared online. The best choice is Google Spreadsheets; you won't be doing any special operations with spreadsheets, just using them as a convenient way to store and share your data. However, if you can learn how to use a spreadsheet to do some simple calculations, it will cut down on the amount of busy work tremendously. MS Excel is acceptable, but you will be asked to share your spreadsheets online if you do so. 

## Background and setup 

Think of a topic that interests you -- sports, politics, weather, etc, Then go to the internet and search for **a two-variable data set that relates two quantities involved with that topic**. You may use any kind of data you like as long as:

 
- It *doesn't involve Covid-19 cases and time*, because this is the subject of AEP 1.
- The set involves *only two variables*, and there are *at least five pairs of data in the set*.
- The data set is *real* (not made up by you) and you can *provide a link to the source*.
- The data set has *some kind of personal relevance to you, that you can explain.* You are especially encouraged to look for data that relate to your academic major in some way.
  

For example, I (Prof. Talbert) like to cook, so recently I began to wonder how the prices of some of the ingredients I use have changed over time. Doing a Google search on "price of a pound of ground beef over time" led me to this site, which shows the price in US dollars of a pound of beef in each year from 1995 to 2017. (Here the independent variable is time in years, and the dependent variable is price in US dollars.)

https://www.statista.com/statistics/236776/retail-price-of-ground-beef-in-the-united-states/

  
Once you have found a data set you like, **place your data into a Google Spreadsheet with the independent variable data in column A and the dependent variable data in column B.** IMPORTANT NOTE: If you are using data for years, rescale the data so that time = 0 corresponds to your first year. This will avoid issues with the regression analysis later.

For example, here are my ground beef data, entered in with 1995 set as year 0: <https://i.imgur.com/WK4nxxs.jpg>

If your data set is very long, over 30 pairs, you are allowed to use just a subset of the data consisting of 30 pairs. Most of the calculations in this lab are done with technology, so don't worry about the number of hand computations. But don't cut out more than this, or you will lose accuracy (and this is considered bad data analysis).

Creating a Google Spreadsheet is the same process as creating a Google Doc -- just choose Spreadsheets instead of Documents when creating. If you are unfamiliar with this process, please contact the professor or friend, or ask a question on Campuswire and tag it with `Technology`. 

## AEP Tasks 

1. Copy and paste a link to the source of your data, and write a short paragraph explaining why you chose it and why it's of interest to you personally. 

2. Enter your data into a Google Spreadsheet as described above. Then get a link to share that spreadsheet, and make sure that the link allows **Anyone with the link** (not just Grand Valley State University people) to **Edit** (not just view or comment). Here is a short video showing how to do this (some of the specifics may be different for you, but the process is the same): https://drive.google.com/a/mail.gvsu.edu/file/d/1Ysd-DaJiDTGNPMhqlhEBdnPLYLbeCTEn/view?usp=drivesdk I will be checking your data directly in your spreadsheet, so it's important that I can edit the work you've done. In your writeup, just paste the link for this task.


3. Either in your writeup or in the spreadsheet (your choice), **construct a table of values for both the first and second derivatives of the data you have**. In the writeup, give an explanation that is 2-3 complete sentences long that explains how you constructed the first and second derivatives. **Your work here should use the derivative estimation techniques from Module 3. Please do not use formulas (such as regression models) or graphs.** You do not need to show work, but the work must be correct and your explanation should be such that a reader could replicate the process with no mistakes if they follow your directions. 

:::info
**Pro tip:** It is *much* less work if you can figure out how to do these calculations automatically using the spreadsheet, rather than doing them all separately by hand and then typing the results into the spreadsheet. Learning how to do these calculations automatically in the spreadsheet is also a valuable transferable skill that you can use once MTH 201 is over. It may be well worth your time to search up some introductory Google Sheets tutorials to learn how to use "formulas" (as they are called) to automate these calculations. 
:::

For comparison purposes, Here is an example of the completed spreadsheet for my ground beef price example (explanation and work not shown): https://i.imgur.com/CS8KTmA.jpg

4. Using your computations from the previous task, identify all places where your data are: 
    a. Increasing at an increasing rate
    b. Increasing at a decreasing rate
    c. Decreasing at an increasing rate
    d. Decreasing at a decreasing rate 
And give a brief explanation for how you arrived at your results. ("I looked at the data" is not enough! Explain your reasoning as if you were writing to a MTH 201 classmate who knows the math but is not familiar with your data set.)

5. Use your data --- including the original data along with the first and second derivatives --- to give a non-technical, descriptive story about your data. Avoid technical words like "function", "derivative", "concave up", and "concave down" --- instead, interpret the increasing/decreasing and concave up/down behavior into terms that are understandable and accessible to a person who has not studied any calculus. Here's part of an example of a good description for part 5, using my ground beef data: 

>For most years from 1995 to 2017, the price of ground beef was increasing. The exceptions were in 1996-1997, 2006, 2008-2009, and 2015-2016. However the growth was not always occurring at the same rate. For example, from 2003 through 2006, the price of ground beef was increasing, but at a slowing pace. In some years, for example 1998-1999 and 2012-2013, the price of ground beef was increasing at an accelerating pace. At the end of this set of data, the price of a pound of ground beef reached a turning point, changing from decreasing in 2016 to increasing, at an increasing rate, in 2017. 

6. Write a 1-2 paragraph summary of your work on this AEP, addressing the following: 
    - What concepts from the course were used in your work
    - How the work you did here could be useful in a different application setting 
    - Three things you learned in the process of completing this assignment
    - At least one substantive question that you still have (Please, do not ask questions about the assignment itself, grades or the course; ask about math, technology, or something related to the core concepts.)


## Grading criteria and submission instructions

Please refer to the [overall quality standards for AEPs](https://hackmd.io/@rtalbert235/HkSbMs2Av) at the link (and posted to the *AEPs* area on Blackboard) first, and make sure your work meets all these criteria. In addition to the overall standards, this AEP has the following specific standards: 



| Mark: | Criteria:  |
| -------- | --------  |
| **E** (Excellent)     | All the criteria for an M are satisfied, and additionally there are no mathematical mistakes; all verbal explanations are clear, easy to understand, and mistake-free; and the presentation of the writeup is neat and professional.           |
| **M** (Meets Expectations) | <ul> <li>The links to the data source and spreadsheet must work; the spreadsheet must be set to "Anyone with the link can edit".</li><li>All the first and second derivative calculations should be correct and the process of getting them fully explained.</li> <li>The reponses in Task 4 should correctly reflect the data in Task 3. </li><li>The narrative summary in Task 5 has to be clear, professionally written (no grammar/spelling errors), and pitched to the right level of audience.</li></ul>   | 
| **X** (Not Assessable) | A grade of "X" will be given automatically, and the draft returned without comment, if the link given to the data source in Task 1 is dead (that is, following the link leads to a disconnected or nonexistent site) or if it is clear that the data are not real (that is, they are made up by the student or someone else). | 

Please [see the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-are-individual-assignments-graded) for how grades of **P** (Progressing) and **X** (Not Assessable) are typically assigned. 


To submit this AEP: 

- Create a **typed document** using a word processor utilizing an equation editor for any significant mathematical notation. **Submissions that are handwritten or contain any handwritten work without prior permission will be graded "X" and returned without comment.** 
- Save the document as a PDF. Please **do not submit Word (.doc, .docx) or Open Office (.odt) files** as these do not always render mathematical notation correctly on screen. 
- Upload the PDF to the appropriate AEP assignment in the *AEPs* area on Blackboard. **Remember to hit the "Submit" button after uploading**, otherwise your work is merely on the Blackboard server and not in the instructor's grading queue. 

Once graded, the grade (E, M, P, X) will appear in your gradebook. You can then open the submission to view feedback left by the professor. These appear as text comments on the page or as general comments next to the grade. Grades of E or M may not have much feedback. Grades of P or X *always* have feedback, so please look carefully for this. 

For information on revisions of AEPs, please [consult the syllabus](https://hackmd.io/@rtalbert235/SJ5fDZIAv#How-do-I-revise-and-resubmit-my-work).


[![hackmd-github-sync-badge](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw/badge)](https://hackmd.io/0hGsJdDIQ32XTMVuy2I1tw)