# Introduction
Computational complexity has always been a matter of concern when designing alogrithms. As we always want the algorithm to work as fast as possible thus requiring lesser time to execute. Here, we are going to see the bhevioural difference between few time complexity equations of few algorithms. 

1. Logarithmic = θ(log n)
2. Linear = θ(n)
3. Quadratic = θ(n2)
4. Cubic = θ(n3)
5. Polynomial = θ(nk)

The task we are performing here is determining the best performing algorithm using visualization. The choice of language will be python as this language enables easy access to such libraries which can help perform visualizations. The visualizations have been done using the `matplotlib.pyplot` library. The equations have been formed using `numpy` or `Numerical Python` lilbrary.

# Language
- Python

# Libraries
- Matplotlib.pyplot
- Numpy

# Data
The data that will be used in this task will come directly from the user. The input range is flexible and can be set from 1 to positive infinity.

# Methodoloy
The procedure which is being followed here is defining a function and taking the number of points from the user as `n` and for the n^k equation taking `k` as input from the user. The logarithmic equation has been established using the `numpy` library. The resulting function will produce a plot which will have all the graphs generated from the equations and will show the indecating colour of each plot using legend. From the graph the user will be able to determine which function will provide the best results.

# Graph
![](graphs.jpg) 

# Discussion
As we can see from the graph the `Ploynomial = n^k` is increasing exponentially and going upwards on every instance. Thus, we cannot say that this is a good algorithm. Next, if we look at the Quadratic and Cubic equations. We are able to see that both are infact going upwards but not as much as the polynomial equation. But then again this cannot be interpreted as the best algorithm. The final decision is between `linear` and `logarithmic`. Though, both look to be same, but infact the `Logarithmic` equation is a little less than 1 acutally. Thus, making it the most efficient equation of them all.

# Conclusion
Finally, it can be said that Computation Complexity equations containing log take the least time and equations containing polynomials take exponential amount of time.
