# Module 2

[1] Learn the gradient function. Find the convergence. 

[1.1] Mathematic function to find the gradient in 2 dimentional plains. 

f(x,y) = (x-2)^2 + (y+30)^2 + 10
- Here, pair (x,y) can be (2,-30) to get the convergence. Here we find only one possible pair. 

[1.2] Simillaryly, for a 2 dimentional function to have more than 2 possible convergence points. 

f(x,y) = (x+10)^2 * (y-2)^2 + (x-8)^2 * (y+3)^2 + 10 
- Here pair (x,y) possible values are (-10,-3) and (8,2). These values will make the function converge when take the differentiation.


[1.3] Concept of GRADIENT: 
- Gradient is at which rate we need to change the function to reach to convergence point. (minimum point of the function)
- Also, the number of iterations are also important.
-   Sometimes, with higher gradient (gamma) we can reach to convergence quickly (with less iterations). Whereas lower gradient we can reach convergence slowly (need more iteration == expemsive process).
-   Higher gradient might overshoot and we cant reach the convergence point.

- To get the optimal convergence there are a few techniques:
-   [a] clipping the gradient : Put the threshold value, if the differentiation of the function overshoots and move above threshold then move to threshold value.

[1.4] Discussed 4 methods to find the minimal: 
- Brute force method (extremely costly)
- Gradient free
- Nedler Mead
- Gradient Decend

