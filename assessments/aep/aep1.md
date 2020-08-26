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

How fast is the typical American city growing right now? This is a question that a lot of people might want to know --- for example city councils, businesses and families thinking of moving to a new city, legislatures trying to determine voting district boundaries, and so on. We have lots of data showing *how many* people live in America's cities and towns but, surprisingly, not a lot of data to show *how fast* the population is changing. Since population is related to time, this is a *relationship that is affected by change* and so calculus should be helpful for answering the question!

 
For this lab, you'll select a city in the USA, build some models for its population over time, and then apply what you've learned about rates of change to estimate how fast the population was growing in 2016.

**First**, go to this website, which generates randomly-selected US cities, and pick the first one off the list: <https://www.randomlists.com/random-us-cities>. Then go to that city's Wikipedia entry. Somewhere in the entry for your city should be a table that shows the US Census Bureau data for the "Historical population" of your city measured at 10-year intervals. If you cannot find that table for your city, generate another city.

**Second**, setup a **scatterplot** of your Census Bureau data in Desmos, by doing the following:

- In Desmos, create a table (click on the plus sign in the upper-left, then select Table). In the left column ($x_1$), enter in the year values from the census data *minus 1800*. This will rescale the numbers down to a more managable size. For example if your population data has years $1830, 1840, 1850, \dots, 2000, 2010$ then enter in the values $30, 40, 50, \dots, 200, 210$.
<!--stackedit_data:
eyJoaXN0b3J5IjpbODUwOTU0NDQ4XX0=
-->