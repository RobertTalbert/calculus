# Script for Functions Bootcamp video 1

Almost every situation you encounter in real life involves quantitative information in some way or another. 

Let's suppose for example you want to go for a run to get some exercise. The simple act of running involves a huge amount of numerical or quantitative data. Many of us who run wear these devices that capture these data. For example, you might keep track of 

- The time elapsed
- The distance you've traveled
- Your heart rate
- The number of calories you've burned 
- And much more. 

Although each piece of information about your run might be useful, it becomes more interesting and useful when you think about how pairs of quantities are related to each other. 

For example, if you look not just at distance you've covered but how that distance relates to the time that's elapsed, you can get a sense of your pace or how fast you've been moving. 

Or, you might look not just at the number of calories you've burned but how that number changes with your heart rate. A relationship between calories and heart rate might reveal some information about your exercise to you -- for example you might find the right "zone" for your heart rate that burns calories at the fastest rate. 

So one of the most useful things we can do with mathematics is to understand the relationships between quantities and express those relationships in ways that help us learn things, make predictions, and tell stories about those quantities. 

Just like in real life, not all relationships are created equal, and in mathematics the most useful kind of relationship between quantities is when a value of one quantity determines exactly one value of the other. 

Let's go back to running and specifically the way time and distance travelled relate to each other. If you give me a specific time on my run, I can look back at the data later and tell you exactly how far I had travelled at that point in time. I can't be in two places at once and so if you give me one time value, there's only one possible distance value I can give back. Distance is *uniquely determined* by time. 

On the other hand think about heart rate and calories burned. It feels like those should be related, but what's the relationship? Suppose you ask, how many calories have I burned when my heart rate is 120 beats per minute? Given the heart rate, what's the calories? However, this question unlike the other one about time and distance doesn't have a unique answer. I might hit 120 bpm early on in my run when I've only burned a few calories. But then I might also be at 120 bpm later, after I've burned a lot of calories and am cooling down. So if you give me a specific heart rate value, I can't necessarily give you a single, unique calorie count. Calories burned is not uniquely determined by heart rate. 

We have a special name for a relationship in which one quantity uniquely determines another: We call it a **function**. 

**A function is a process that may be applied to a collection of input values to produce a corresponding collection of output values in such a way that the process produces one and only one output value for any single input value**.

Put simply, a function is a relationship between two quantities in which one quantity is uniquely determined by the other, so there's an input and an output, like time (input) and distance travelled (output). And the function also tells us HOW to get the output from any given input. 

The input variable in a function is often called the *independent* variable and the output is called the *dependent* variable. They're both called "variables" because they can take on different values, and one depends on the other. 

Some examples: 

- In my running example, distance traveled is the dependent variable and time is the independent variable. We say that distance **is a function of** time. 
- But calories burned was not a function of heart rate, because if you give me a heart rate I can't tell you with certainty what the calorie count was. 
- However, my heart rate could be considered a function of my distance traveled. If you ask me what my heart rate was at, say, the one-mile mark, I can look in my data and tell you what my heart rate was at that point. The heart rate is uniquely determined by distance and they change in tandem with each other. 


Let's take a quick concept check. Another stat that a fitness tracker measures during a run is elevation change -- how much you've climbed or descended during the run. Which of the following is true? 

- Elevation change is a function of time
- Elevation change is a function of distance
- Distance is a function of elevation change 

Pause the video here and think about it, then unpause. 

Let's go through one by one here. We ask the same question each time. 

- If I know the time, does this give me a unique value of elevation change? In this case YES -- It's not possible for my elevation change to be two different things at the same time. So elevation change is a function of time. Time is the independent variable, and elevation change is the dependent variable. 
- If I know the distance I've traveled, does that give me a unique value of elevation change? In this case this is also YES -- if you stop me at any single point of distance along my route, the elevation change at that point can only be one thing, not two. 
- But is distance a function of elevation change? In this case NO, because a single value of elevation change might happen at several different distance values. For example what if I gave you an elevation change of 0 meters -- that will happen at at least two different distance values, namely at the start and at the end of my run, assuming I end at the same place I started. So while distance uniquely determines elevation change, the vice-versa is NOT true. 