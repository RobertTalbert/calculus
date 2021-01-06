In the last two videos we've been learning how to combine two functions to produce a third one. Here we want to turn this around and take a function that seems to be a combination of two others, and understand what those two functions are that were combined, and also HOW they were combined. This is going to be very important later because taking complex functions and breaking them down into their simpler component parts along with a rough sense of how they were assembled will be the key for solving a lot of problems. 

The best way to do this is just by example. 

So look at A(x) = x^3 + 2^x. Although it's a somewhat complicated function, I can see that *fundamentally*, this function is a sum of two smaller functions: f(x) = x^3 and g(x) = 2^x. The *fundamental algebraic structure* of A(x) is that it's a sum. A way that I can see this, is that if I were to evaluate A at a single point, like A(2), trace the steps I'd have to perform to find the output. I'd need to put 2 in for x here and cube it, then put 2 in for x here and find 2^2, then add. So I perform two smaller actions, then add. That makes this function a sum and I can tell that the smaller functions are cubing and raising as a power of 2. 

Now look at B(x) = x^3/(x+1). Fundamentally this function is a quotient of two smaller ones, namely f(x) = x^3 and g(x) = x+1. Again if I were to evaluate B at a point, like 2, I'd find the output by doing x^3 first then doing x+1 second then dividing. 

Finally look at C(x) = sqrt(x^2 + x + 1). What's this? I see there's some summing here, but there's also a square root. Well, in this case C(x) is fundamentally a composite of two functions. Again look at evaluating at a single point, x = 2 for instance. To find C(2) I have to do two things: First evaluate 2^2 + 2 + 1 (which happens to be 7) then take the square root. This is not addition, subtraction, multiplication or division but rather evaluating one function then using the output as the input for another. That's a composition -- and this is what C(x) fundamentally is. 

This is kind of subtle, so let's give you a chance to try. Here are three functions. Pause the video, think about them, and decide on their fundamental algebraic structure --- sum, difference, product, quotient, or composite. THen unpause when you're done. 

1 + sqrt(x)
(x+1)*sqrt(x)
(1/(x^2 + 1))^3/2

The first function is fundamentally a SUM because we are just taking two simple functions -- the constant function 1 and the function sqrt(x) and adding them. 

The second function is fundamentally a PRODUCT because we are taking two smaller functions y=x+1 and y = sqrt(x) and multiplying them. 

Finally the last function is fundamentally a COMPOSITE because it involves taking the function g(x) = 1/x^2 + 1 and evaluating that into the function f(x) = x^(3/2). Again to see this, try evaluating at a single point like x = 1. You'd have to run it through the 1/x^2 + 1 function first, then take the output and run that through the function x^(3/2). 

Thanks for watching.
