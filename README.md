# PCA

PCA stands for principle component Analysis

PCA is used for dimensionality reduction

PCA works on the concept of maximizing the vaiance of the projected data points


# steps to perform PCA

consider a matrix Xnxd.

1.standardise the columns

2.caluclate the covariance of matrix
        
        Adxd = X.T*X

3.caluculate the eigen values and eigen vectors of the covariance matrix A
        
        1.eigen values tells us how the data is spread
        2.eigen vectors tells us the direction of variance

4.select the principal components(consider larger values)


# Limitations of PCA

1.PCA is sensitive to the relative scaling of the original variables.

2.Indépendant variables become less interpretable

3.sometimes we may loss Information as we are selecting vectors with larger values


Dataset used:
      https://www.kaggle.com/competitions/digit-recognizer/data
