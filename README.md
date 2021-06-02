# USArrests-Clustering-KMeans
Clustering of States according to USArrests using KMeans Algorithm



# About the Dataset

Description
This data set contains statistics, in arrests per 100,000 residents for assault, murder, and rape in each of the 50 US states in 1973. Also given is the percent of the population living in urban areas.

Usage
USArrests
Format
A data frame with 50 observations on 4 variables.

[,1]	Murder	numeric	Murder arrests (per 100,000)
[,2]	Assault	numeric	Assault arrests (per 100,000)
[,3]	UrbanPop	numeric	Percent urban population
[,4]	Rape	numeric	Rape arrests (per 100,000)
Source
World Almanac and Book of facts 1975. (Crime rates).

Statistical Abstracts of the United States 1975. (Urban rates).

References
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
