# AEP 1: Data-driven rates of change 

## Overview 

In this AEP, you will use technological tools to work with sets of data and build models of real-world quantitative phenomena, then apply what you've learned to determine average and instantaneous rates of change.

**Learning Targets associated with this AEP:**

+ F.1: I can find the average rate of change of a function on an interval.
+ D.1 **(CORE)**: I can find the derivative of a function, both at a point and as a function, using the definition of the derivative.
+ D.2 **(CORE)**: I can use derivative notation correctly, state the units of a derivative, estimate the value of a derivative using difference quotients, and correctly interpret the meaning of a derivative in context.

Remember, AEPs do not have fixed deadlines; simply work on this item until you are ready to submit it. But remember the **Two Items Per Week Rule.** 

## Technology Background

Before you begin this AEP, you will need to get comfortable with two

tasks using the Desmos online graphing tool: **graphing functions** and doing **regression analysis**. *Regression* refers to the process of approximating a collection of data with a function and then using the function to draw conclusions about the data.

Desmos can be accessed at `http://desmos.com`, or by going to Blackboard and clicking on **Course technology** and then **Desmos graphing tool**. There's also an app for mobile devices.

Please do the following before attempting this Lab:

  

- If you are not already familiar with graphing functions in Desmos, go to Blackboard and then **Course technology**, then **Desmos tutorials** and watch the three short videos that are there.
- Work through this short lesson on regression:
<https://www.khanacademy.org/math/probability/regression>. The "Scatter plots" portion of the lesson (which is the first grouping of videos and exercises) is really all you need, but you are welcome to work through the rest of the lesson as well. If you are already familiar with the concept of regression, you can just skim this section.
- Now learn how to use Desmos to construct regressions by accessing the interactive web page at <https://www.desmos.com/calculator?tour=regressions>.
- Once you have worked through the regressions tour, you can watch a video on using Desmos to do regressions at
 <https://www.youtube.com/watch?v=E9B0hQYfziw>.

Once you are sure you know how to create regressions in Desmos, you can continue on to the lab. If you are not yet sure and have a question, please post your question on Campuswire in the `#tech` channel to get help.

## AEP Description and Tasks 

### What this AEP is about
How fast is the typical American city growing right now? This is a question that a lot of people might want to know --- for example city councils, businesses and families thinking of moving to a new city, legislatures trying to determine voting district boundaries, and so on. We have lots of data showing *how many* people live in America's cities and towns but, surprisingly, not a lot of data to show *how fast* the population is changing. Since population is related to time, this is a *relationship that is affected by change* and so calculus should be helpful for answering the question!

 
For this lab, you'll select a city in the USA, build some models for its population over time, and then apply what you've learned about rates of change to estimate how fast the population was growing in 2016.

### Setup (do this first) 


**First**, go to this website, which generates randomly-selected US cities, and pick the first one off the list: <https://www.randomlists.com/random-us-cities>. Then go to that city's Wikipedia entry. Somewhere in the entry for your city should be a table that shows the US Census Bureau data for the "Historical population" of your city measured at 10-year intervals. If you cannot find that table for your city, generate another city.

**Second**, setup a **scatterplot** of your Census Bureau data in Desmos, by doing the following:

- In Desmos, create a table (click on the plus sign in the upper-left, then select Table). In the left column ($x_1$), enter in the year values from the census data *minus 1800*. This will rescale the numbers down to a more managable size. For example if your population data has years $1830, 1840, 1850, \dots, 2000, 2010$ then enter in the values $30, 40, 50, \dots, 200, 210$.
- In the right column ($y_1$), enter in the population values without rescaling. Once you enter these data in, Desmos will automatically create a "scatter plot" of the data, plotting each table entry as a single point. However, you'll need to change the axis settings to be able to see the points.

Here is a 1-minute video showing an example of this process, using Prof. Talbert's hometown of Nashville, TN (just the first five data points from the Census Bureau data): <http://bit.ly/2N4ojOM>. (The second-to-last character is a capital "O", not a zero.) You might need to enlarge the video to full screen in order to see some of the details.

### Tasks for this AEP

1. On Desmos, do the following:

	a. Create a linear function that approximates the data. The process for doing this is described in the resources under "Technology Background" above.

	b. Create a second-degree polynomial (that is, a parabola) that approximates the data. The process for doing this is described in the resources under "Technology Background" above.

	c. Create a *power function* that approximates the data. This is done similarly to the first two except you should type in:
$$y_1 \sim a x_1^n$$ 
(Remember that a power function is a function in which the variable is raised to a constant power, like $y = 3 x^5$.)

	d. Finally, create an *exponential function* that approximates the data. This is done similarly to the first two except you should type in: $$y_1 \sim a b^{x_1}$$ (Remember that an exponential function is a function in which the variable is a power, which is an exponent on a constant base, like $y = 3 \cdot 5^x$.)

	When you have these four graphs and the data table prepared, copy the link to your graph by clicking on the "Share" button in Desmos (it's in the upper right of the screen, to the left of the question mark; it looks like a square with an arrow pointing out of it.) Copy this link and paste it into your writeup. Double-check before you submit anything that the link actually works.

  

2. On each of the regression models you created with Desmos, there is a number called $R^2$. This number is a statistic that indicates the quality of the "fit" of the model to the data. It ranges between 0 and 1, with 1 indicating an exact fit of the graph to the actual data. The closer to $1$ this number is, the better the fit. Look through the models and choose the one that has the highest $R^2$ value, and state which one that is, and state the formula for that model in your writeup with the parameters $a$, $b$, $c$, etc. filled in with their numerical values. The values of the parameters are given on the graph. For example, look at the sample results here: <https://goo.gl/0U8atf>. In that example, the quadratic model has the best fit ($R^2 = 0.977$). That model has three parameters: $a$, $b$, and $c$ and their values are shown where it says "Parameters". This means that the formula for this model is

$$y_1 = 57.689x_1^2 - 7594.8x_1 + 244380$$ 

Your model might look different, since the quadratic model might not be the best fit for your data.

  

3. Now let's think about rates of change.

	a. The model you selected, and which you just wrote a formula for, can be used to approximate values of population that we *don't* have in the table. Use the formula for your model to estimate the population of your city in 2018. (Remember that $x_1$ represents time, and these values are shifted by 1800 years --- so you cannot just plug in 2016.)

	b. Find the average rate of change in the population from 2010 (the last known data point in the Census Bureau table) to 2016. Show your work, and put correct units of measurement on your answer.
	
	c. Use a table of values to estimate the *instantaneous* rate of change in your city's population in 2018. **Do not attempt to use any algebra.** For examples of how to evaluate limits using numerical methods, study Example 1.2.4 in the textbook. Show all your work; state your answer clearly; and put correct units of measurement on this answer.


## Assignment Expectations and Grading Criteria 

AEPs are graded using the "EMRN" rubric found in the syllabus. **A grade of E or M requires all of the following to be met:**

- The link to the Desmos graph --- consisting of the scatterplot of data and four regression models --- is given in question 1, the link works, and all four models and the data table are visible in the web page. **Writeups with a non-functioning link in question 1 will be automatically graded "N". Please check to make sure the link works before submitting.**
- The correct model is chosen in task 2 and a correct formula is given in the writeup.
- In task 3:
	- **All parts of task 3 must consist not only of correct, complete computations but also clear, correct English text that explains to the reader what is taking place.** Responses that are just raw calculations with no text will receive a "N" (Not Assessible) grade. Responses that have significant issues with the clarity or correctness of the explanatory text may receive a grade of R ("Needs Revision").
	- The computations in parts (a) and (b) are correct and the work is shown (in addition to the explanatory text).
	- The computation in part (c) is correct, and the numerical process involves at least 4-5 computations from the left and the same amount from the right. (For comparison, the first limit that is computed in Example 1.2.4(a) in the textbook, which is shown in Tables 1.2.5 and 1.2.6, uses eight computations each.)
- All work is shown, and all results are explained clearly. 

Please note, it is the case with all AEP's that **your grade is primarily based on your explanations and writing, and only secondarily on the precision and correctness of your computations.** Correct computations with insufficient explanation will need to be revised and may receive an "N" grade. 

A grade of "E" is given if all of the above expectations are met, and the work is of superior quality in terms of the clarity of explanations and work, appearance of the writeup, and precision of the mathematics. 


## Submitting your work 

**AEP submissions must be typewritten and saved as either a PDF or MS Word file. No part of your submission may involve handwriting; work that is submitted that contains handwriting will be graded N and returned without feedback.** This includes electronic handwritten docments, for example using a stylus and a note-taking app. To type up your work, you can use MS Word or Google Docs (both of which have equation editors for mathematical notation) or any other computer-based math typesetting tool. Just make sure you save your work as a Word document or PDF (no `.odt`, `.rtf`, or other file extensions are allowed).

When you have your work typed up, double-check it for neatness, correctness, and clarity. Then, go to Blackboard, then **Assignments**, then **AEP**, then **AEP 1**. Clicking on the text "AEP 1" will take you to a place on Blackboard where you can upload your work. All grading and revisions of labs are done entirely on Blackboard. **Do not email your work to the professor** -- only Blackboard submissions are accepted.

## Getting Help

Ple
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MDQ3OTE4NDNdfQ==
-->