# Project 3 - AMES Housing Data

## Estimating the value of homes from fixed characteristics
- [x] Develop an algorithm to reliability estimate the value of residential houses based on *fixed* characteristics

## Results

Metrics | Score
--------|-------
R2 Score |
RMSE | 

Graph of linear plot

Graph of residual plot

Graph of prediction error plot (?)

Graph of validation curve
Explaination of validation curve

Graph of learning curve
Explanation of learning curve

The workflow for estimating the value of the homes from fixed characteristics

## EDA

### Imputing NA Values

### Columns with little rows

### Multicollinearity
### Correlation Heatmap

Explain which variables to look at

#### Scatter Plot

#### Variance Inflation Factor

### Outliners
Graph of box plots


### Feature Engineering
Bucketize, polynomial features based on lmplot, cross-column

### Label Encoding
``` python
def hello():
  hello
```

### Fixed characteristics vs non-fixed characteristics
Fixed characteristics | Non-fixed characteristics
----------------------|--------------------------
hello | bye bye

### Feature Selection

#### Backward Elimination: Categorical Features and Continuous Features

#### Recursive Features Elimination

#### LassoCV

#### Principal Component Analysis
```python
from sklearn.decomposition import PCA

pca = PCA(n_components = 0.95)
pca.fit(X)

exp_var_ratio = pca.explained_variance_ratio_
```

### Standard Scaling
``` python
from sklearn.base import BaseEstimator, TransformerMixIn

class encode_scale_concat(BaseEstimator, TransformerMixIn):
  def __init__ (self):
  
  def fit (self):
   
  def transform (self):
   
```python
from sklearn.base import BaseEstimator, TransformerMixIn
```
![image tooltip here](/images/assets/image.jpg)
