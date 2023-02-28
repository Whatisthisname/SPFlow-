# Contains different explorative notebooks I've used to learn this stuff.

Here's a disretized pdf of a normal distribution, constructed as a mixture of non-overlapping uniform distributions:

![alt text](iterative%20subdivision.png)

This can be used again to construct multivariate distributions, by taking the products and weighted sums of the pdfs of the individual variables.

Below is a plot of increasingly discretized pdfs of a normal distribution, using no discretization, discretization of one axis, and discretization of both axes.

![alt text](increasingly%20discretized%20pdf.png)

They produce increasingly inaccurate approximations of the original pdf, but marginalization, conditioning, map estimates, moments, KL divergece, (conditional) likelihood and other operations can be performed on them easily with zero knowledge of gaussians, which might be useful in some cases.