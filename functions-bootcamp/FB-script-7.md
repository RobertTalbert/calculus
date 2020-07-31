There's another way to combine two functions to get a new function besides doing arithmetic. It happens when we "chain" two functions together by evaluating one, then using the output as the input for the other. 

Here's an example. We know that the area of a circle is a function of its radius via the formula A = pi r^2. Let's suppose you are having some fun and dive off a high cliff into a deep pool of water. When you hit the water, it creates a circular ripple that expands outward. If you look at that ripple there are two functions happening. On the one hand, the ripple has an area that's equal to pi r^2. But on the other hand the input variable for the area, radius, is itself a function because it changes with time. So we have a chain reaction: Time causes the radius to change, and the radius then causes the area to change. Therefore instead of asking a question like "What's the area when the radius is 2 meters?" we might ask "What's the area 1 second after I hit the water?"

Let's say the radius as a function of time is given by this table. If I want to answer the question "What's the area 1 second after I hit the water?" I would have to do two steps in order: First, evaluate the radius function when time = 1, then take the output of that process --- the radius --- and put that into the formula for area. 

We can think about this "chaining" process more generally. Let's say f(t) = t^2(t-1) and g(t) = t+5. Then I can chain these two together by evaluating g at an input, then recycling it to use as the input for f. For example g(2) = 2+5 or 7; and then I can plug that into f to get f(7) = 7^2(7-1) which is 294. Using function notation, what I just did was find g(2) then put that into f, so that's f(g(2)). Note that this isn't multiplication -- it's starting with 2, then putting that into g, then putting the output into f. 

This process of chaining two functions together and using the output of one as the input of the other is called COMPOSITION. It's fundamentally different from adding, subtracting, multiplying or dividing. In general, if f and g are functions so that the outputs of g can be used as the inputs of f, then the composition of f and g is a new function h given by h(t) = f(g(t)). This again is not multiplication but instead repeated function evaluation. WE also sometimes use an open circle for this: (f o g)(t) which means f(g(t)). 

Let's look at some examples. 

First, let f(t) = 1/(t+1) and g(t) = t^3. First, what's (fog)(2)? Well, (fog)(2) means f(g(2)) which means find g(2), then take the result evaluate f at whatever it equals. So step 1 g(2) is 2^3 which is 8. So now I find f(g(2)) which is f(8). That's 1/(8+1) or 1/9. 

What if you reversed the order? Well, (gof)(2) is g(f(2)) and that means find f(2) first, which is 1/(2+1) or 1/3. THen I need to take that and put it into g: g(f(2)) = g(1/3) = (1/3)^3 = 1/27. 

So notice the results are different, which isn't surprising because whenever you have a process that consists of two steps done in a particular order, reversing the steps doesn't typically give you the same results. For example you brush your teeth by first putting toothpaste on the brush and then scrubbing your mouth. If you scrubbed your mouth first and THEN put on the toothpaste... it wouldn't be the same. 

We can also compose these two functions in general just using their formulas. For any t value, a formula for (fog)(t) is f(g(t)), which is f(t^3). Like we mentioned earlier this just means go to the formula for f and replace all the "t" expressions with f^3. That gives 1/(t^3 + 1). 

Let's look at one more example using different representations. A(x) is given by this table and B(x) is given by this graph. 

A(x) = (0,2), (1,3), (2,0), (3,1)
g\left(t\right)=\sin\left(\pi t\right)+\frac{1}{2}t

What is (BoA)(1)? Well again, this means B(A(1)). So find A(1) first, then take the result and evaluate it into B. A(1) according to the table is 3. So now feed that into B, and the graph tells us that B(3) is 1.5. So (BoA)(1) = 1.5. As with combining functions via arithmetic, it doesn't matter that the functions are in different representations as long as we can find and evaluate individual values. 

Thanks for watching. 