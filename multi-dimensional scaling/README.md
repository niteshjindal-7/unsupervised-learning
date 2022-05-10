# MULTI DIMENSIONAL SCALING (MDS)- 
<br>
OBJECTIVE FUNCTION FOR MULTI DIMENSIONAL SCALING (MDS)
<br>
<br>
The objective function for computing the mean of the numbers is, SSE ( Sum of Squared Error):

<img src="https://render.githubusercontent.com/render/math?math=J\left(m\right)=\sum_{i=1}^{N}\left(m-x_i\right)^2">

The objective function for Principal Component Analysis (PCA) is to maximise the variance in the projected space:
<br>

<img src="https://render.githubusercontent.com/render/math?math=J\left(\bar{\omega}\right)\">
=<img src="https://render.githubusercontent.com/render/math?math=\ \frac{1}{N}\sum_{n=1}^{N}\left(\bar{\omega}.x^{\left(n\right)}\ -\ \bar{\omega}{.\mu}_o\right)^2">

![equation2](<img src="http://www.sciweavers.org/tex2img.php?eq=%5C%20%5Cfrac%7B1%7D%7BN%7D%5Csum_%7Bn%3D1%7D%5E%7BN%7D%5Cleft%28%5Cbar%7B%5Comega%7D.x%5E%7B%5Cleft%28n%5Cright%29%7D%5C%20-%5C%20%5Cbar%7B%5Comega%7D%7B.%5Cmu%7D_o%5Cright%29%5E2&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="\ \frac{1}{N}\sum_{n=1}^{N}\left(\bar{\omega}.x^{\left(n\right)}\ -\ \bar{\omega}{.\mu}_o\right)^2" width="190" height="51" />)

<br>
=![equation3](<img src="http://www.sciweavers.org/tex2img.php?eq=%5C%20%5Cfrac%7B1%7D%7BN%7D%5Csum_%7Bn%3D1%7D%5E%7BN%7D%7B%7B%7B%7B%5Cbar%7B%5Comega%7D%7D%5ET%28x%7D%5E%7B%5Cleft%28n%5Cright%29%7D%5C%20-%5C%20%5Cmu_o%29%28x%7D%5E%7B%5Cleft%28n%5Cright%29%7D%5C%20-%5C%20%5Cmu_o%29%7D%5ET%5Cbar%7B%5Comega%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="\ \frac{1}{N}\sum_{n=1}^{N}{{{{\bar{\omega}}^T(x}^{\left(n\right)}\ -\ \mu_o)(x}^{\left(n\right)}\ -\ \mu_o)}^T\bar{\omega}" width="287" height="51" />)

<br>
[eqn4](<img src="http://www.sciweavers.org/tex2img.php?eq=%7B%5Cbar%7B%5Comega%7D%7D%5ET%5C%20%5B%5C%20%5Cfrac%7B1%7D%7BN%7D%5Csum_%7Bn%3D1%7D%5E%7BN%7D%7B%7B%7B%28x%7D%5E%7B%5Cleft%28n%5Cright%29%7D%5C%20-%5C%20%5Cmu_o%29%28x%7D%5E%7B%5Cleft%28n%5Cright%29%7D%5C%20-%5C%20%5Cmu_o%29%7D%5ET%5D%7B%5Comega%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="{\bar{\omega}}^T\ [\ \frac{1}{N}\sum_{n=1}^{N}{{{(x}^{\left(n\right)}\ -\ \mu_o)(x}^{\left(n\right)}\ -\ \mu_o)}^T]{\omega}" width="315" height="51" />)

<br>
[1$*$D vector]	         [D$*$D matrix] 	 [D$*$1 vector]	
<br>
where $\bar{\omega}$ is a D$*$1 vector,  $x_i$ is a D$*$1 vector, ${.\mu}_o$ is a D$*$1 vector.
<br>
<br>
Sometimes, the data is not multivariate data, and it is in the pair-wise distance form. [Multi dimensional scaling](https://en.wikipedia.org/wiki/Multidimensional_scaling) is a means of visualizing the level of similarity of individual cases of a dataset.
<mds1>
<br>
<br>
The objective of MDS is to minimize the pair-wise distance (for all pairs of i and j) in the projected space –
<br>
$\sum_{i<j}\left(d_{ij}-\delta_{ij}\right)^2$  = $\sum_{i<j}\left(d_{ij}-||x_i-x_j||\right)^2$
<br><br>
Such methods falls under the category of proximity preserving methods as they preserve the proximity in the projected space 
<br>
where –
<br>
 $d_{ij}$ = the pairwise similarity (distance between point i and point j in the original space), which is given to us, and $x_i$ , $x_j$ are the parameters to calculate.

