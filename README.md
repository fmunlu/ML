# Machine Learning Notebooks
I collect various Jupyter notebooks of ML projects I worked on in this repository.

### Case Study -- Mines vs Rocks
This is a very small data set (208 rows) which is also wide (60 predictor variables). I investigated the effects of small sample size in the notebook. I tend to use the year we are in (2019 in this case) as the random number generator seed and I realized that I got very lucky in this dataset as a result; I got perfect recall! If I had worked on it in a different year, the result would have been drastically different. Therefore, I averaged the performance of my models using different seeds in order to reduce the variance.

### Support Vector Identification
When I was learning the theory of Support Vector Machines (SVM) from the awesome book titled 'An Introduction to Statistical Learning with Applications in R' of James, Witten, Hastie and Tibshirani (which is made freely available by the authors, hint: just google it), I had to disagree with the authors on a simple case of counting.
In one of the figures (the bottom right one on page 348), the authors say that there are eight support vectors and I counted nine! (I am including the figure here for quick reference). As a result, I simulated some data, fitted SVMs, and identified the support vectors to check my understanding of the concept.
