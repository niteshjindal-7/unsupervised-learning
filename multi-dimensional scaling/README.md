MULTI DIMENSIONAL SCALING (MDS)-

OBJECTIVE FUNCTION FOR MULTI DIMENSIONAL SCALING (MDS)

The objective function for computing the mean of the numbers is, SSE ( Sum of Squared Error): 𝐽(𝑚)=∑𝑁𝑖=1(𝑚−𝑥𝑖)2

The objective function for Principal Component Analysis (PCA) is to maximise the variance in the projected space:

𝐽(𝜔¯) <𝑏𝑟>= 1𝑁∑𝑁𝑛=1(𝜔¯.𝑥(𝑛) − 𝜔¯.𝜇𝑜)2
=  1𝑁∑𝑁𝑛=1𝜔¯𝑇(𝑥(𝑛) − 𝜇𝑜)(𝑥(𝑛) − 𝜇𝑜)𝑇𝜔¯
= 𝜔¯𝑇 [ 1𝑁∑𝑁𝑛=1(𝑥(𝑛) − 𝜇𝑜)(𝑥(𝑛) − 𝜇𝑜)𝑇]ω
[1∗D vector] [D∗D matrix] [D∗1 vector]
where 𝜔¯ is a D∗1 vector, 𝑥𝑖 is a D∗1 vector, .𝜇𝑜 is a D∗1 vector.
Sometimes, the data is not multivariate data, and it is in the pair-wise distance form. [Multi dimensional scaling](https://en.wikipedia.org/wiki/Multidimensional_scaling) is a means of visualizing the level of similarity of individual cases of a dataset.

The objective of MDS is to minimize the pair-wise distance (for all pairs of i and j) in the projected space –
∑𝑖<𝑗(𝑑𝑖𝑗−𝛿𝑖𝑗)2 = ∑𝑖<𝑗(𝑑𝑖𝑗−||𝑥𝑖−𝑥𝑗||)2

Such methods falls under the category of proximity preserving methods as they preserve the proximity in the projected space
where –
𝑑𝑖𝑗 = the pairwise similarity (distance between point i and point j in the original space), which is given to us, and 𝑥𝑖 , 𝑥𝑗 are the parameters to calculate.
