# MULTI DIMENSIONAL SCALING (MDS)- 
<br>

<br>
<br>
The objective function for computing the mean of the numbers is, SSE ( Sum of Squared Error):

<img src="https://render.githubusercontent.com/render/math?math=J\left(m\right)=\sum_{i=1}^{N}\left(m-x_i\right)^2">

The objective function for Principal Component Analysis (PCA) is to maximise the variance in the projected space:
<br><br>
<img src="https://render.githubusercontent.com/render/math?math=J\left(\bar{\omega}\right)"> 
<br><br>
= <img src="https://render.githubusercontent.com/render/math?math=\ \frac{1}{N}\sum_{n=1}^{N}\left(\bar{\omega}.x^{\left(n\right)}\ -\ \bar{\omega}{.\mu}_o\right)^2"> 
<br><br>
= <img src="https://render.githubusercontent.com/render/math?math=\ \frac{1}{N}\sum_{n=1}^{N}{{{{\bar{\omega}}^T(x}^{\left(n\right)}\ -\ \mu_o)(x}^{\left(n\right)}\ -\ \mu_o)}^T\bar{\omega}">
<br><br>
= <img src="https://render.githubusercontent.com/render/math?math={\bar{\omega}}^T\ [\ \frac{1}{N}\sum_{n=1}^{N}{{{(x}^{\left(n\right)}\ -\ \mu_o)(x}^{\left(n\right)}\ -\ \mu_o)}^T]{\omega}">

= [1 * D vector]	         [D * D matrix] 	 [D * 1 vector]	

<br>
where

 <img src="https://render.githubusercontent.com/render/math?math=\bar{\omega}"> is D*1 vector

 <img src="https://render.githubusercontent.com/render/math?math=x_i"> is D*1 vector

 <img src="https://render.githubusercontent.com/render/math?math={.\mu}_o"> is D*1 vector

<br>
OBJECTIVE FUNCTION FOR MULTI DIMENSIONAL SCALING (MDS)

Sometimes, the data is not multivariate data, and it is in the pair-wise distance form. [Multi dimensional scaling](https://en.wikipedia.org/wiki/Multidimensional_scaling) is a means of visualizing the level of similarity of individual cases of a dataset.
<mds1>
<br>
The objective of MDS is to minimize the pair-wise distance (for all pairs of i and j) in the projected space –
<br>
<img src="https://render.githubusercontent.com/render/math?math=\sum_{i<j}\left(d_{ij}-\delta_{ij}\right)^2"> 
= <img src="https://render.githubusercontent.com/render/math?math=\sum_{i<j}\left(d_{ij}-||x_i-x_j||\right)^2"> 
 
<br>
Such methods falls under the category of proximity preserving methods as they preserve the proximity in the projected space 
<br>
where
<br>
<img src="https://render.githubusercontent.com/render/math?math=d_{ij}"> = the pairwise similarity (distance between point i and point j in the original space), which is given to us, and x_i , x_j are the parameters to calculate.

