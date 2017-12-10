# machine-learning

Exploring a variety of machine learning methods and data analysis.

## Author

Mark Reynoso created this code base as a project for Python 401 at Code Fellows Seattle. 

### Requirements for testing and development

In order to create a development and testing environment, you will need the following:
```
python3, pytest, tox
```

#### Create a virtual environment in the root of repository.

```
python3 -m venv ENV

source ENV/bin/activate
```

```
Install in environment:

pip install jupyter notebook

to run:

jupyter notebook

```


#### Boston Housing Data Analysis

_Introduction to Data_ * quoted from https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html

"This dataset contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. It was obtained from the StatLib archive (http://lib.stat.cmu.edu/datasets/boston), and has been used extensively throughout the literature to benchmark algorithms. However, these comparisons were primarily done outside of Delve and are thus somewhat suspect. The dataset is small in size with only 506 cases."

* The data was originally published by Harrison, D. and Rubinfeld, D.L. Hedonic prices and the demand for clean air', J. Environ. Economics & Management, vol.5, 81-102, 1978.
* Data used via uci.edu

_Categories_

- CRIM     – per capita crime rate by town
- ZN     – proportion of residential land zoned for lots over 25,000 sq.ft
- INDUS     – proportion of non-retail business acres per town
- CHAS     – Charles River dummy variable (1 if tract bounds river; else 0)
- NOX     – nitric oxides concentration (parts per 10 million)
- RM     – average number of rooms per dwelling
- AGE     – proportion of owner-occupied units built prior to 1940
- DIS     – weighted distances to five Boston employment centres
- RAD     – index of accessibility to radial highways
- TAX     – full-value property-tax rate per $10,000
- PTRATIO     – pupil-teacher ratio by town
- B     – 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT     – % lower status of the population
- MEDV     – Median value of owner-occupied homes in $1000’s

_Analysis_

Using this data I have visualized four plots which consider the given data and any inferences that may be made given their result. 
- Relationship between per-capita crime rate and the pupil-teacher ratio. Also considering whether the locaion of a given area is bound by the Charles River and any impact which may be drawn from this. 
- Relationship between the proportion of black citizens and the distance to employment centers in Boston. 
- The relationship between median value of owner-occuped homes and nitric oxide concentration & median home value and the proportion of non-retail business.
- The relationship between crime per capita and an areas proximity to radial highway systems. 
