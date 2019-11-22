# Machine Learning Notebooks
I collect various Jupyter notebooks of ML projects I worked on in this repository.

## Case Study -- Mines vs Rocks
This is a very small data set (208 rows) which is also wide (60 predictor variables). I investigated the effects of small sample size in the notebook. I tend to use the year we are in (2019 in this case) as the random number generator seed and I realized that I got very lucky in this dataset as a result; I got perfect recall! If I had worked on it in a different year, the result would have been drastically different. Therefore, I averaged the performance of my models using different seeds in order to reduce the variance.
