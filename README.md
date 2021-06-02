# USArrests-Clustering-KMeans
Clustering of States according to USArrests using KMeans Algorithm



# About the Dataset

Description
This data set contains statistics, in arrests per 100,000 residents for assault, murder, and rape in each of the 50 US states in 1973. Also given is the percent of the population living in urban areas.

Usage
<br>
USArrests
<br>
<br>
Format
<br>
A data frame with 50 observations on 4 variables. 
<br>
<br>
<br>
<br>

[,1]	Murder	numeric	Murder arrests (per 100,000)
<br>
[,2]	Assault	numeric	Assault arrests (per 100,000)
<br>
[,3]	UrbanPop	numeric	Percent urban population
<br>
[,4]	Rape	numeric	Rape arrests (per 100,000)
<br>
<br>
<br>
Source
<br>
World Almanac and Book of facts 1975. (Crime rates).
<br>
<br>
<br>

Statistical Abstracts of the United States 1975. (Urban rates).
<br>
<br>
<br>

References
<br>
McNeil, D. R. (1977) Interactive Data Analysis. New York: Wiley.





<h2>Requirements</h2>

```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import scipy as sp
from sklearn.cluster import KMeans
from scipy.stats import shapiro
from yellowbrick.cluster import KElbowVisualizer
# !pip install --upgrade matplotlib
# import mpl_toolkits
from mpl_toolkits.mplot3d import Axes3D
```
